# pureWit

Desarrollo de plataforma virtual para el lanzamiento de mensajes SMS y llamadas desde la web.

## Getting Started

(Lo mismo del readme actual)

### Prerequisites

Visual Studio 2015 - 2017

* Paso 1: Asegurarse de que el equipo está listo para Visual Studio

```
Antes de comenzar la instalación de Visual Studio:
Compruebe los requisitos del sistema. Estos requisitos le permiten saber si el equipo es compatible con Visual Studio 2017.
Aplique las actualizaciones de Windows más recientes. Estas actualizaciones garantizan que el equipo tiene las actualizaciones de seguridad más recientes y los componentes del sistema necesarios para Visual Studio.
Reinicie el equipo. El reinicio garantiza que cualquier actualización o instalación pendiente no dificultará la instalación de Visual Studio.
Libere espacio. Quite los archivos y aplicaciones innecesarios de %SystemDrive% ejecutando, por ejemplo, la aplicación Liberar espacio.
```

* Paso 2: Descargar Visual Studio

```
A continuación, descargue el archivo de programa previo de Visual Studio. Para ello, haga clic en el botón siguiente, seleccione la edición de Visual Studio 2017 que desee instalar, haga clic en Guardar y, a continuación, haga clic en Abrir carpeta.
Enlace: https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=button+cta&utm_content=download+vs2017
```

* Paso 3: Ejecución de Instalador de Visual Studio

```
1. Desde la carpeta Descargas, haga doble clic en el archivo de programa previo que coincida o sea similar a uno de los siguientes archivos:
vs_enterprise.exe para Visual Studio Enterprise
vs_professional.exe para Visual Studio Professional
vs_community.exe para Visual Studio Community 

Si recibe un aviso de Control de cuentas de usuario, haga clic en Sí.

2. Le pediremos que acepte los Términos de licencia de Microsoft y la Declaración de privacidad de Microsoft. Haga clic en Continuar.
```
<div align="center">
  <img src="https://docs.microsoft.com/es-es/visualstudio/install/media/vs2017-privacy-and-license-terms.png"><br><br>
</div>

* Paso 4: Seleccionar cargas de trabajo
```
Una vez instalado el Instalador, puede usarlo para personalizar la instalación mediante la selección de los conjuntos de características, o cargas de trabajo, que desee. Esta es la manera de hacerlo.

1. Busque la carga de trabajo que quiera en la pantalla Instalando Visual Studio.
```
<div align="center">
  <img src="https://docs.microsoft.com/es-es/visualstudio/install/media/install-visual-studio-community.png"><br><br>
</div>

```

Por ejemplo, elija la carga de trabajo "Desarrollo de escritorio de .NET". Incluye el editor principal predeterminado, que contiene compatibilidad de edición de código básica para más de 20 lenguajes, la capacidad de abrir y editar código desde cualquier carpeta sin necesitar un proyecto y control de código fuente integrado.

2. Después de que seleccione las cargas de trabajo que quiera, haga clic en Instalar.

Después, aparecerán las pantallas de estado que muestran el progreso de su instalación de Visual Studio.

3. Después de que se instalen los nuevos componentes y cargas de trabajo, haga clic en Iniciar.

```
* Paso 5: Seleccionar componentes individuales(opcional)
```
Si no desea usar la característica Cargas de trabajo para personalizar la instalación de Visual Studio, puede hacerlo mediante la instalación de componentes individuales. Para seleccionar componentes individuales, haga clic en la opción Componentes individuales del Instalador de Visual Studio, seleccione lo que quiera y siga las indicaciones.
```
<div align="center">
  <img src="https://docs.microsoft.com/es-es/visualstudio/install/media/vs2017-components.png"><br><br>
</div>

* Paso 6 - Instalar paquetes de idioma (opcional)
```
De manera predeterminada, el programa instalador intenta hacer coincidir el idioma del sistema operativo cuando se ejecuta por primera vez. Para instalar Visual Studio 2017 en un idioma de su elección, haga clic en la opción Paquetes de idioma del instalador de Visual Studio y siga las indicaciones.
```
<div align="center">
  <img src="https://docs.microsoft.com/es-es/visualstudio/install/media/vs2017-languages.png"><br><br>
</div>
```
Cambio del idioma del instalador en la línea de comandos
Otra manera de cambiar el idioma predeterminado es mediante la ejecución del instalador desde la línea de comandos. Por ejemplo, puede forzar al instalador a utilizar el inglés utilizando el comando siguiente: vs_installer.exe --locale en-US. El instalador recordará esta configuración cuando se ejecute la próxima vez. El instalador admite los siguientes tokens de idioma: zh-cn, zh-tw, cs-cz, en-us, es-es, fr-fr, de-de, it-it, ja-jp, ko-kr, pl-pl, pt-br, ru-ru y tr-tr.
```
* Paso 7: Empezar a desarrollar
```
1. Una vez completada la instalación de Visual Studio, haga clic en el botón Iniciar para empezar a desarrollar con Visual Studio.

2. Haga clic en Archivo y después en Abrir proyecto.

3. Seleccione un el proyecto pureWit. 

```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
