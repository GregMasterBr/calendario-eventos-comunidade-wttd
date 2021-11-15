Passo a passo para publicar uma página estática no Heroku 
-> criar uma pasta, 
-> criar um arquivo que não seja o nome index.html
-> criar a index.php e realizar o include do arquivo .html

https://medium.com/@agavitalis/how-to-deploy-a-simple-static-html-website-on-heroku-492697238e48

heroku apps:create calendario-comunidade-wttd

git add .
git commit -m “A message describing the changes made”
git push heroku master

https://calendario-comunidade-wttd.herokuapp.com/
