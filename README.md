 
# Ferramenta de Controle de Investimentos Imobiliários

## Descrição do Projeto

Este trabalho envolve a criação de uma ferramenta no **Microsoft Excel** para modelagem de investimentos em Fundos de Investimento Imobiliário (FIIs).  
A planilha possibilita ao usuário realizar previsões financeiras, automatizando operações como o montante total aplicado, capital acumulado e rendimentos mensais, contribuindo para decisões de investimento mais conscientes e planejadas.

## Funcionalidades da Ferramenta

- Modelagem de aportes mensais e por período definido
- Cálculo automático do total investido ao longo do tempo
- Previsão do capital acumulado com base no retorno mensal
- Estimativa dos rendimentos recebidos mensalmente
- Interface intuitiva para inserção de dados e visualização dos resultados
- Com base no perfil do investidor (*Conservador, Moderado ou Agressivo*), a planilha emprega a função **PROCV** para localizar automaticamente uma sugestão de distribuição de investimentos entre diversos tipos de ativos
- Simulações e sugestões são exibidas em porcentagens de distribuição recomendada para cada classe de investimento, conforme o perfil detectado

## Tecnologias e Funções Utilizadas

- **Microsoft Excel**
- Fórmulas:
  - `VF`
  - `PROCV` (*VLOOKUP*)
  - Multiplicações diretas (*percentual × valor total*)
  - Formatação Condicional
  - Organização estética de dados

## Prints da Planilha



![Tela inicial da planilha](print1.png)  
*Legenda: Tela inicial*

![Exemplo de simulação de perfil](print2.png)  
*Legenda: Simulação para perfil Moderado*

## Observações

> Este trabalho tem fins exclusivamente educacionais.  
> Os dados de rendimento e patrimônio foram estimados apenas para ilustrar o uso das ferramentas do Excel.  
> Para uso real em finanças, recomenda-se consultar especialistas certificados.

---
