# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Conceitos Fundamentais da Computação em Nuvem (AZ-900)
A certificação AZ-900: Microsoft Azure Fundamentals é o ponto de partida para profissionais que desejam validar seus conhecimentos básicos sobre serviços em nuvem e como eles são fornecidos com o Microsoft Azure.

O que é Computação em Nuvem?
É a entrega de serviços de computação (como servidores, armazenamento, bancos de dados, redes, software e análise) através da internet. O objetivo é oferecer inovação mais rápida, recursos flexíveis e economia de escala. Em vez de adquirir e manter sua própria infraestrutura, você pode acessar esses serviços de um provedor de nuvem conforme a necessidade.

Tipos de Nuvens (Modelos de Implantação)
Existem três modelos principais para implantar serviços de nuvem, cada um com diferentes níveis de controle, gerenciamento e custo.

1. Nuvem Pública
Definição: A infraestrutura de computação é totalmente gerenciada por um provedor de nuvem (como Microsoft Azure, AWS, Google Cloud) e disponibilizada para múltiplos clientes através da internet.

Características Principais:

Sem Despesas de Capital (CapEx): Não há necessidade de investir em hardware físico.

Agilidade: Recursos podem ser provisionados e desprovisionados rapidamente.

Modelo de Pagamento: Você paga apenas pelo que consome (pay-as-you-go).

Manutenção: O provedor é responsável pela manutenção, segurança e atualização do hardware e da infraestrutura física.

2. Nuvem Privada
Definição: Um ambiente de nuvem exclusivo para uma única organização. A infraestrutura pode estar localizada no datacenter local da empresa ou ser hospedada por um provedor de serviços terceirizado.

Características Principais:

Controle Total: A organização tem controle completo sobre os recursos, a arquitetura e a segurança.

Responsabilidade: A própria empresa é responsável pela manutenção, atualização e gerenciamento do hardware e software.

Segurança e Privacidade: Oferece um nível mais alto de isolamento e privacidade, sendo ideal para setores com regulamentações rígidas.

3. Nuvem Híbrida
Definição: É uma combinação estratégica de nuvens públicas e privadas, interligadas por tecnologia que permite que dados e aplicações sejam compartilhados entre elas.

Características Principais:

Flexibilidade: Permite que as empresas aproveitem os benefícios da nuvem pública (como escalabilidade e custo-benefício) para cargas de trabalho não críticas, enquanto mantêm dados e aplicações sensíveis em seu ambiente privado.

Escalabilidade sob Demanda: É possível usar a nuvem pública para "transbordar" (bursting) a capacidade quando a demanda excede os recursos da nuvem privada.

Modelos Financeiros: CapEx vs. OpEx
A mudança para a nuvem também representa uma transformação no modelo de investimento em TI.

CapEx (Capital Expenditure - Despesa de Capital)
O que é: O investimento inicial em infraestrutura física, como a compra de servidores, switches, racks e equipamentos de refrigeração para montar um datacenter.

Modelo Tradicional: Associado principalmente a ambientes locais (on-premises) e nuvens privadas. O valor do investimento é depreciado ao longo do tempo.

OpEx (Operational Expenditure - Despesa Operacional)
O que é: O gasto contínuo em serviços ou produtos, pago conforme o uso. Não há um grande investimento inicial.

Modelo de Nuvem: Este é o modelo predominante na nuvem pública. Você paga uma fatura (geralmente mensal) baseada no consumo real dos recursos, transformando um grande investimento de capital em uma despesa operacional previsível.

O Modelo Baseado em Consumo
Este é o coração do modelo financeiro da nuvem pública (OpEx). As principais características são:

Pague pelo que usar: A cobrança é baseada no uso real dos serviços.

Sem custos iniciais: Elimina a necessidade de grandes investimentos em hardware.

Faturamento claro: Os preços são detalhados por recurso e serviço, e a fatura reflete o consumo exato durante o período.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Benefícios da Computação em Nuvem
A computação em nuvem oferece uma série de vantagens estratégicas para empresas de todos os portes. Estes são os principais benefícios:

1. Alta Disponibilidade
Garante que os recursos e serviços contratados estejam acessíveis e operacionais sempre que necessário. A disponibilidade é formalizada através de um Acordo de Nível de Serviço (SLA), que especifica o tempo de atividade garantido para cada serviço. Caso o provedor de nuvem, como o Microsoft Azure, não cumpra o SLA estabelecido, a empresa pode receber créditos para uso futuro na plataforma.

2. Escalabilidade
Refere-se à capacidade de ajustar a quantidade de recursos (como poder de processamento, armazenamento e memória) para atender à demanda. A escalabilidade pode ser:

Vertical (Scale-Up): Aumentar a capacidade de um único recurso, como adicionar mais CPU ou RAM a uma máquina virtual.

Horizontal (Scale-Out): Adicionar mais instâncias de um recurso, como adicionar mais máquinas virtuais para distribuir a carga de trabalho.

Isso permite que você pague apenas pelos recursos que efetivamente utiliza, otimizando os custos.

3. Elasticidade
A elasticidade é a capacidade do ambiente em nuvem de se dimensionar de forma automática e dinâmica com base na demanda em tempo real. É ideal para lidar com picos de tráfego inesperados ou sazonais.

Exemplo Prático: Durante a Black Friday, uma loja virtual pode configurar seu ambiente para adicionar (escalar horizontalmente) ou remover (reduzir) recursos automaticamente com base no número de requisições dos usuários. Isso garante que o site permaneça estável durante o pico de acessos e que os custos sejam reduzidos quando a demanda diminuir.

