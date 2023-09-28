### Configuracion Inicial 

Para todos los repositorio que se creen
```shell
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

Solo en el repositorio actual
```shell
git config user.name "Tu Nombre"
git config user.email "tu@email.com"
```


Crear un repositorio

```shell
git init
```

Realizar seguimiento de archivos

```shell
git add <nombre_del_archivo>
git add -A 
git add .
git add *
```

Confirmar cambios
```shell
git commit -m "Mensaje descriptivo de los cambios"
```
