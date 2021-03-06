# Cours
## Supports & TPs

* Supports de cours : 
  * [Cours 1 : Remise dans le bain (IP, MAC, ports, création + install de VM)](./1.md)
  * [Cours 2 : Transport de données (TCP/UDP), adressage IP (WAN/LAN), NAT](./2.md)
  * [Cours 3 : OSPF, VLAN](./3.md)

* [Lexique](./lexique.md)

* Procédures
  * [CentOS7](./procedures.md)  
  * [Cisco](./procedures-cisco.md)

* [TPs](../tp)

## Objectif du cours réseau B2
* appréhender les termes et protocoles de bases
  * *[IP](./lexique.md#ip--internet-protocol), [MAC](./lexique.md#mac--media-access-control), [routage](./lexique.md#routage-ou-routing),client/serveur, [DHCP](./lexique.md#dhcp--dynamic-host-configuration-protocol), [DNS](./lexique.md#dns--domain-name-system), [HTTP](./lexique.md#http--hypertext-transfer-protocol), etc.*

* maîtriser la [stack réseau](./lexique.md#stack-réseau-ou-stack-tcpip-ou-pile-réseau) de son propre poste (Windows, Linux ou Mac)
  * gestion de [cartes réseau](./lexique.md#carte-réseau-ou-interface-réseau)
  * gestion [IP](./lexique.md#ip--internet-protocol) ([DHCP](./lexique.md#dhcp--dynamic-host-configuration-protocol)/statique, [gateway](./lexique.md#passerelle-ou-gateway), [binaire](./lexique.md#binaire), [masque de sous-réseau](./lexique.md#masque-de-sous-réseau), etc.)
  * [firewall](./lexique.md#pare-feu-ou-firewall)
  * exploration des [ports](./lexique.md#ports) utilisés
  * [ligne de commande](./lexique.md#commandes)
  
* comprendre le rôle d'une Box internet et ses principales fonctionnalités : 
  * routeur WAN/LAN
  * AP WiFi
  * [DNS](./lexique.md#dns--domain-name-system)
  * [DHCP](./lexique.md#dhcp--dynamic-host-configuration-protocol)
  * NAT
  * [firewall](./lexique.md#pare-feu-ou-firewall)

* savoir gérer le réseau d'une distrib Linux orienté serveur
  * [CentOS 7](https://www.centos.org/)
  * gestion de [stack réseau](./lexique.md#stack-réseau-ou-stack-tcpip-ou-pile-réseau)
  * administration distante ([SSH](./lexique.md#ssh--secure-shell), [firewall](./lexique.md#pare-feu-ou-firewall))
  * [routage](./lexique.md#routage-ou-routing) statique
  
* travailler avec des outils du monde Cisco
  * [routage](./lexique.md#routage-ou-routing) statique et dynamique
    * OSPF, EIGRP
    * NAT
    * LACP
    * ACL
  * switching
    * VLAN
  * sécurité
  * appréhension de la première certification ([CCNA](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna-routing-switching.html))

* utilisation de OpenVSwitch
  * alternative libre/opensource aux constructeurs comme Cisco, Juniper, HP, etc.
  * gestion L2 (switching) et L3 (routing)
  * intégration native à beaucoup d'autres outils ouverts et standards
    * Kubernetes
    * Métrologie/Monitoring
    * Backup
    * etc.
  * sécurité

* approfondissement accès WAN
  * NAT or not NAT ? 
  * front firewall
  * backbone

* connaissances techniques en réseau
  * modèle OSI et principaux protocoles
  * Internet
  * design réseau
    * adressage IP
  * sécurité
  * fonctionnement du routage/encapsulation
  
