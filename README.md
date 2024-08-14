# NeuroGame

**NeuroGame** es un juego interactivo educativo diseñado para ayudar a personas con trastornos cognitivos como la demencia o en proceso de recuperación tras un accidente cerebrovascular. El juego integra ejercicios de memoria y resolución de problemas para crear una experiencia personalizada y adaptativa según las necesidades del usuario.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Características](#características)
3. [Tecnologías Utilizadas](#tecnologías-utilizadas)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Licencia](#licencia)

## Descripción del Proyecto

El objetivo de **NeuroGame** es combinar ejercicios terapéuticos con elementos de juego para hacer que el proceso de rehabilitación sea más atractivo y accesible. El juego está desarrollado en C++ y utiliza la biblioteca Qt para proporcionar una interfaz gráfica de usuario (GUI) intuitiva.

## Características

- **Interfaz gráfica intuitiva**: Diseñada con Qt para facilitar la interacción del usuario.
- **Retos cognitivos**: Incluye rompecabezas y juegos de memoria para estimular las funciones cognitivas.
- **Dificultad adaptativa**: El juego ajusta su dificultad en función del progreso del jugador.
- **Diseño modular**: Fácilmente extensible para agregar nuevos ejercicios o modos de juego.

## Tecnologías Utilizadas

- **C++**: Lenguaje principal del proyecto.
- **Qt**: Utilizado para desarrollar la interfaz gráfica de usuario.
- **Make**: Utilizado para automatizar el proceso de compilación mediante un `Makefile`.

## Instalación

### Prerrequisitos

- **Compilador de C++**: Asegúrate de tener instalado un compilador de C++ (por ejemplo, GCC, Clang, MSVC).
- **Qt**: Instala el framework Qt desde [el sitio oficial de Qt](https://www.qt.io/download).
- **Make**: Asegúrate de tener `make` instalado. Puedes instalarlo en tu sistema de la siguiente manera:

    - **En Linux**: `make` suele estar preinstalado, pero si no lo está, puedes instalarlo con tu gestor de paquetes:
    
      ```bash
      sudo apt-get install build-essential
      ```

    - **En macOS**: Instala Xcode Command Line Tools, que incluye `make`:

      ```bash
      xcode-select --install
      ```

    - **En Windows**: Puedes instalar `make` utilizando MinGW o Cygwin.

### Pasos

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu-usuario/NeuroGame.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd NeuroGame
    ```

3. Compila el proyecto:

    ```bash
    make
    ```

4. Ejecuta la aplicación:

    ```bash
    ./main/bin/neuro_game
    ```

## Uso

Después de iniciar el juego, el usuario se encontrará con varios desafíos cognitivos diseñados para mejorar la memoria y las habilidades de resolución de problemas. El juego se adapta en tiempo real según el rendimiento del usuario, lo que lo hace adecuado para diferentes niveles de capacidad cognitiva.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

