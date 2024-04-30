<h1 align="center"> Laboratório de Hub e Spoke no Azure </h1>

Neste laboratório vou criar um cenario simples de uma rede Hub e Spoke.

<p align="center"><img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/></p>

![2024-04-28](https://github.com/FelipeFerreira17/labAzureHubSpoke/assets/142698934/c50569ad-14eb-4649-acd5-15af92aa72a9)

Redes Virtuais não se comunicam entrw si. Então numa topologia Hub e SPOKE, Temos uma rede de Hub, onde deixamos os serviços que todos vão usar.
E temps as Redes Spoke, que podem ser redes de produção, desenvolvimento, logística e outras. Essas redes não teram acesso uma as outras.
Todas as redes Spokes, serão ligadas a rede de Hub através de um serviço chamado Peering.
