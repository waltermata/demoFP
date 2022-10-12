# Presentación
## Problemas resueltos en clase con Diagramas de Flujos de Datos
### Ejercicio 1. Imprimir el nombre de una persona
#### 1.1 Análisis
Escribir  el análisis del problema
#### 1.2 Diagrama de Flujo de Datos
Poner la imagen del DFD
![image](https://user-images.githubusercontent.com/14845203/190483548-ab2f41db-b14b-498d-8e54-a19df62d4428.png)
#### 1.3 Prueba de Escritorio
#### 1.4 Entradas
Ninguna, o escribir las variables que se ingresan al DFD
#### 1.5 Salidas
escribir la salida del DFD

Ejemplo:

### Ejercicio 1. Se desea obtener como salida el mensaje de ‘Hola Mundo’ utilizando una variable para el almacenamiento del mensaje.
#### 1.1 Análisis
Se necesita utilizar el símbolo de proceso para realizar la asignación de la cadena del mensaje y posteriormente utilizar el símbolo de salida para imprimirlo.
#### 1.2 Diagrama de Flujo de Datos
![image](https://user-images.githubusercontent.com/14845203/190484202-9187d3ae-e467-4fa8-acf7-1fc29dd1b5e8.png)
#### 1.3 Prueba de Escritorio
| msg          | Salida | 
| -------------| ------ |
| "Hola Mundo" | Hola Mundo |

#### 1.4 Entradas
Ninguna, solo se asigna la cadena "hola mundo" a la variable mensaje
#### 1.5 Salidas
Hola Mundo


# Elixir

## Introducción a la Programación Funcional

## Introducción a Elixir

## Instalación en Windows

* Página principal del lenguaje: [https://elixir-lang.org/](https://elixir-lang.org/)
* Página de descarga: [https://elixir-lang.org/install.html](https://elixir-lang.org/install.html)
* Enlace directo de descarga: [Descargar](https://github.com/elixir-lang/elixir-windows-setup/releases/download/v2.2/elixir-websetup.exe)
* Instalación:
    * Descargar el instalador y ejecutar
    * Click en **Next**
    * Seleccionar la versión, de preferencia la más reciente (1.13.x), click en **Next**
    * Seleccionar la versión de Erlang que aparece por defecto,  click en **Next**
    * Click en **Install**
    * Click en **Next**, **Next**, **Install**, hasta terminar la instalación.
* Comprobación de la instalación:
    * Abrir una terminal
    * Escribir *elixir --version*
    
```bash
c:\>elixir --version
Erlang/OTP 24 [erts-12.1.5] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [jit]

Elixir 1.13.3 (compiled with Erlang/OTP 22)
c:\>
```
