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
![image](https://github.com/andreec2/cvds-lab3--Monroy-Montes-/assets/111905757/f00feeef-6bdb-4e74-a904-24caf635114a)

## **COMPILAR Y EJECUTAR**
