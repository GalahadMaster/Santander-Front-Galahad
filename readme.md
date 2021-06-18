# Iniciar Proyecto de Git
git init 

# Preparar archivos que se convrtiran en commit  (El punto es para agregar todos los archivos)
git add .

# Crear commit con su mensaje 
git commit -m "Aqui va el mensaje"

# Agregar remoto solo la primera vez (Esto se hace cada que se crea un nuevo repositorio, que le da el origen)
git remote add origin https://github.com/Example

# Enviar commit al servidor de GitHub
git push -u origin master 

