# Documentación de configuración del proyecto
## Creación de estructura de directorios
Crear carpetas para los archivos CSS del proyecto y el readme.md
```bash
mkdir -p assets/css
mv style.css assets/css/
touch README.md
```
##  Inicie un repositorio dentro de la carpeta del proyecto que será la rama “main”
```bash
git init
git branch -m main
```
### Agregue los archivos al “stage”
```bash
git add .
```
## Primer commit
```bash
git commit -m "Primer commit"
```
##  Cree una nueva rama “development” y sitúese en ella.
```bash
git checkout -b development
```
##  Agregue los cambios al “stage"
```bash
git add .
git commit -m "Errores corregidos"
```

##  Conecte el repositorio local al remoto y  pushee  las dos ramas ”main” y “development”
```bash
git remote add origin https://github.com/RerreRojas/Renachalenge.git
git checkout main
git push -u origin main
git checkout development
git push -u origin development



