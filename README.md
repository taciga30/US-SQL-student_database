# Student Database

## 1. Tutoriales
[Workspaces](https://gitpod.io/workspaces)

### Tutorial 1
[Tutorial 1 en Gitpod](https://laboratoria-learnsqlbyb-157dmfm7f9w.ws-us115.gitpod.io/)
<p>Se aprenderió a construir y gestionar una base de datos de estudiantes utilizando SQL y PostgreSQL, configurando el entorno
necesario, que incluye la instalación de PostgreSQL y el uso de máquinas virtuales. A través de comandos SQL se hizo la 
creación de tablas con claves primarias y foráneas, la inserción y consulta de datos, y la actualización y eliminación de 
registros. Además, se explororó el uso de scripts Bash para automatizar tareas y gestionar permisos de archivos.
</p>
<details><summary>Pasos que se siguieron en la terminal:</summary><p>

#### Paso 1

   `echo sql Hello`

#### Paso 2

   `touch insert_data.sh`

#### Paso 3

   `chmod +x insert_data.sh`

#### Paso 4

   `./insert_data.sh`
    
#### Paso 5

   `declare -p IFS`  
      
#### Paso 6

   `cp courses.csv courses_test.csv`  
    
#### Paso 7

   `./insert_data.sh`  
    
#### Paso 8

   `psql --username=freecodecamp --dbname=postgres`  
    
#### Paso 9

   `psql --username=freecodecamp --dbname=students`  
    
#### Paso 10

   `cp students.csv students_test.csv`  
    
#### Paso 11

   `./insert_data.sh`  
    
#### Paso 12

   `ls`  
    
#### Paso 13

   `rm students_test.csv`  
    
#### Paso 14

   `rm courses_test.csv`  
    
#### Paso 15

   `ls`  
    
#### Paso 16

   `pg_dump --help`  
    
#### Paso 17

   `pg_dump --clean --create --inserts --username=freecodecamp students > students.sql`  

</p></details>

### Tutorial 2
[Tutorial 2 en Gitpod](https://laboratoria-learnsqlbyb-ovydaek8ozl.ws-us115.gitpod.io/)
<p>En el segundo tutorial, se profundizó en la administración y análisis
de bases de datos de estudiantes usando SQL y PostgreSQL. Se
realizaron consultas avanzadas mediante JOIN para combinar datos de múltiples
tablas y se utilizaron funciones de agrupamiento (GROUP BY) y ordenamiento
(ORDER BY). Se cubrieron también las funciones agregadas para sumarizar
datos y la modificación de estructuras de tablas existentes con ALTER TABLE.
Esta parte incluye la creación de copias de seguridad y restauración
de bases de datos, y el uso de scripts Bash para una gestión más
eficiente y segura de tu entorno.
</p>
<details><summary>Pasos que se siguieron en la terminal:</summary><p>

#### Paso 1

   `echo sql Hello`

#### Paso 2

   `psql -U postgres < students.sql`

#### Paso 3

   `\c`

#### Paso 4

   `touch student_info.sh`
    
#### Paso 5

   `chmod +x student_info.sh`  
      
#### Paso 6

   `./student_info.sh`  
     

</p></details>













