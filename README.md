
CLONACION DEL REPOSITORIO <br>
git clone https://github.com/alahkdmovak/my_web_page2.git

CREACION DE LA RAMA new_features <br>
git init <br>
git checkout -b new_features <br>

AGREGACION Y COMMIT DE LOS ARCHIVOS MENCIONADOS EN LA PRACTICA <br>
git add aboutme.html <br>
git commit -m "Aboutme_primer_html" <br>
git add styles <br>
git commit -m "aqui se agregaran los estilos para la pagina web, archivos CSS" <br>
git add aboutme.html <br>
git commit -m "Modificacion al archivo con informacion acerca de mi" <br>
git add index.html <br>
git commit -m "Archivo index de la pagina web" <br>
git add aboutme.html <br>
git commit -m "Modificacion a la linea 7 y despues de la linea 35 se agregaron 5 lineas de codigo" <br>

ELIMINACION DEL COMMIT REALIZADO CON EL ARCHIVO INDEX <br>
git log #para mirar el sha del commit y asi poder eliminarlo <br>
git revert 4026de4d00981b959aa9d457b9b1dbc3e68af60f <br>

MERGE Y PUSH DEL REPOSITORIO LOCAL HACIA EL REPOSITORIO REMOTO <br>
git checkout main <br>
git merge new_features <br>
git push <br>
