> Written with [StackEdit](https://stackedit.io/).
**

> Written with [StackEdit](https://stackedit.io/).
**
# Ejercicio de Práctica-PD
#  Lista de Alumnos.

## Instrucciones:

Considera la siguiente Estructura de Datos **Alumno** que contiene los datos:
```c++
     - Nombre Completo (cadena),  
     - Créditos Aprobados( int),
     - Semestre equivalente (int).
 ```
![EstructurDiagrama de Alumno](assets/Alumno.drawio.png)
 
Se creará una lista (simplemente enlazada) para mantener la información de los alumnos.  Cada nodo de la lista ***contiene*** en el dato una estructura Alumno y un apuntador al siguiente nodo.

La lista simplemente enlazada y la estructura Alumno se deben crear en memoria dinámica. 

![Estructura de la lista de Alumnos](assets/ListaAlumnos.drawio.png)

La funcionalidad que se implementará para la lista es la siguiente:

```c++
    *Alumno crearAlumno(*char, int, int)
    void imprimirAlumno()

    
    *Nodo crearNodo(*Alumno)
    int insertarNodoOrdenadoCréditos(*nodo)
    void imprimirLista()
```
El programa puede implementarse en C o C++. Puede utilizar estructuras y funciones por separado o definidas dentro de la estructura.

Se debe incluir una sección main que incluya los llamados correspondientes a funciones para realizar las siguientes acciones:

```c++
    int main(){
    //Crear 5 instancias de estructuras Alumno

    
    //crear la lista con las 5 instancias de Alumno
    //insertar de forma ordenada de acuerdo al número de créditos (ascendente)
    //imprimir la lista
}
```

No se espera que la funcionalidad este completa durante la sesión pero es requisito realizar un commit/push al repo de la tarea ANTES del final de la sesión. Puedes completar la funcionalidad hasta antes del deadline indicado en el assignment.

**IMPORTANTE:** Incluir en el repo evidencia (imagen, video) de la ejecución en la terminal que muestre el correcto funcionamiento de la implementación. La evidencia se incluye como un  ejemplo y la ejecución se espera lo más similar posible.

![Evidencia](assets/EvidenciaTerminal.png)