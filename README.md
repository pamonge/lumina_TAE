# Comandos de GIT
Iniciar repositorio: git init
Ver status del proyecto: git status (Muestra archivos con y sin seguimiento)
descargar repositorio: git pull origin <rama> (main, master, ...)
Subir repositorio: git push origin <rama> (main, master, ...)
cambiar de rama: gir checkout <rama> (main, master, prod, ...)
cambiar nombre de la rama: git branch -M <nombre> (hay que estar en la rama para renombrar)
agregar archivos al seguimiento: git add nombre_del_archivo.extencion
agregar todos los archivos: git add .
agregar un commit: git commit -m 'comentario del commit'

## Orden Logico

1. Antes de empezar a trabajar: hacer git pull
2. ver los cambios: git status
3. Agregar cambios: git add .
4. Agregar el commit
5. Hacer el push 
