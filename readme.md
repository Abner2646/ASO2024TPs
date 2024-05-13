# TP3
## 1A
Se puede notar del tiempo de ejecución que es menor cuando se usan hilos porque con hilos se ejecutan procesos en paralelo.
En promedio el tiempo de ejecución con hilos es de 4.01460 segundos mientras que sin hilos es de 5.13283.

## 1B
Comparando con mi compañero, el tuvo en la ejecución con hilos 4.05920 y sin hilos tuvo 5.23259.


## 1C
Después de hacer eso, noté que el programa tardaba más en completarse. Porque cuando descomente, agregué dos bucles extra que no hacían nada útil, solo esperaban un poco.

Estos bucles estaban dentro de las partes de sumar y restar, y cada uno se ejecutaba mil veces. Aunque no hacían nada importante, aumentaban el tiempo total que el programa tardaba en ejecutarse.

## 2A
<a href="./con_race_condition2.0.c">puzzle corregido</a>