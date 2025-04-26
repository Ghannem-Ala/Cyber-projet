# Cyber-projet
L'objectif principal de ce projet est de concevoir et mettre en place deux backbones réseau
distincts utilisant des routeurs Cisco, chacun avec des protocoles de routage et des technologies
spécifiques. Le premier backbone est basé sur le protocole OSPF (Open Shortest Path First)
avec MPLS (Multi Protocol Label Switching) pour le Forwarding, tandis que le second
backbone utilise le protocole IS-IS (Intermediate System to Intermediate System) avec
également MPLS pour le Forwarding. Chaque backbone comporte six routeurs, incluant des
routeurs PE (Provider Edge), P (Provider), et CE (Customer Edge), avec un routeur client
commun pour assurer l'interconnexion entre les deux backbones.
En plus de la configuration réseau, le projet intègre des mesures de sécurité robustes pour
protéger l'infrastructure contre les attaques potentielles. Deux pare-feu Fortinet (version
7.0.9) et deux WAF (Web Application Firewall) FortiWeb (version 7.2.4) ont été configurés
pour renforcer la sécurité périmétrique et protéger les applications web respectivement. La
sécurité a été testée à l'aide du site Burp suite pour simuler des attaques courantes.
Par ailleurs, la gestion des utilisateurs et des ressources réseau a été centralisée à l'aide de deux
annuaires Active Directory configurés sous Windows Server 2019. Des simulations d'attaques
ont été réalisées à l'aide de Kali Linux pour évaluer la résilience de l'infrastructure contre
divers vecteurs d'attaque.
