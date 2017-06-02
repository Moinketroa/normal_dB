# normal_dB

normal_dB est un projet personnel dont le but sera de normaliser le niveau audio d'un fichier sonore par rapport à un Décibel donné.

Prenons par exemple, un fichier audio en entrée. Il comporte une conversation chuchotée, une conversation normale et une explosion bruyante avec des différences de niveaux entre ces 3 scènes. Avec un volume adapté à l'explosion, un utilisateur va lire le fichier audio sans pouvoir comprendre un mot de la conversation chuchotée. Et avec un volume adapté à la conversation chuchotée, un utilisateur va lire le fichier audio, mais lors de l'explosion, le niveau audio sera bien trop élevé.

Le but de ce projet permettra de récupérer en sortie, le fichier audio contenant ces 3 scènes avec un niveau audio normalisé sur toute la longueur du fichier. En lisant ce fichier récupéré en sortie avec un volume adapté à l'explosion, l'utilisateur va pouvoir comprendre la conversation chuchotée.
