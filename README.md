
## Proyecto de Blog para práctica del curso de [Redux por bedu](https://platzi.com) de [Platzi](https://platzi.com/cursos/redux/)


`npm start`
Para iniciar el proyecto en modo desarrollo en el puerto 3000
___

### Resúmen del curso
#### Ciclo de vida de componentes en React

**Tenemos 4 fases por los que un componente pasa:**
- *Initialization:* Declaramos nuestro estado o propiedades
- *Mounting:* Todo componente debe tener render. Es obligatorio.
- *Updation*
- *Unmounting:* Solo hay una función en caso de que queramos hacer algo cuando se destruya un componente

![Ciclo de vida de componentes en React](https://github.com/ArielAyala/blog_platzi_react_redux/blob/master/src/imagenes_resumen/ciclo%20de%20vida%20de%20componentes%20react.png?raw=true)

#### Manejo de promesas
Una **Promesa** es un proxy para un valor no necesariamente conocido en el momento que es creada la promesa.
Las promesas tienen tres estados:
- pending
- fullfilled
- rejected

Las promesas se invocan de la siguiente forma:

```js
new  Promise( ( resolve, reject ) => {
// --- llamado asíncrono 
        if( todoOK ) { 
        // -- se ejecutó el llamado exitosamente resolve() }
        else { 
        // -- hubo un error en el llamado reject() 
        } 
} )
```

