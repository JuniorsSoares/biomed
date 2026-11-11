# Conciliação de recebimentos

Sistema em um único arquivo (`index.html`) para conferir vendas de **cartão** e **Pix** e conciliar com o **extrato bancário** (Sicoob) e o **Unilab**.

## Como usar
1. Abra o `index.html` no navegador.
2. Carregue o relatório CSV de vendas de cartão (ou um progresso salvo).
3. Use as abas: **Cartão**, **Pix**, **Conciliação bancária** e **Resumo por unidade**.
4. No fim do dia, clique em **Salvar progresso** para guardar a conciliação.

## Dados sensíveis
Os arquivos de trabalho (CSV, PDF e o `.json` de progresso) contêm nomes de pagadores e **não devem ser enviados ao repositório**. O `.gitignore` já os bloqueia.
