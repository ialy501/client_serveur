# client_serveur


## Principe du client serveur

Le client-serveur designe un mode de transaction(souvent a travers un reseau) entre plusieurs programmes ou processus:  l'un, qualifier client , envoie des requetes; l'autre, qualifie de serveur, attend le requete du client et y repond. Le serveur offre le service au client


## Protocole utilisee

### protocole tcp/ip

le protocole tcp/ip est un standard de communication entre deux processus. il garantie la fiabilite dans le transfert de donnees et capable de recuperre un nombre de message de grande taille

## Installer quelque  package 


### installer python3

```sh
sudo apt-get install python3
```
	sudo apt-get install python3



## Quelque details a suivre 


### git le projet 


```sh
git clone https://github.com/ialy501/client_serveur.git
```

### quelque precision 

### connection entre deux pc different 

```sh
	# Create a TCP/IP socket
	sock = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

	# Create a TCP/IP socket
	server_address = ('localhost', 12345)
	print ('starting up on %s port %s' % server_address )
	sock.bind(server_address)
	
```

if faut changer le ``` localhost ``` en ``` ip_serveur ``` ssur les deux code python
```
server_address = ('10.27.0.1', 12345)

```
puis executer les codes

```client
python3 clientSimple.py
```

```server
python3 serverSimple.py
```


### connection en local

-> ouvrir deux terminal different 

-> executer les deux  codes pythons

```client
python3 clientSimple.py
```

```server
python3 serverSimple.py
```


### instruction

-> mettre un fichier dans mla meme repetroire  ou se trouve le code python

-> le fichier doit  avoir un codtenue( image , texte)


creer un fichier text (ex: mess.txt)
```sh
touch mess.txt
```
ecrire le message dans le fichier text (mess.txt)


