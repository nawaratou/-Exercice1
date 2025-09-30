 Exercice 1 – Correction

 Commandes exécutées
mkdir cli_tmp
cd cli_tmp
touch je_suis_dans_tmp.txt
touch in_cli_tmp.txt
mkdir in_cli_tmp
rm -r je_suis_dans_tmp.txt
cd ~
rm -r cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir
mv bachir ../ami/
cd ~
mv ami parent/
cd parent/ami
pwd
cd ~ 

 Remarques personnelles
- J’ai eu un peu de mal avec la commande 'mv' pour déplacer le fichier dans un autre dossier.
- J’ai appris à créer plusieurs dossiers en une seule commande.

