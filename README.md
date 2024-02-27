
#CLONACION DEL REPOSITORIO
git clone https://alahkdmovak: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@github.com/alahkdmovak/my_web_page.git

#CREACION DE LA RAMA new_features
git init 
git checkout -b new_features

#AGREGACION Y COMMIT DE LOS ARCHIVOS MENCIONADOS EN LA PRACTICA
git add aboutme.html
git commit -m "Aboutme_primer_html"
git add styles
git commit -m "aqui se agregaran los estilos para la pagina web, archivos CSS"
git add aboutme.html
git commit -m "Modificacion al archivo con informacion acerca de mi"
git add index.html
git commit -m "Archivo index de la pagina web"
git add aboutme.html
git commit -m "Modificacion a la linea 7 y despues de la linea 35 se agregaron 5 lineas de codigo"

#ELIMINACION DEL COMMIT REALIZADO CON EL ARCHIVO INDEX
git log #para mirar el sha del commit y asi poder eliminarlo
git revert 4026de4d00981b959aa9d457b9b1dbc3e68af60f

#MERGE Y PUSH DEL REPOSITORIO LOCAL HACIA EL REPOSITORIO REMOTO
git checkout main
git merge new_features
git push
