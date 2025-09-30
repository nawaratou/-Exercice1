# Exercice 5 – Projet scolaire

 Commandes utilisées
mkdir -p ~/projet_scolaire/maths ~/projet_scolaire/sciences
echo "x^2 + y^2 = z^2" > ~/projet_scolaire/maths/equations.txt
echo "eau + huile = séparation" > ~/projet_scolaire/sciences/experiences.txt
mv ~/projet_scolaire/maths/equations.txt ~/projet_scolaire/maths/geometrie.txt
mv ~/projet_scolaire/sciences/experiences.txt ~/projet_scolaire/maths/
rmdir ~/projet_scolaire/sciences

 Résultat
ls -R ~/projet_scolaire

 Capture d’écran
[Exercice 5](exercice5_capture.png)

