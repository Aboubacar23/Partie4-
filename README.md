# Partie4-
Partie 4 du tp automatisation
#Partie4 : Automatisation . 

#creation automatique d'apache,php et mysql en même temps

sudo apt install apache2 mysql-server php php-mysql libapache2-mod-php php-cli

#echo "Creation des utilisareurs et de la base de données"
sudo mysql 
create user 'Aboubcar23' identified by 'Aboubacar23';
grant all privileges on . To Aboubacar23;

create database grh; use grh;

CREATE TABLE personne ( id Int NOT NULL AUTO_INCREMENT, nom VARCHAR(255), prenom VARCHAR(255), age Int(11), adresse VARCHAR(255), PRIMARY KEY (id) );
