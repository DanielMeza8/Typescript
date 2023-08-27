# Requerimientos
- Node JS
- Visual Studio Code 

## Pasos crear un proyecto en Typescript
1. Generar una carpeta en la cual contendrá el archivo .ts
2. Generar el archivo .ts **ejemplo: main.ts**
```TS
// ejemplo de codigo en Typescript
console.log("Hola mundo");
```

```NOTE
Typescript es muy parecido en JavasScript al escribir codigo, la diferencia es que no existe la inmutabilidad ya que es un lenguaje de tipo Tipado.
```

### Como ejecutar el programa de TS

1. Generamos el archivo de configuración en nuestra carpeta con el comando: **TSC --init** 

```NOTE
Si la terminal no deja ejecutar comandos ejecutaremos el siguiente comando que nos permitira remover los permisos y poder ejecutar comando con node
Set_ExecutionPolicy Unrestricted ----> aprobar el uso de scripts en terminal
```
2. Ejecutamos el comando  **tsc .\main.ts**. 
```NOTE
Este comando generará un archivo .js que es el que al final sera ejecutado
```
3. Ejecutamos el archivo .js que se generó con el comando node .\main.js




