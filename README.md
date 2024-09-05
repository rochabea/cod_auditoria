# cod_auditoria
Código utilizado para separar os atendimentos que devem ir para a auditoria

## INSTRUÇÕES DO CÓDIGO
- Necessário que você importe o arquivo do relatório B+P mais atual, como fazer isso? Vá até o simbolo de pasta e clique nele, após isso importe o documento clicando no ícone de Documento e selecionando o documento nessário. É importante que você renomeie o arquivo como está no códio, 'SGT.xlsx'

## Explicação do Código
- O código está fazendo um filtro pelo status Concluído e pelo Produto (ME e EE)
- A linha que possui o 'PORTE RECEITA' ou 'PORTE CONTRATAÇÃO' como Demais é pintada de amarelo
- Também é feito um filtro de acordo com o período definido
- É feito um cálculo de 20% dos atendimentos de cada Regional e separado em uma nova planilha (os 20% e 80%)
- É feito um embaralhamento nas planilhas geradas
- Após está etapa é juntado as duas planilhas geradas
- Com isso, é lido a planilha que iremos usar como referência e aplicado as função em cima desse arquivo
- Logo após isso, é aplicado a formatação de colorir a primeira linha após os 20%
