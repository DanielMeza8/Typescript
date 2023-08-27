En Typescript se puede encontrar diferentes formas de hacer una función, estas están hechas poder ser ocupadas de acuerdo a las necesidades de cada programador.

##### **Ejemplo de funciones en Ts**

```TS
(() => {

    function saludar() {

        return "hola mundo";

    }

  

    console.log(saludar());

  

    function despedida(nombre) {

        return `hola ${nombre}`;

    }

  

    console.log(despedida("Jorge"));

  
  

    //Funcion anonima

  

    let saludarAnonima = function (){

        return "hola que tal";

    }

    console.log(saludarAnonima());

  
  
  

    //Funcion flecha

    let despedirFlecha = () => {

        return "hasta luego nos vemos pronto";

    }

  

    console.log(despedirFlecha());

  
  

    //Funciones Asincronas

    //Estas realizan tareas que puedan tardar ejemplo conectarte a una bd, consumir grande cantidades de datos, tareas que tarden ul largo periodo de tiempo en realizarce

  

    // async function conexionBD(url:string) {

    //     await setTimeout(() => {

    //         console.log(`Conexion realizada con exito ${url}`);

    //     }, 3000); //-> 3 segundo

    // }

  

    // console.log(conexionBD("mongo"));

  
  
  

})()
```
