

# Arquitectura

1. Carpetas
   1. **In:** carpeta data, archivos de entrada, exceles, documentos de texto, csv, etc...
   2. **Out:** Resultado de la exportación de los modelos, graficas generadas, archivos generados
   3. **models:** Guardamos los modelos que nos han dado buenos resultados. 
2. **Main.py:** contiene el flujo de trabajo del archivo y es el código a correr
   1. Cada archivo se encarga de una tarea individual
3. **load.py:** se encarga solo de leer los archivos.
4. **Utils.py:** métodos que se reutilizarán (como el escalamiento).
5. **models.py:** allí va la parte de ML como tal.

