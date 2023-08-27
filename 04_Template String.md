Al ocupar las Template String estas nos ayudaran para hacer que todo parezca que se invoca como un texto plano cuando en realidad se esta haciendo referencia a una variable, objeto, método
```NOTE
Estructura de una template String
${}
```

```TS
(() => {

    let nombre:string = "Daniel";

    function obtenerapellido() {

        return "Daniel Meza";

    }

    console.log("hola " + nombre);

    console.log(`mi nombre es ${nombre}`);

    console.log(`mi nombre es ${obtenerapellido()}`);

})()
```

