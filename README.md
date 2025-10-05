# Gerador de Placas de Carros

Microsoft SQL Server — Projeto completo (2018–2019)

Este repositório apresenta um script desenvolvido em T-SQL para gerar todas as combinações possíveis de placas de veículos no Brasil, incluindo o padrão antigo (ABC-1234) e o novo padrão Mercosul (ABC1D23). O projeto foi criado com fins didáticos e exploratórios, utilizando recursos nativos do SQL Server.

# 🎯 Objetivo

- - Simular a geração de placas válidas conforme os padrões brasileiros.

- - Demonstrar técnicas de manipulação de strings, controle de fluxo e modelagem de dados em SQL Server.

- - Servir como base para estudos, testes e aplicações educacionais.

# 📁 Estrutura do Script

O script realiza as seguintes operações:

1. Criação do banco de dados `GeradorDePlacas`

2. Criação de tabelas:

- `LetrasCombinadas`: combinações de três letras (AAA a ZZZ)

- `Numeracao`: faixa numérica de 0001 a 9999

- `Placas`: junção entre letras e números

- `FaixasDePlacasPorEstado`: faixas específicas por UF (em construção)

3. Inserção de dados:

- Geração automatizada das combinações alfabéticas

- Geração da numeração sequencial

- Montagem das placas completas

4. Consultas e visualizações:

- Exibição de placas geradas

- Filtros por prefixo, sufixo ou faixa numérica

- Simulação de placas Mercosul com letras embaralhadas

# ⚙️ Requisitos

- - Microsoft SQL Server (2016 ou superior)

- - Ambiente de execução: SQL Server Management Studio (SSMS)

# 🚀 Como usar

1. Clone o repositório:

    git clone https://github.com/pedrogalvaojunior/GeradorPlacaDeCarros.git

2. Abra o arquivo `.sql` no SSMS.

3. Execute os blocos de código na ordem indicada:

- Criação do banco

- Criação das tabelas

- Inserção dos dados

- Consultas de exemplo


# 📊 Exemplos de uso

- - Geração de placas como `ABC-1234`, `XYZ-9999`, `BRA1D23`

- - Filtros por estado, faixa de letras ou números

- - Simulação de placas inválidas para testes de validação

# 🎓 Aplicações Didáticas

- - Aulas de banco de dados e modelagem relacional

- - Exercícios de lógica e manipulação de dados

- - Simulações em sistemas de cadastro e controle de frota

# 📄 Licença

Este projeto está licenciado sob a MIT License.
