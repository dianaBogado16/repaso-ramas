README.md
#clase 06 -bootcamp

## Repaso git

## creo el repositorio de GIT

```sh
git init
```

## Listo el estado de los archivos

```sh
git status
```

## Haciendo un commit

1. Agrego(al staging area) los archivos que necesito que formen parte del commit

```sh
git add nombre_archivo
git add nombre_archivo nombre_archivo nombre_archivo
git add 
<!-- el ultimo comando agrega todos los archivos -->
```

2. Hago el commit

```sh
git commit -m"comentario descriptivo"
```

# Cambair el editor por nano
```sh
git config --global core.editor nano
git config --global core.editor "code --wait"
```

# Ver el listado de commits que hice en el repo

```sh
git log # version larga
git log --oneline # version corta

```

# Para ver si se agrego el repo remoto
```sh
git remote -v
```


## subo al remoto el repositorio local

```sh
git push -u origin main # la primera vez
git push # ya las proximas veces solo uso este comando (con la rama main)
```

## Para recuperar un codigo luego de una catastrofe, lo que hago es
Ir al repositorio de github, hacer click sobre el boton code y copiar la url a mi repositorio
```sh
git clone <url-al-repositorio> ./ #clona en el directorio actual
git clone <url-al-repositorio> #Crea una carpeta (repaso-ramas) y clona el repositorio remoto al local
```
