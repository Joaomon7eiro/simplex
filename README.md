
**Commits desse repositório foram feitos em:

  https://gitlab.com/joaoagrom/simplex 
  
  https://github.com/leotramontini/aprendaSimplex
  
**1. NOME DOS INTEGRANTES DO GRUPO**

- João Vitor Monteiro Nandes      BCC
- Leonardo Gonçalves Tramontini   BCC
- Monique Elen Fernandes Altero   BCC
- Rafael Lepri                    BCC

**2. INTRODUÇÃO**

Este documento provê uma visão geral da versão da aplicação AprendaSimplex que está sendo liberada. Aqui descreveremos as funcionalidades do aplicativo, bem como seus problemas e limitações conhecidos. Por último são descritos as demandas e os problemas que foram resolvidos para liberação da versão atual.

**3.LINK DE ACESSO A APLICAÇÃO ONLINE**

[Acessar Aplicação AprendaSimplex](https://aprendasimplex.herokuapp.com/)

**4. NOTA DE RELEASE A SER PUBLICADO**

- Funções MIN E MAX
- Demonstrar tabela da programação dinâmica. Não possuir número fixo de itens
- Gerar passo a passo, que mostra todas as iterações necessárias para o resultado final
- Análise de Sensibilidade
- Opção para solução direta

**5. PROBLEMAS CONHECIDOS E LIMITAÇÕES**

- Necessário ao menos 1 conexão mínima com a internet
-

**6. DATAS IMPORTANTES**

Segue abaixo as datas importante do desenvolvimento:

| DATA ENTREGA | FEATURES |
| --- | --- |
| 03/05/2018 |  Informar valores na função Z |
|  |Informar valores de 3 restrições |
|  |Informar valores de 2 variáveis de decisão  |
|  |Solução direta |
| 17/05/2018 |   Selecionar maximizar e minimizar  
| |Informar quantidade de variável de decisão  |
| |Informar quantidade de restrições 
| | Fazer passo a passo Resultado mais fácil compreender |
| 31/05/2018 |  Explicação do passo a passo
| | Tratar os resultados para entendimento do usuário 
|  |Documentação final da aplicação 
| |Mostra os valores de sombra, limites máximos e mínimos |

**7. COMPATIBILIDADE**

Segue abaixo os requisitos:

| REQUISITOS | FERRAMENTA |
| --- | --- |
| Navegadores | Mozzilla Firefox, Chrome, Internet Explorer e Microsoft Edge |
| Sistema operacional | Linux e Windows |
| Dispositivos Móveis | IOS e Android |



|  TECNOLOGIAS |   |
| --- | --- |
| Linguagem de programação | JavaScript e JQuery |
| Tecnologia WEB | HTML, CSS, Bootstrap |
| IDE | Sublime Text 2 |
| Servidor Web | Heroku|

**8. PROCEDIMENTO E ALTERAÇÃO DE CONFIGURAÇÃO DO AMBIENTE**

O projeto foi implementado com a linguagem JavaScript com o auxílio da biblioteca JQuery, devido ao conhecimento dos membros do grupo e também para melhorar o aprendizado na própria linguagem. Na parte visual foi usado HTML, CSS3 e Bootstrap, pela sua fácil adesão e modificação. Já a hospedagem foi feita no Heroku, por já ter sido usado antes por membros do grupo.

**9. ATIVIDADES REALIZADAS NO PERÍODO**

Nessa liberação foram contemplados os seguintes itens:

| Cód | Título | Tarefa | Situação | Observação |
| --- | --- | --- | --- | --- |
| 1 | Maximizar | Montar a Tabela Simplex, e possibilitar o usuário a maximizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de &quot;&lt;=&quot; |
| 2 | Minimizar | Montar a Tabela Simplex, e possibilitar o usuário a minimizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de &quot;&lt;=&quot; |
| 3 | Adição de restrições | Possibilitar o usuário a adicionar inputs para maiores números de restrições. | Concluído |   |
| 4 | Demonstrar passo a passo | Demonstrar ao usuário as alterações na tabela causada pelas iterações do método simplex. | Concluído |   |
| 5 | Tabela de Sensibilidade | Demonstrar ao usuário tabela de sensibilidade. | Concluído |   |
