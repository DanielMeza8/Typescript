*Para poder usar los parámetros de invocación en Typescript necesitamos decirle que tipo de dato o datos puede recibir ese parámetro, al igual podemos hacer que los parámetros ya se encuentren con datos que estos a la vez pueden ser sustituidos por el usuario pero que no importa si alguno no es rellenado con INFO

```TS
(() => {

    function saludarPorNombre(nombre:string, apellidop:string, apellidom:string, edad:number) {

        return `Hola ${nombre} ${apellidop} ${apellidom}, tu edad es ${edad}`;

    }

  

    console.log(saludarPorNombre("Jorge Daniel", "Meza", "Romero", 25));

  
  
  

    //parametros opcionales

  

    function despedirPorNombre(nombre:string ="Alejandra", apellidop:string = "Yandari", apellidom:string = "Meza", edad:number = 4) {

        return `Adios ${nombre} ${apellidop} ${apellidom}, tu edad es ${edad}`;

    }

  

    console.log(despedirPorNombre());

})()
```
