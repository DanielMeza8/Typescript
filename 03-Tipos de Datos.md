En Typescript al igual que en otros los lenguajes de programación de alto nivel se poseen tipos de datos en la cual nos da un mejor manejo del software.

```TS
(() => {

    let cadena:string = "Hola mundo";

    let numeros:number = -8; //enteros, decimales, negativos

    let bolean:boolean = true;
  
    let cualquierDatos:any = true; //mala practica al menos que sea extricto usarlo

    let variosTiposDatos:number | string = 345; //

    let variosTiposDatos2:number | boolean = true; //

})()
```


## *Estructura de una función que se invoca sola*

```TS
(() => {
	// codigo
})()
```
