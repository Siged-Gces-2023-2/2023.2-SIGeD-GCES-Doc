# Sprint 1

## Duração
- Início: 19/09/2023
- Término: 05/10/2023

## Sobre o SIGeD
<p align="justify">&emsp;&emsp;SiGeD (Sistema de Gerenciamento de Demandas) tem o próposito de facilitar o gerenciamento de vários serviços da DPSS - Divisão de Proteção à Saúde do Servidor do estado de Goiás, promovendo uma interface entre funcionários de diferentes setores da área, auxiliando os funcionários da DPSS a cadastrar pacientes e atendimentos, facilitando também a atualização e visualização dos dados dos pacientes, serviços e demandas.</p>

### Arquitetura

#### Front-end
A aplicação web utiliza no front-end o framework **React**. A divisão é feita da seguinte forma:

- **Pages:** armazena as telas do website.
- **Services:** local onde são realizadas as comunicações com a API.
- **Components:** reúne os componentes utilizados nas telas da aplicação, como botões e a navbar.
- **Constants:** armazena os códigos das cores utilizadas.

#### Back-end
<p align="justify">&emsp;&emsp;Os microsserviços foram construídos utilizando <b>NodeJS</b> e o framework <b>Express.js</b>, em que cada microsserviço tem um banco de dados não relacional MongoDB independente. Dada a alta escalabilidade dos microsserviços, foram definidos seis para essa aplicação, sendo eles: <b>Users, Clients, Demands, Cargos, Sectors e Patrimonio</b>.</p>

<center>

  ![diagrama de relações](https://github.com/Siged-Gces-2023-2/2023.2-SIGeD-GCES-Doc/assets/79341819/c3ebdbf1-c6c5-4122-8e38-deb955896e81)

</center>

<figcaption align="center">Figura 1: Diagrama de relações. (Fonte: Autor, 2023).</figcaption>

## Planejamento
- Subir o ambiente: objetivo de todos estarem com o projeto rodando ao final da sprint;
- Dividir os pareamentos para melhor colaboração na execução das issues;
- Entrar em contato com o mantenedor.

## Execução
- Divisão dos pareamentos: dividimos os grupos, ficando dois trios e um quarteto.
    - Artur, Bianca Sofia e Guilherme
    - Bruno, Davi e Lucas
    - Ana, Débora, Gustavo e Laís
- Entramos em contato com o mantenedor e combinaremos um horário para nossas reuniões.

## Problemas enfrentados
<p align="justify">&emsp;&emsp;Os alunos Ana, Bruno e Gustavo não conseguiram subir o ambiente. Os integrantes relatam problemas com o Docker e sistema operacional.</p>

<p align="justify">&emsp;&emsp;Os integrantes do grupo relatam dificuldades de entendimento das diversas documentações e suas versões. Alguns novos problemas não mapeados foram identificados e o grupo pretende documentá-los nas próximas sprints.</p>

## Issues planejadas
| ID |Descrição | Responsável | Status |
| :--: | :-----: | :---------: | :-----:|
| [#3](https://github.com/Siged-Gces-2023-2/2023.2-SIGeD-GCES-Doc/issues/3) | Criar o relatório do Inventário dos itens patrimoniais do SIGED | Artur, Bianca Sofia, Guilherme | Em andamento |
| [#5](https://github.com/Siged-Gces-2023-2/2023.2-SIGeD-GCES-Doc/issues/5) | Relatório de todas as demandas por cliente | Davi, Lucas, Bruno | Em andamento |
| [#7](https://github.com/Siged-Gces-2023-2/2023.2-SIGeD-GCES-Doc/issues/7) | Mapeamento de Erros e Melhorias | Ana, Débora, Gustavo, Laís | Em andamento|


<figcaption align="center">Tabela 1: Issues planejadas na sprint.</figcaption>


## Conclusão
<p align="justify">&emsp;&emsp;Pelo foco da sprint ter sido buildar o ambiente e alinhar os membros do grupos em divisão de tarefas, nenhuma issue foi finalizada.</p>

<p align="justify">&emsp;&emsp;Após debate entre o grupo foi definido que a próxima sprint terá divisão em pares. Além disso também iremos fazer uma reunião com o Bruno para o esclarecimento das issues.</p>

## Histórico de versão
| Versão | Data | Descrição | Autor |
| :----: | :--: | :-------: | :---: |
| 1.0 | 04/10/2023 | Elaboração do documento | Todos |