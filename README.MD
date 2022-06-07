### RChain / rholang sessions  d'apprentissage

RChain est une plateforme blockchain ultra-scalable qui permet la production concurrente de blocs et le scaling horizontal (proportionnel au hardware disponible).

A la suite d'une conférence donnée à l'ecole 42 on a créé des sessions dev/apprentissage pour apprendre à coder en rholang, le langage des smart contracts pour RChain. Pour participer au session joindre Raphaël -> contact[ at]fabco.tech .

[rchain.coop](https://rchain.coop)
[Rholang cheat sheet](https://fabcotech.github.io/rholangcheatsheet/)

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
easyrnode run
easyrnode deploy helloworld.rho
```

#### April 21 2022

[vidéo associée](https://youtu.be/QfjXcsQ_k24)

Smart contract qui stocke une string, et la rend accessible en lecture à d'autres executions

**A reproduire :**
```
easyrnode deploy getset.rho
# changer le resigtry URI dans get.rho
easyrnode deploy get.rho
```

**Challenge :** coder le set :)
