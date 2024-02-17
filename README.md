# Lab 3
# **Laboratorio 3**

## **CREAR UN PROYECTO CON MAVEN**
Usamos este código para crear el proyecto maven con la información dada
``````
 mvn archetype:generate   
 -DgroupId=edu.eci.cvds   
 -DartifactId=ClasesEquivalencia   
 -Dversion=1.0.0   
 -Dpackage=edu.eci.cvds.tdd   
 -DarchetypeGroupId=org.apache.maven.archetypes   
 -DarchetypeArtifactId=maven-archetype-quickstart   
 -DinteractiveMode=false
``````
![image](https://github.com/andreec2/cvds-lab3--Monroy-Montes-/assets/111905757/4cd8d5e4-be1e-4651-a039-1105e50c1ff1)

## **ACTUALIZAR Y CREAR DEPENDENCIAS EN EL PROYECTO
Una vez dentro del repositorio central de Maven, buscamos JUnit y seleccionamos la siguiente opción:
![image](https://github.com/andreec2/cvds-lab3--Monroy-Montes-/assets/111905757/5371a415-12f8-413d-a705-84992b6b1736)

Luego de esto seleccionaresmos la última versión (en este caso la 4.13.2)
![image](https://github.com/andreec2/cvds-lab3--Monroy-Montes-/assets/111905757/532158e1-2406-4e1d-a36b-dada54da84c9)

Y encontraremos la parte del código que debemos adicionar en el pom.xml
![image](https://github.com/andreec2/cvds-lab3--Monroy-Montes-/assets/111905757/356cc70b-1b75-4530-bd6d-649c61e9bf03)

Usamos algún editor de texto para modificar el pom.xml
![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/5daa69dd-e5be-4c29-ab14-d09b22d99376)


## **COMPILAR Y EJECUTAR**
Usamos el siguiente comando para copilar:
``````
mvn compile
``````
![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/f425399c-7b34-42aa-ba20-358425c87c39)

Ahora ejecutamos las pruebas con el sieguiente comando:
``````
mvn test
``````
![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/3fb0acd0-9243-4e27-8426-5ce9e00b9e97)

## **EJECUTAR LAS PRUEBAS**

El comando mvn test y mvn package son dos comandos de Maven utilizados para diferentes propósitos en el ciclo de vida de desarrollo de un proyecto.

mvn test: Este comando ejecuta todas las pruebas unitarias definidas en tu proyecto. Las pruebas unitarias son programas de código que verifican el comportamiento de componentes individuales (como clases o métodos) de tu código. Al ejecutar mvn test, Maven compila el código fuente y luego ejecuta todas las pruebas unitarias definidas en tu proyecto. Si alguna prueba falla, Maven te informará sobre los fallos y los detalles de las pruebas que fallaron.

mvn package: Este comando empaqueta tu proyecto en un archivo JAR, WAR o cualquier otro formato de archivo especificado en el archivo pom.xml. El comando mvn package compila el código fuente, ejecuta todas las pruebas unitarias y luego empaqueta el resultado en un archivo según la configuración especificada en el pom.xml. Este archivo empaquetado puede ser distribuido o utilizado en otros proyectos como una dependencia.

## **FINALIZAR EL EJERCICIO**
![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/bb1e5812-3a75-448e-8960-a29d82fee7bd)

## **EJERCICIO "DESCUENTO DE TARIFAS"**

![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/d03d4163-65e4-48ae-a8be-e9b6ae9fc9b6)

![image](https://github.com/Mauricio-A-Monroy/cvds-lab3--Monroy-Montes-/assets/111905757/bb1e5812-3a75-448e-8960-a29d82fee7bd)
