# CASOS
Casos practicos de POO

# Practica No.1
- Cree una cuenta de usuario en GitHub, recuerde su usuario, email y password para su cuenta
- Usted es ahora parte del repositorio progra2019/CASOS

# Ingresar a Git Bash
1. Cree una carpeta (Ejercicio)en su computador
2. Ingrese a su carpeta(Ejercicio), de click derecho dentro de ella y elija la opcion Git Bash Here
3. Configurar usuario correo e inicializar Git
- git config --global user.name TuNombredeGitHub 
- git config --globañ user.email TuemaildeGirHub
- git init
4. Verificar el estado del git
-   git config -l
5. Verificar que se encuentra dentro de la carpeta (Ejercicio) creada 
- pwd
- Sino se encuentra en la carpeta (Ejercicio) recuerde debe ingresar con 
- CD NombreCarpeta
6. Clonar el repositorio  
- git clone url_NombreRepositorio
7. cambiarse dentro del nuevo repositorio clonado
- cd CASOS
8. Listar los archivos con 
- ls
9. Modificar archivos y subir al Repositorio 
- Modificar el archivo Nombres.txt, inserte su nombre y guarde en windows
- Modificar el archivo Colegio.txt, inserte su colegio y guarde en windows
10. Comprobar el estado de los archivos con 
- git status, verifique que sus archivos modificados esten en rojo
11. Suba el archivo al repositorio local o STAGE  instruccion con
- git add Nombres.txt
- git add Colegio.txt
12. verifique que sus archivos modificados esten en verde 
- git status
13. preparar el archivo para el repositorio 
- git commit -m "Actualizacion realizada por: ponga su nombre"
14. Poner los cambios en el reposotio web
- git push --set-upstream origin master
15. Si no le deja actualizar sus datos es por que algun otro contibuyente ya modifico la información. 
por lo tanto debe descargarse las actualizaciones y repetir desde el paso 9
- git pull

# Verificar el cambio en GITHUB
1. Ingrese a GitHub con su usuario
2. Ingrese al repositorio
3. Actualice la pagina web
4. Debe estar el archivo de Nombres.txt y Colegio.txt actualizado


