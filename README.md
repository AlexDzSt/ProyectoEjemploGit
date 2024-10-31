# Práctica 1:Introduccion a Git

## Descripción
Este programa imprime un mensaje en la consola. El objetivo de esta práctica es aprender a utilizar los comandos básicos de Git.

## Instrucciones de uso
Ejecuta el programa desde la terminal utilizando el siguiente comando:
```
python HolaMundo.py
```

## Comandos utilizados
```
git init
git add <nombreArchivo>
git commit -m "mensaje"
git status
git remote add origin <URL>
git push -u origin master
```

## Notas sobre el archivo .gitignore
El archivo .gitignore se creo para ignorar archivos innecesarios como los archivos .log. Este archivo evita que debug.log se suba al repositorio.

## Resultados esperados
El programa debe mostrar el mensaje "Hola Git" en la consola. Al verificar en GitHub el archivo debug.log no debe aparecer en el repositorio.