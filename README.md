# SMA-Gama-
Fonctionnement du projet : C’est une plate forme technologique qui mettra
en relation passager et chauffeur. Pour ce faire, il est n ́ecessaire de mettre en place
une application destin ́ee `a deux groupes, le groupe des passagers et le groupe des
chauffeurs. L’application aura besoin d’ˆetre connect ́e en permanence `a la base de
donn ́ee pour effectuer la mise `a jour.

Dans ce syst`eme il y aura Trois principaux agents qui sont Agents client, agents
taxis et agent de liaison(DF).

2

Agent client : client (passager) envoi une demande de transport caract ́eris ́ee par
les coordonn ́ees point de d ́epart, point d’arriv ́ee et les fenˆetres de temps
associ ́es `a ces points. Ainsi que d’autres param`etres telles que le confort du
v ́ehicule et le nombre de places. Ces requˆetes seront soumises `a l’agent taxi
via l’agent de liaison
Agent de liaison(DF): Apr`es la r ́eception des exigences aupr`es de l’agent client,
il v ́erifie la disponibilit ́e, le nombre de place, le type et la distance a parcourir

puis envoie les r ́eponses a agent de taxi.A la r ́eception des informations (val-
idation par l’agent taxi) aupr`es de l’agent taxi, il assure la n ́egociation et la

planification. Il fera un retour `a l’agent client de l’offre avec les rubriques
selon les exigences du client.
Agent de taxi: Il re ̧coit les informations aupr`es de l’agent liaison. Il r ́eponds `a
chaque requˆete soit par un avis favorable `a l’agent de liaison (DF).
