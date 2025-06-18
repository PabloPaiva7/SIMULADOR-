📊 Análise e Simulador de Desconto por Banco
Este projeto é um mini aplicativo em Streamlit que permite ao usuário:

✅ Analisar a média de desconto aplicada por banco com base em dados históricos
✅ Simular o valor do desconto e o saldo final devedor após o desconto

🚀 Funcionalidades
Leitura de dados de um arquivo CSV contendo informações sobre percentuais de desconto por banco.

Cálculo automático da média percentual de desconto para cada banco.

Simulador interativo, no qual o usuário informa:

O saldo devedor (R$)

O banco para o qual deseja simular o desconto

Exibição dos resultados da simulação:

Desconto médio do banco

Valor estimado do desconto

Valor final com o desconto aplicado

🛠️ Como funciona o código?
1️⃣ O app configura o layout em tela cheia e define o título da página.
2️⃣ Lê os dados do arquivo CSV localizado no caminho:

mathematica
Copiar
Editar
C:\Users\pablo paiva\PROJETOS\CÓDIGO\relatorio.csv
(⚠️ Você deve ajustar o caminho do arquivo conforme a sua máquina ou ambiente.)

3️⃣ Trata a coluna PERCENTUAL:

Remove o símbolo %

Substitui vírgulas por pontos

Converte os valores para tipo float

4️⃣ Agrupa os dados por banco e calcula a média percentual de desconto.

5️⃣ Cria um formulário interativo:

Usuário informa o saldo devedor.

Seleciona um banco a partir dos bancos disponíveis no arquivo.

6️⃣ Ao submeter o formulário:

O app calcula o valor médio do desconto aplicado ao saldo informado.

Mostra os valores do desconto e do saldo final com o desconto.

📂 Estrutura esperada do arquivo CSV
O arquivo CSV deve conter, no mínimo, as seguintes colunas:

BANCO	PERCENTUAL
Nome do Banco	Percentual do desconto aplicado (ex: 15,5%)
