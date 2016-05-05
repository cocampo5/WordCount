# WordCount
Programa WordCount en Python con mrjob y en Java con las librerias de hadoop
## Ejecución

Python: instalar mrjob mediante pip o easy_install y luego ejecutar
`$ python WordCount.py hdfs:///datos_in/*.txt --output-dir hdfs:///datos_out_python -r hadoop`

Java: Compilar el archivo .java con los respectivos .jar que se encuentran en las librerias de hadoop y luego ejecutar
`$ hadoop jar WordCount.jar WordCount /datos_in/*.txt /datos_out`
