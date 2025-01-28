# resumo-do-lab-cmva
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Criação de Máquinas Virtuais no Azure

## 1. SLA (Service Level Agreement)

Os Acordos de Nível de Serviço (SLA) são compromissos por parte da Microsoft sobre a disponibilidade e desempenho dos serviços do Azure. Alguns pontos-chave a considerar:

- **Definição de SLA**: Entender o que o SLA cobre (como tempo de atividade e suporte) ajuda na escolha dos serviços a serem utilizados no Azure.
- **Impacto no Projeto**: Um conhecimento claro dos SLAs pode influenciar sua arquitetura, já que serviços com SLAs diferentes podem ter impactos diretos na disponibilidade e performance da sua aplicação.
- **Monitoramento**: É importante monitorar constantemente o desempenho dos serviços e garantir que eles estejam dentro dos parâmetros do SLA acordado para evitar surpresas.

## 2. Armazenamento no Azure

O armazenamento no Azure oferece diferentes opções que podem atender diversas necessidades de negócios. Os tipos de armazenamento mencionados incluem:

- **LRS (Locally Redundant Storage)**: Armazenamento em que os dados são replicados três vezes em um único datacenter. Isso oferece proteção contra falhas de hardware, mas não protege contra desastres que afetem a região inteira.
  
- **GRS (Geo-Redundant Storage)**: Este tipo de armazenamento replica os dados em uma região secundária, garantindo maior proteção contra falhas em larga escala. Assim, os dados são duplicados em duas localidades geograficamente separadas.

- **ZRS (Zone-Redundant Storage)**: Oferece replicação de dados em várias zonas de disponibilidade dentro de uma mesma região, garantindo resiliência e alta disponibilidade, mesmo em casos de falhas em uma zona específica.

- **GZRS (Geo-Zone-Redundant Storage)**: Combina as funcionalidades de GRS e ZRS, garantindo a replicação geográfica e proteção completa contra falhas em zonas.

Esses conceitos podem ser extremamente úteis na hora de decidir a melhor estratégia de armazenamento, considerando fatores como custo, redundância e níveis de disponibilidade exigidos pelo projeto.
