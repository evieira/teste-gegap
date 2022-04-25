Questão 1) 

private static boolean isOn () { 
	return !isOff();
} 


Questão 2)

private List<Item> processarItens(List<Item> itens) {
        List<Item> itemsComErro = new ArrayList<>();
        for (Item i: itens) {
            try {
                process(i);
            } catch (Exception e) {
                itemsComErro.add(i);
            }
        }
        return itemsComErro;
    }

Questão 3)

Passo 1 – Gerar uma nova branch a partir da trunk
Passo 2 – executar a correção
Passo 3 – executar os testes necessários
Passo 4 – fazer o merge com a trunk
Passo 5 – gerar uma tag
Passo 6 – fazer o build e o deploy

Questão 4)

select p.NOME, s.SALARIO from PESSOA p 
  join SALARIO s on p.ID_PESSOA = s.ID_PESSOA
where p.CPF = '123.123.123-12'                                    
and '2018-06-01' between DATA_INICIO_VIGENCIA AND DATA_FIM_VIGENCIA

Questão 5)
SELECT sum(p.SALARIO+b.VALOR_BENEFICIO) from PESSOA 
  p join BENEFICIO b on p.CD_PESSOA = B.CD_PESSOA

Questão 6)

É uma constraint que define um campo como único no banco de dados e é usado para impedir que dois registros com o mesmo valor sejam inseridos na tabela.

Questão 7)

O AngularJS utiliza javascript, e tem a estrutura de controllers. Já Angular utiliza TypeScript e tem a estrutura de componentes.

Questão 8)

Com o maven é feito o gerenciamento das bibliotecas do projeto e também é configurado as etapas de build da aplicação.
Desde a compilação, execução de testes unitários e de integração, e geração do arquivo binário do projeto. Também é possível configurar outras funções como atualização do banco de dados usando flyway ou liquibase, por exemplo.

Questão 9)

GET: é utilizado para fazer consultas à API.
POST: é utilizado para salvar novos registros na API.
PUT: é utilizado para atualizar um registro na API.
PATCH: é utilizado para atualizar parcialmente um registro na API.
DELETE: é utilizado para apagar registros na API.

Questão 10)

Questão 11)

é uma função reutilizável essencial para o processamento de grandes volumes de dados.

O step é um passo independente a ser executado por um job.

MAVEN - 10
SPRING MVC - 9
SVN - 8
SPRING BATCH
JAVASCRIPT/JQUERY - 6
GIT - 10
SPRING DATA - 9
AJAX/REST - 9
WEBSPHERE - 4
JENKINS - 9
ANGULAR 2 - 7
SPRINGBOOT - 9
ENTERPRISE ARQUITECT - 6


