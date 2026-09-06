# apuntes-sostenibilidad
Apuntes del módulo Sostenibilidad aplicada al sistema productivo

# instrucciones para subir versión nueva
git add .
git commit -m "Descripción del cambio"
git push origin master
python -m mkdocs gh-deploy --force

# Instalar dependencias.
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
