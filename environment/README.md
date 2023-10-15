GreenGrass: 
- Es un gateway o un concentrado IoT
- es un edge location para IoT
- Puede agrupar informacion de micro controladores
- Es una aplicacion Java se comunica de manera constante/automatica a AWS

Prerequisitos:
   - aws cli
   - Linux 
   - Python 3.5 or later
   - JDK 11  

Componente Greengrass:
    Recipe: Un archivo JSON o YAML que describe el módulo de software mediante la definición de los detalles, la configuración y los parámetros de los componentes.

    Artefacto: El código fuente, los archivos binarios o las secuencias de comandos que definen el software que se ejecutará en el dispositivo. Puedes crear artefactos desde cero o puedes crear un componente con una función de Lambda, un contenedor de Docker o un tiempo de ejecución personalizado.

    Dependencia: La relación entre los componentes que permite aplicar actualizaciones o reinicios automáticos de los componentes dependientes. Por ejemplo, puede tener un componente de procesamiento de mensajes seguro que dependa de un componente de cifrado. Esto garantiza que cualquier actualización del componente de cifrado actualice y reinicie automáticamente el componente de procesamiento de mensajes.

Deployment: 
    El proceso para enviar componentes y aplicar la configuración de componentes deseada a un dispositivo de destino de destino, que puede ser un solo dispositivo principal de Greengrass o un grupo de dispositivos principales de Greengrass

AWS IoT GreengrassSoftware de Core:
    Núcleo: Este componente necesario proporciona la funcionalidad mínima delAWS IoT GreengrassSoftware Core. El núcleo gestiona las implementaciones, la organización y la gestión del ciclo de vida de otros componentes. También facilita la comunicación entreAWS IoT Greengrasscomponentes localmente en un dispositivo individual. Para obtener más información, consulte Núcleo de Greengrass.

    Componentes opcionales: Estos componentes configurables son proporcionados porAWS IoT Greengrassy habilite funciones adicionales en sus dispositivos perimetrales. Según sus requisitos, puede elegir los componentes opcionales que desea implementar en su dispositivo, como la transmisión de datos, la inferencia de aprendizaje automático local o una interfaz de línea de comandos local. Para obtener más información, consulte

Link: https://docs.aws.amazon.com/es_es/greengrass/v2/developerguide/how-it-works.html

instalacion en host linux:
    https://docs.aws.amazon.com/greengrass/v2/developerguide/getting-started.html
