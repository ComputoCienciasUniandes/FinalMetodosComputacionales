# Instrucciones

1. Desde su cuenta de github pulse el boton de 'fork' en https://github.com/ComputoCienciasUniandes/FinalMetodosComputacionales
2. En una nueva ventana del navegador escriba la direccion: `https://mybinder.org/v2/gh/usuario/FinalMetodosComputacionales/master?urlpath=lab`, cambiando `usuario` por su nombre de usuario de github.
3. Edite cada uno de los archivos .py con la respuesta correspondiente.
4. En File->New->Terminal puede abrir una terminal para probar el codigo.
5. En la misma terminal utilice git para subir el codigo con las respuestas.

# Nota
Si van a usar matplotlib dentro de un programa deben escribir

```
import matplotlib
matplotlib.use('Agg')
import matplotlib.pyplot as plt
```

Para luego poder usar `plt`
