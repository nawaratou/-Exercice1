# Créer arborescence
mkdir -p ~/conteneur/voitures ~/conteneur/ustensiles ~/conteneur/electronique

# Ajouter contenu aux fichiers
echo "benz" >> ~/conteneur/voitures/mes_voitures.txt
echo "toyota" >> ~/conteneur/voitures/mes_voitures.txt
echo "honda" >> ~/conteneur/voitures/mes_voitures.txt

echo -e "cuillere\nmarmite\ncouteau" > ~/conteneur/ustensiles/cuisine.txt

# Vérifier le contenu de cuisine.txt
cat ~/conteneur/ustensiles/cuisine.txt

# Lister le contenu du dossier conteneur
ls ~/conteneur
# Remarques
# - -e dans echo interprète \n comme retour à la ligne
