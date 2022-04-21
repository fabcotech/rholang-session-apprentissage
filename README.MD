### RChain / rholang sessions  d'apprentissage

Le setup avec l'installation de rnode directement au niveau OS
```
https://rchain.coop/developer.html
```

Le setup avec npm et docker-compose
voir -> https://github.com/fabcotech/dappy-node
```
npm i -g @fabcotech/dappy-node
mkdir test
cd test
easyrnode init
eadyrnode run
easyrnode deploy helloworld.rho
```

#### April 21 2022

Contract qui stocke une string, et la rend accessible en lecture à d'autres executions

**A reproduire :**
```
easyrnode deploy getset.rho
# changer le resigtry URI dans get.rho
easyrnode deploy get.rho
```

**Challenge :** coder le set :)
