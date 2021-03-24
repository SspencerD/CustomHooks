#UseForm

Ejemplo de uso:
```

// estructuración del initialForm
const initialForm ={
    name:'',
    lastname:'',
    age:'',
    email:''
};

const [formValues, handleInputChange, reset ] = UseForm( initialForm );

```
Se realiza la inicialización del form con la estructura formada, según el ejemplo para implimentarlo dentro del arreglo del UseForm