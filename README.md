# Router-on-a-stick

Tarefas:

Configure o roteador em um stick da seguinte maneira:
1) VLAN 1 = 10.1.1.0/24, VLAN 10 = 10.1.10.0/24, VLAN 20 = 10.1.20.0/24
2) Roteador = último endereço IP na sub-rede
3) Interruptor = 10.1.1.253/24 apenas
Configurar VLANs no switch (PC1 na VLAN 10 e PC2 na VLAN 20)
4) Configure o link entre o switch e o roteador
5) Certifique-se de que o PC1 pode executar ping no PC2 (PC1 = 10.1.10.1) PC2 = 10.1.20.2)

<img src="https://raw.githubusercontent.com/MattheusMartins/Router-on-a-stick/main/1.PNG">
