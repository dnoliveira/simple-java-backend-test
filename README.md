# Simple Java Backend Test

## Descrição:

O teste a seguir é dividido em duas partes que serão avaliadas e contemplam o 
ambiente de desenvolvimento `Java + Spring boot`. Dado o cenário em que a empresa 
NFE Now necessita de uma aplicação para cadastrar as notas fiscais por cliente.


## `1a parte - O Projeto:`

Criar uma tabela e um microserviço para o cadastro de NFe. Os campos para o cadastro 
da NFe são: CNPJ, Endereço, Razão Social, Valor, Número da nota (este deverá ser gerado 
sequencialmente) e Número de série.

O projeto deverá:
1) ser entregue no GitHub com acesso público;
2) conter o script de criação da tabela para o mysql (informar qual a versão do mysql);
3) conter todo o código do projeto;
4) ter um readme.md com as instruções necessárias para a implantação;
5) fornecer as URLs e os bodys como exemplos de chamadas http para a:
   1) criação de uma NFE;
   2) consulta de uma NFE;
   3) consulta de todas as NFEs;
   4) alteração de uma nota;
   5) exclusão de uma nota.

Será avaliado:
1) O manual de implantação;
2) O script *.sql de criação do banco de dados;
3) Clareza e organização de código;
4) Injeção de depedência;
5) Padrões de arquitetura;
6) Lidar com Exceptions e Logs.

Será um adicional:
1) entregar pelo menos um teste utilizando o JUnit.
2) entregar um controle acesso utlizando o Spring Security.

## `2a parte - Entrevista técnica:`

Caso o avaliador do projeto achar necessário, poderemos marcar uma entrevista técnica.
