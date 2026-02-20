🎮 Dashboard de Vendas - Xbox Game Pass
Este projeto consiste em uma ferramenta de análise de dados desenvolvida em Excel para monitorar, visualizar e gerenciar as vendas de assinaturas do serviço Xbox Game Pass. O objetivo é fornecer insights rápidos sobre a performance de diferentes planos, receitas adicionais (add-ons) e comportamento dos assinantes.

📋 Sobre o Projeto
O arquivo atua como um sistema completo de Business Intelligence (BI) de baixo código. Ele processa uma base de dados bruta de assinantes e transforma esses dados em métricas visuais, permitindo a tomada de decisão baseada em dados reais de vendas, renovações e upsells (como Season Passes).

🗂 Estrutura do Arquivo
O projeto está organizado em quatro abas (planilhas) principais, cada uma com uma função específica:

1. Dashboard (D̳ashboard)
A interface visual do usuário.

Conteúdo: Exibe o título "XBOX GAMEPASS SUBSCRIPTION SALES" e os principais KPIs.

Período de Análise: 01/01/2024 a 31/12/2024.

Função: Apresentar o resumo executivo dos dados para leitura rápida.

2. Bases (B̳ases)
A fonte de dados bruta (Raw Data). Cada linha representa um assinante único.

Colunas Principais:

Subscriber ID: Identificador único do cliente.

Name: Nome do assinante.

Plan: Tipo de plano (ex: Ultimate, Standard, Core).

Start Date: Data de início da assinatura.

Auto Renewal: Status de renovação automática (Yes/No).

Subscription Type: Periodicidade (Annual, Monthly, Quarterly).

Add-ons: Colunas indicando compra de "EA Play Season Pass" e "Minecraft Season Pass".

Total Value: Valor final da transação (Assinatura + Add-ons - Cupons).

3. Cálculos (C̳álculos)
A camada de processamento de dados.

Função: Contém as Tabelas Dinâmicas (Pivot Tables) e fórmulas auxiliares que agregam os dados da aba Bases.

Processamento: Calcula somas de valores totais, contagem de assinaturas por tipo e consolida a receita dos Season Passes (EA Play e Minecraft).

4. Assets (A̳ssets)
Guia de estilos e recursos visuais.

Conteúdo: Paleta de cores oficial da marca e referências para ícones.

Xbox Color: #9BC848, #22C55E.

Menus: #2AE6B1, #5BF6A8.

Backgrounds: #E8E6E9.

📊 Instruções para Reprodução e Uso
Para utilizar ou atualizar este dashboard, siga os passos abaixo:

Pré-requisitos
Microsoft Excel (versão 2016 ou superior recomendada para suporte total a gráficos dinâmicos).

Como Atualizar os Dados
Abra a aba Bases.

Insira os novos dados de vendas nas colunas correspondentes, mantendo a formatação existente (datas em AAAA-MM-DD e valores numéricos).

Certifique-se de que a coluna Total Value esteja calculando corretamente (geralmente a soma do preço da assinatura + season passes - descontos).

Como Atualizar o Dashboard
Como o projeto utiliza a aba Cálculos como intermediária:

Após inserir os dados na aba Bases, vá até a guia Dados no menu superior do Excel.

Clique no botão Atualizar Tudo (Refresh All).

Isso forçará as tabelas dinâmicas na aba Cálculos a lerem as novas linhas da Base, atualizando automaticamente os gráficos na aba Dashboard.

🛠 Tecnologias Utilizadas
Microsoft Excel:

Tabelas Dinâmicas (Pivot Tables).

Segmentação de Dados (Slicers) - Sugerido para interatividade.

Fórmulas condicionais.

Última atualização dos dados: 25/01/2026
