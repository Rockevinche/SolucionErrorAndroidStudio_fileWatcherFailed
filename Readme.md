## Referencias del error

1) https://youtrack.jetbrains.com/issue/IDEA-145762

2) https://github.com/JetBrains/intellij-community

## Solución del error "External file changes sync may be slow: File watcher failed to start" al Arrancar Android Studio en Linux

### Pasos para solucionar el problema:

1) Ir a la carpeta donde está instalado Android Studio ".../android-studio/bin/" y buscar el archivo ejecutable "fsnotifier" para luego borrarlo

2) Ejecutar el archivo "make.sh" en consola con el comando $ ./make.sh (Debes tener instalado "Clang" para poder compilar los archivos para crear el fsnotifier). Esto compilará nuestro nuevo archivo ejecutable "fsnotifier"

3) Copiar el nuevo archivo "fsnotifier" en la carpeta de instalación de Android Studio ".../android-studio/bin/"

Listo, ya estaría solucionado el problema :D
