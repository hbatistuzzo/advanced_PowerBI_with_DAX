<div align="center">
  <img src="media/powerbi.png" alt="11" width="70%">
  <img src="media/dsa.png" alt="22" width="20%">
</div>

![GitHub top language](https://img.shields.io/github/languages/top/hbatistuzzo/advanced_PowerBI_with_DAX)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/hbatistuzzo/advanced_PowerBI_with_DAX)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hbatistuzzo/advanced_PowerBI_with_DAX)
![GitHub last commit](https://img.shields.io/github/last-commit/hbatistuzzo/advanced_PowerBI_with_DAX)

> __Warning__ In Progress!

Este repositório estrutura o conteúdo do curso "Power BI avançado para Análise de Dados com DAX" da Data Science Academy (~ 70 horas de duração, avançado). Além do Microsoft PowerBI, são utilizadas principalmente as linguagens **Python** para acessorar a manipulação de dados e o combo **SQL Server / SSMS** para modelagem do banco de dados.

<div align="center">
  <img alt="python" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />
  <img alt="SQLSERVER" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-original.svg" />
</div>


O curso é focado em dados OLAP (_OnLine Analytical Processing) i.e. já estruturados em formato de Data Warehouse, modelados utilizando um esquema tipo "estrela", uma vez que o interesse está mais nas consultas do que a modelagem do banco em si. A outra opção seria utilizar dados OLTP (_OnLine Transactional Processing).

O SQL Server disponibiliza amostras de datasets para exercícios didáticos [neste repositório](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases); em particular, utiliza-se no curso o dataset [Wide World Importers](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/wide-world-importers), cuja documentação pode ser consultada [aqui](https://learn.microsoft.com/en-us/sql/samples/wide-world-importers-what-is?view=sql-server-ver16). Uma breve descrição deste dataset é incluída abaixo caso você queira se familizar com o conteúdo:

---

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center;">
  <div style="flex: 1; min-width: 300px; padding-right: 10px;">
    <p>
      <em>Wide World Importers (WWI) é uma importadora e distribuidora atacadista de artigos de novidades, operando a partir da área da baía de São Francisco. Como atacadista, os clientes da WWI são principalmente empresas que revendem para indivíduos.
    </p>
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="media/wwi.png" alt="Wide World Importers Logo" style="max-width: 100%; height: auto; border-radius: 5px;" />
  </div>
</div>

_A WWI vende para clientes de varejo em todos os Estados Unidos, incluindo lojas especializadas, supermercados, lojas de informática, lojas de atrações turísticas e alguns indivíduos. A WWI também vende para outros atacadistas por meio de uma rede de agentes que promovem os produtos em nome da empresa. Embora todos os clientes da WWI estejam atualmente baseados nos Estados Unidos, a empresa pretende expandir-se para outros países/regiões._

_A WWI compra produtos de fornecedores, incluindo fabricantes de artigos de novidades e brinquedos, além de outros atacadistas de artigos de novidades. Eles armazenam os produtos em seu armazém da WWI e fazem novos pedidos aos fornecedores conforme necessário para atender aos pedidos dos clientes. Eles também compram grandes volumes de materiais de embalagem e os vendem em quantidades menores como conveniência para os clientes._

_Recentemente, a WWI começou a vender uma variedade de novidades comestíveis, como chocolates gelados. Anteriormente, a empresa não precisava lidar com itens refrigerados. Agora, para atender aos requisitos de manuseio de alimentos, eles precisam monitorar a temperatura em sua câmara frigorífica e em qualquer um de seus caminhões que possuam compartimentos refrigerados._

---

<i class="devicon-microsoftsqlserver-plain-wordmark"></i>


# $\color{red}{\textrm{Joining the 2 datasets: deaths and vaccinations}}$
## $\color{orange}{\textrm{Total Cases VS Total Deaths.}}$


![Abhinandan Trilokia](https://raw.githubusercontent.com/Trilokia/Trilokia/379277808c61ef204768a61bbc5d25bc7798ccf1/bottom_header.svg)