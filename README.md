firewall.cpl ==>On peut acceder au firewall avec la recherche firewall.cpl. Par la suite on doit cliquer
sur parametre avance ou on pourrait trouver les regles qui interdisent ou pas qu une
connexion reseau se fasse.

netsh interface show interface = on peut voir le nom et le statut de notre
interface réseau

netsh interface ip add address= pour modifier l’adresse IP.

apt-get update = mettre à jour les paquets

ipconfig /renew = demande une nouvelle adresse IP au serveur DHCP

ipconfig /release = libère l’adresse ip actuelle

netsh interface ip set dns «Ethernet» dhcp = cette commande permet de configurer en mode DHCP l’adresse IPv4 d’un serveur DNS.<br>
netsh interface ip delete address "Ethernet" «IPV4» = cette commande permet de supprimer une IPV4 sur la carte Ethernet

ipconfig /flushdns = Efface le cache DNS local
netstat =Affiche les connexions réseau actives, les ports ouverts et d'autres informations réseau
tracert = Affiche le chemin pris par les paquets pour atteindre une destination spécifiée.
ping = Envoie un paquet de test à une adresse IP spécifiée pour vérifier la connectivité réseau.
