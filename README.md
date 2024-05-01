<h1 align="center"> Laboratório de Hub e Spoke no Azure </h1>

Neste laboratório vou criar um cenario simples de uma rede Hub e Spoke.

<p align="center"><img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/></p>

![2024-04-28](https://github.com/FelipeFerreira17/labAzureHubSpoke/assets/142698934/c50569ad-14eb-4649-acd5-15af92aa72a9)

Redes Virtuais não se comunicam entre si. Então numa topologia Hub e SPOKE, Temos uma rede de Hub, onde deixamos os serviços que todos vão usar.
E temos as Redes Spoke, que podem ser redes de produção, desenvolvimento, logística e outras. Essas redes não terão acesso uma as outras.
Todas as redes Spokes, serão ligadas a rede de Hub através de um serviço chamado Peering.

Vamos aos passos para criar esse laboratório.

```Markdown
*Crie um Grupo de Recursos
*Crie 3 Redes Virtuais, cada uma com uma Subnet
*Crie 3 Grupos de Segurança de Rede, um para cada Rede Virtual.
*Associe as Subnets aos NSGs
*Crie 3 Máquinas Virtuais. Uma em cada Rede Virtual.

```
<br>
Eu criei duas VMs Windows Server e uma VM linux.
Nos NSGs, crie regras para acesso as portas RDP e SSH para podemos acessar as VMS.

<br>
Criadas as 3 VMs, você irá acessar cada uma delas.
<br>

![HubPart1](https://github.com/FelipeFerreira17/labAzureHubSpoke/assets/142698934/16ada9c3-116b-42eb-98e6-ce25ff141f85)
<br>

![HubPart2](https://github.com/FelipeFerreira17/labAzureHubSpoke/assets/142698934/37dae2ac-a93d-413a-998e-7a4c5171c910)
