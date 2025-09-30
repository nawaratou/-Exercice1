# Exercice 6 – Dossier personnel

 Commandes utilisées
mkdir ~/dossier_perso
cd ~/dossier_perso
touch banque.txt sante.txt .mdp
echo "Relevé bancaire janvier" > banque.txt
echo "Vaccination complète" > sante.txt
ls -a
mv sante.txt medical.txt
mkdir documents
mv banque.txt medical.txt documents/
rm .mdp

 Résultat
ls -a
ls -R documents

 Capture d’écran
[Exercice 6](exercice6_capture.png)

