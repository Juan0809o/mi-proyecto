# mi-proyecto
git config --global user.name "Juan Cano Gonzalez"
git config --global user.email "jcg0083@alu.medac.es"
mkdir mi_proyecto
cd mi_proyecto
git init
git add .
git status   # Muestra los archivos añadidos
git commit -m "Primer commit con archivos del proyecto"
git add .
git status   # Aqui mostramos nuestros archivos.
git commit -m "Primer commit con archivos del proyecto"
git remote add origin https://github.com/Juan0809o/2-proyecto.git
git branch -M main
git push -u origin main
git checkout -b version-2.0
git push -u origin version-2.0

