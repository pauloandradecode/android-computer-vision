Android NDK (Native Development Kit)
===

La página oficial refiere que Android NDK es un conjunto de herramientas que permite implementar partes de nuestra app usando lenguajes de código nativo como C y C++. Para ciertos tipos de apps, esto puede ayudarle a volver a usar las bibliotecas de códigos escritas en esos lenguajes.

Permite a los desarrolladores reutilizar código escrito en C/C++ introduciéndolo en las aplicaciones a través de JNI (Java Native Interface). El NDK hace que la ejecución de la aplicación sea en cierto modo más rápida, ya que pasará a ejecutarse directamente en el procesador y no es interpretado por una máquina virtual.

Las aplicaciones que suelen utilizar el NDK son aquellas que harán un uso intensivo de la CPU, como por ejemplo motores de videojuegos o procesado de señal. En general, se trata de optimizar al máximo costosas operaciones matemáticas.

## Instalación

Ingresamos a la web oficial de [Android NDK](https://developer.android.com/ndk/downloads/index.html?hl=es-419) y descargamos el zip con la versión que corresponda al sistema operativo que utilizamos.-

![versiones de SDK](https://raw.githubusercontent.com/pauloandradecode/android-computer-vision/master/images/ndk-version.png)

Terminada la descarga, descomprimimos el Android NDK en el directorio donde tengamos nuestro Android SDK (de esta forma tenemos más organización).-

![versiones de SDK](https://raw.githubusercontent.com/pauloandradecode/android-computer-vision/master/images/directorio-sdk.png)

## Fe de erratas

Si encuentras algún error en el código o la forma de optimizarlo puedes informarme en el siguiente enlace para realizar las correcciones correspondientes.-

[https://github.com/pauloandradecode/android-computer-vision/issues](https://github.com/pauloandradecode/android-computer-vision/issues)

## Referencias bibliográficas

Pérez, Esteso, M. (Sin fecha). Que es el Android NDK - Parte 1. Recuperado de: [https://geekytheory.com/que-es-el-android-ndk-parte-1](https://geekytheory.com/que-es-el-android-ndk-parte-1)