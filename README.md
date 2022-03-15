# devops

Après avoir déployer les VM avec terraform :  
changer les parametres reseau en réseaux nat dans VBox  
Editer /etc/ssh/sshd_config - changer **PasswordAuthentication** et **ChallengeResponseAuthentication** à *yes*  
sudo service sshd restart  
