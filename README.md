# comandos-git

Esta es una lista de comandos de Git más utilizados:


### Clonar un repositorio de git

```
git clone urldelrepositorioremoto.git
```

### Iniciar un repositorio de git
```
git init
```

### Agregar un archivo o varios a git
```
# Un Archivo
git add /ruta/nombredelarchivo.extension

# Varios archivos
git add .
```

### Comprobar el estado de los archivos de la carpeta
```
git status
```

### Hacer un commit de los cambios agregados
```
git commit -m "Mensaje del commit"
```

### Enviar los commit al repositorio remoto de git
```
git push -u origin nombredelarama

git push
```
### Descargar los cambios y ramas de repositorio de git sin aplicarlos a los cambios locales
```
git fetch --all
```

### Descargar los cambios de un repositorio de git remoto (Ya clonado) en la rama que te encuentras
```
git pull
```

### Crear una rama localmente
```
git branch nombredelarama
```

### Cambiar de rama localmente
```
git checkout nombredelarama
```

### Eliminar una rama localmente

```
git branch -d nombredelarama
```

### Descartar los cambios que aun no han sido agregados
```
#Un solo archivo
git checkout nombredelarchivo

#Varios archivos
git checkout .
```

