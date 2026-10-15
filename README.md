# HOLAMUNDO

Primer programa de consola en C++, creado para configurar y verificar el entorno de desarrollo (IDE) de la materia Laboratorio de Programación.

## Descripción

El proyecto documenta la configuración de **Visual Studio Code** para programar en C/C++, junto con el compilador **MinGW (GCC)** instalado mediante **MSYS2**. Para comprobar que todo funciona, se compila y ejecuta un programa "Hola Mundo" que muestra por consola un mensaje de bienvenida con el nombre del estudiante.

## Entorno configurado

- **Editor:** Visual Studio Code
- **Extensiones:** C/C++ (Microsoft), C/C++ Extension Pack y Code Runner
- **Compilador:** g++ (MinGW / GCC vía MSYS2), agregado al Path del sistema
- **Terminal:** PowerShell integrada en VS Code

## Conceptos aplicados

- Código fuente, compilador, depurador e IDE
- Terminal / consola y variable de entorno Path
- Estructura básica de un programa en C++ (`#include`, `main`, `cout`, `return 0`)
- Organización de un proyecto y control de versiones con Git

## Estructura del proyecto

```
holamundo/
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   └── InformeProyectoholamundo.pdf
├── src/
│   └── main.cpp
└── capturas/
    ├── gpp_version.png
    ├── extensiones_vscode.png
    └── ejecucion_hola_mundo.png
```

## Compilación y ejecución (PowerShell, Windows 10/11)

Desde la raíz del proyecto:

```
g++ src/main.cpp -o src/holamundo.exe
.\src\holamundo.exe
```

Para verificar que el compilador está instalado:

```
g++ --version
```

Si la PC no permite compilar, se puede usar OnlineGDB para ejecutar el código.

## Ejemplo de salida

```
=====================================================
 Hola Mundo! Bienvenido al Taller de LPR 2026.
 Estudiante: Marcelo Cantamessi
=====================================================
```

## Autor

Benjamin Hlynczuk
E.E.S.T. N.º 1 "Eduardo Ader", Vicente López
Laboratorio de Programación (LPR), 5.º año, 2026
