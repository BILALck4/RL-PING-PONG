
# Pong Q-Learning

Le but de ce projet est d'expérimenter l'utilisation de l'algorithme Q-learning pour battre un programme de jeu Pong. Cela inclura la programmation du Q-learner, le choix des hyperparamètres et la quantification de l'état. L'atelier comprendra la rédaction d'une simulation basée sur Python, puis un rapport qui analyse et explique les résultats.

## Outils

- Python
- Pygame
- Qlearning
- Numpy
- Matplotlib

## Exécution du code

Avant d'exécuter les programmes, vous devez d'abord créer un environnement conda, le charger et installer les dépendances comme suit:

```bash
$ conda create -n q_learning_pong python=3.8
$ conda activate q_learning_pong
$ pip install -r requirements.txt
```

Pour entraîner l'agent, vous pouvez appeler Q_Learning.py directement:

```bash
$ python Q_Learning.py grid_dem alpha epsilon num_episodes check_freq file_name [agent_type]
```

Pour tester l'agent, vous pouvez appeler runEpisode.py directement:

```bash
$ python runEpisode.py grid_dem file_name
```

![image](https://github.com/BILALck4/RL-PING-PONG/assets/115404316/058d839b-7376-4970-baac-388a2152e717)

![image](https://github.com/BILALck4/RL-PING-PONG/assets/115404316/0a9bb706-a2d0-4d87-b86a-189e2b8004fa)
![image](https://github.com/BILALck4/RL-PING-PONG/assets/115404316/f8456324-720b-4910-abe1-15a9ca3c1a91)
![image](https://github.com/BILALck4/RL-PING-PONG/assets/115404316/0846c8f6-1615-4d59-b708-2fb8bb0c5b86)

