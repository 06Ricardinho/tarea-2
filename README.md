# tarea-2

mkdir tarea-2
cd tarea-2


git init


git branch -M main


echo 'def saludo():' > script.py
echo '    print("Hola, GitHub")' >> script.py
echo '' >> script.py
echo 'saludo()' >> script.py

git add script.py


git commit -m "Subiendo el archivo inicial"

git remote add origin https://github.com/tu-usuario/tarea-2.git


git push -u origin main
