# ROLETA DE CORES

## OBJETIVOS 
O objetivo consiste em sortear uma cor aleatória da roda de cores e gerar uma intercessão com uma segunda cor escolhida pelo usuário, usando um cálculo  de interpolação entre valores RGB/HEX

### STACK TECNÓLOGICO
Backend: PHP estruturado em sessões narrativas
Banco de dados: MySQL (PDO para segurança)
Frontend: HTMLS, PHP, CSS, Taiwind CSS

#### Regras de negocio (CORE) 
Não dá para por duas cores na mesma caixa, não dá para rolar a roleta enquanto estiver em animação de rodar, Não dá para escolher uma cor fora do banco de dados

##### Regras globais
- Use sempre o mesmo PDO para conexão e quieres no MySQL para evitar SQL Injections
- Mantenha o código limpo e comente apenas logicas complexas.
- Separe os arquivos  de forma logica: um arquivo para conexão com a base (bd.php) e scrips de backend isolados em views em HTML5/PHP
- Estilize as telas em tailwind de forma responsiva priorizando o MobileFrist.
- Retorne sempre as mensagens de erros de forma claras na interface para o usuário (TOAST)
- sempre trate as mensagens de caixa de mensagens de caixa de mensagens nativas de mensagens nativas do navegador em um MODAL
