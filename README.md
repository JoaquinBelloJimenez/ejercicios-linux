#Linux Tema 3
#Joaquín Bello Jiménez

1.
ls *.jpg

2.
ls /isr/bin j*

3.
ls /usr/bin k?a*

4.
ls /bin *n

5.
ls -R /etc

6.
mkdir /home/joaquin/test
cp /bin/gzip /home/joaquin/test
cp /home/joaquin/test/gzip /home/joaquin/test/gzip2

7.
mv test test2 	(Cambiar nombre de test)
mkdir test3 	(Crear test3)
cp test2/* /test3 (Copiar todo en test3)
rm -R test2 	(borrar test2)

8.
Si puedes crearlo, es mala idea crear archivos con caracteres especiales.
Los nombres de los archivos deben ser de texto simple para no interferir con comandos.
Letras de A-Z(sin ñ ni tildes) y  en minúscula.

9.
cp -u -R multimedia/* multimedia_test

10.
rm -i -R multimedia/pictures/others

11.
mv multimedia/video/films.txt multimedia/my_films.txt