4. Confiabilidade e Alcance Global
A nuvem permite a implantação de recursos em múltiplas regiões geográficas ao redor do mundo. Essa distribuição global aumenta a confiabilidade e a resiliência da aplicação. Em caso de um desastre natural ou falha em uma região, as outras regiões continuam operando, garantindo a continuidade dos negócios.

5. Previsibilidade de Custos
Oferece uma maior previsibilidade tanto no desempenho dos recursos quanto nos custos operacionais. Com ferramentas de monitoramento e calculadoras de preços, é possível estimar com mais confiança os valores que serão cobrados ao final do mês, evitando surpresas no orçamento.

Claro! Suas anotações sobre os tipos de serviços de nuvem estão ótimas como ponto de partida. Abaixo, elas estão aprimoradas e organizadas em um formato mais claro e didático, ideal para estudo e consulta.

Modelos de Serviço da Computação em Nuvem
Os serviços de nuvem são geralmente divididos em três modelos principais. Cada um oferece um nível diferente de controle, flexibilidade e gerenciamento, permitindo que você escolha o que melhor se adapta às suas necessidades.

1. IaaS (Infrastructure as a Service - Infraestrutura como Serviço)
Este é o modelo mais flexível de serviço em nuvem. Essencialmente, você está alugando a infraestrutura de TI — servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais — de um provedor de nuvem.

O que você gerencia: Você tem controle total sobre o sistema operacional, os aplicativos, os dados e as configurações de rede. É sua responsabilidade instalar, configurar e gerenciar o software.

O que o provedor gerencia: O provedor de nuvem cuida da infraestrutura física subjacente, como os datacenters, servidores físicos, armazenamento físico e a rede.

Ideal para: Equipes de TI que precisam de controle máximo e flexibilidade para construir e personalizar seus ambientes do zero.

Exemplos: Máquinas Virtuais do Azure (VMs), Amazon EC2, Armazenamento do Azure (Azure Storage), Redes Virtuais do Azure (VNet).

Analogia: Pense no IaaS como alugar um terreno. Você tem a liberdade de construir a casa que quiser, com os materiais que escolher, mas a fundação e a infraestrutura básica (água, luz) são fornecidas pelo proprietário do terreno.

2. PaaS (Platform as a Service - Plataforma como Serviço)
Este modelo fornece um ambiente completo de desenvolvimento e implantação na nuvem, sem a complexidade de gerenciar a infraestrutura subjacente. Você se concentra em criar, testar e implantar seus aplicativos.

O que você gerencia: Apenas seus aplicativos e dados.

O que o provedor gerencia: O provedor cuida de tudo o que está por baixo da aplicação: servidores, sistemas operacionais, armazenamento, redes, bancos de dados e ferramentas de desenvolvimento.

Ideal para: Desenvolvedores que querem focar na criação de software sem se preocupar com a manutenção da infraestrutura, sistemas operacionais ou atualizações de segurança.

Exemplos: Banco de Dados SQL do Azure, Serviço de Aplicativo do Azure (Azure App Service), Heroku, Google App Engine.

Analogia: O PaaS é como alugar uma oficina ou um estúdio de arte. Todas as ferramentas, bancadas e a infraestrutura do prédio já estão lá para você usar. Sua única preocupação é criar sua obra de arte (seu aplicativo).

3. SaaS (Software as a Service - Software como Serviço)
Este é o modelo mais comum e pronto para uso. O software é fornecido sob demanda, geralmente em um modelo de assinatura, e é acessado pela internet. Não há necessidade de instalar ou gerenciar qualquer infraestrutura ou plataforma.

O que você gerencia: Apenas o seu uso do software e seus dados dentro dele.

O que o provedor gerencia: O provedor de nuvem gerencia absolutamente tudo: a aplicação, os dados, o tempo de execução, os servidores, o armazenamento, a rede e o sistema operacional.

Ideal para: Usuários finais e empresas que buscam uma solução pronta para uso, sem qualquer tipo de gerenciamento técnico.

Exemplos: Microsoft 365 (Office 365), Microsoft Teams, Salesforce, Gmail, Dropbox.

Analogia: O SaaS é como alugar um apartamento totalmente mobiliado e com todos os serviços inclusos (água, luz, internet, limpeza). Você simplesmente entra e começa a usar, sem se preocupar com a manutenção ou com os móveis.

7. Segurança (Responsabilidade Compartilhada)
Os provedores de nuvem oferecem uma vasta gama de ferramentas e serviços de segurança avançados. No entanto, a segurança na nuvem opera em um modelo de responsabilidade compartilhada. O provedor é responsável pela segurança da nuvem (infraestrutura física, rede), enquanto o cliente é responsável pela segurança na nuvem (configuração de acesso, proteção de dados, implantação correta das ferramentas de segurança).

8. Governança e Conformidade
A governança na nuvem estabelece padrões e políticas para garantir que o ambiente opere de maneira segura, otimizada e em conformidade com as regulamentações. Ferramentas de auditoria podem sinalizar recursos que estão fora dos padrões definidos e fornecer estratégias de mitigação para corrigir desvios, garantindo uma gestão centralizada e padronizada.

9. Gerenciabilidade
A nuvem simplifica a gestão da infraestrutura de TI. Os recursos podem ser gerenciados de diversas formas, adaptando-se às preferências da equipe técnica:

Interfaces Gráficas: Portal web intuitivo.

Linha de Comando: Ferramentas como PowerShell e CLI (Command-Line Interface).

Infraestrutura como Código (IaC): Ferramentas como Terraform e modelos ARM/Bicep para implantar e gerenciar recursos de forma automatizada e replicável.

Além disso, a capacidade de escalar recursos automaticamente e implantar ambientes complexos a partir de modelos pré-configurados agiliza significativamente as operações.
