# Aula9
# Projeto Módulo 9: Tela de Login

### Cronograma de desenvolvimento: 

Prazo : início = 11/11/2024
        término = 06/12/2024

### Dia 1: Planejamento e Configuração Inicial

## Objetivos:
_Definir os requisitos do projeto.
_Configurar o ambiente de desenvolvimento.
_Criar a estrutura do projeto (diretórios, pastas e arquivos).
_Configurar o repositório Git para controle de código.
_Criar e documentar o arquivo README.md.

## Dia 2: Desenvolvimento do Layout HTML

# Objetivos:
_Criar a estrutura básica da tela de login usando HTML.
_Escrever o código HTML para a tela de login (index.html).
_Incluir todos os elementos necessários (campos de entrada, botões, links).

## Dia 3: Estilização com CSS

# Objetivos:
_Aplicar estilos à tela de login para torná-la visualmente atraente e responsiva.
_Escrever o código CSS para estilizar a tela de login (style.css).
_Garantir que o design seja responsivo (media queries para diferentes tamanhos de tela).

## Dia 4: Testes e Depuração

# Objetivos:
_Testar a aplicação para garantir que todas as funcionalidades estão funcionando corretamente.
_Realizar testes manuais para verificar a funcionalidade do formulário de login.
_Corrigir quaisquer bugs ou problemas encontrados durante os testes.

## Dia 5: Documentação e Refinamento Final

# Objetivos:
_Refatorar e documentar o código, garantindo clareza e manutenibilidade.
_Revisar e aprimorar a documentação do projeto (README.md).
_Garantir que o código esteja bem organizado e comentado.
_Preparar o projeto para entrega.


## Descrição do projeto
Este é um projeto simples que representa a interface de uma tela de login em HTML e CSS. Permite que os usuários façam login inserindo seus respectivos email e senha. Como se trata de um programa em desenvolvimento, foram utilizados links de acesso a própria plataforma do Moodle AVA, apenas para teste. O projeto também inclui um link para recuperação de senha, que pertence ao domínio nutead AVA. Ainda há a possibilidade da criação de um arquivo script.js pode ser usado para adicionar interatividade ao formulário, como validação de campo em tempo real dos dados inseridos pelo usuário.

## Desafios Enfrentados
Os desafios incluem a criação da interface visual para a o usuário, que, por sua vez, foi construida em HTML e CSS. No entanto, não obtive sucesso ao tentar criar uma ligação da estrutura front-end( HTML, CSS, JavaScript)do projeto com uma estrutura back-end(Python, PHP, Ruby, C++), já que não possuo o conhecimento necessário para tal feito. Pretendo no futuro, adicionar scripts para o armazenamento dos dados inseridos pelo usuário em um banco de dados, além de outras funcionalidades como:
  1. Que o sistema seja capaz de informar ao usuário se ele está cadastrado no sistema, e caso não esteja, que o usuário seja encaminhado para a página de cadastro.
  2. Inserir um sistema de validação de dados, como a verificação da sintaxe correta dos dados informados.
  3. Criar um sistema de recuperação de conta, caso o usuário não consiga efetuar o login.

## Estrutura do Projeto
O projeto está estruturado da seguinte maneira:
   Aula9
    ├── index.html (Este é o arquivo principal da página de login, o arquivo HTML, que é responsável pela semântica da interface visual do projeto)
    ├── style.css (Este é o arquivo responsável pela parte estilizada da interface visual da página de login, o arquivo CSS)
    └── README.md (#)

## Instruções de Uso
1. Acesse a página do GitHub.io em um navegador web com acesso a internet.
1. Clone ou faça o download deste repositório online no computador.
2. Se necessário, extrair o arquivo.
3. Abra o arquivo `index.html` em seu navegador de preferência.

## Estrutura do Arquivo HTML
O arquivo `index.html` contém a estrutura da tela de login:
- Um cabeçalho (representado pela tag `<head>`) que inclui tags responsáveis por:
    1. Determinar o título da página web e link para o CSS externo.<title>
    2. Tornar o documento transcrito para a Lingua Portuguesa.<language>
    3. Determinar o espaço determinado na tela para ser exibido o programa.<meta>

- Um corpo (`<body>`) com a marcação HTML do formulário de login, que inclui:
    1. Determinar a parte principal na tela de exibição. (<main>)
    2. Tags para determinar a infraestrutura do formulário de login.(<form>)
    3. Botões interativos para entrada no servidor(<button>)

# Estilo da Página de Login, Arquivo CSS

O arquivo `style.css` contém o estilo da tela de login:
O arquivo contém seletores para:
    1. /* Configurações globais de estilo da página*/
    2. /*Definir o visual da parte proferida como principal da página web*/
    3. /*Definir as configurações de estilo da interface interativa com o usuário*/ 
    4. /*Definir as configurações para diferentes tamanhos de tela (telas de tamanho médio como tablets)*/
    5. /*Definir as configurações para diferentes tamanhos de tela (telas de tamanho grande, como computadores, notebooks, monitores ou televisores)*/
    6. /*Definir as configurações para a versão mobile(telefones, celulares)*/

## Uso de Branches e Merges 
Facilitou muito a adição de novas funcionalidades ou correções no código sem afetar-lo diretamente.O que me permitiu integrar o trabalho e consolidar etapas de desenvolvimento do projetos. Elas mantem o código organizado e as merges asseguram que todas as mudanças sejam integradas de maneira coesa. Sendo muito útil no ambiente de desenvolvimento. No entanto, houve muita dificuldade para me adaptar ao uso da ferramenta, pois ocorreram vários problemas de compatibilidade e reconhecimento com minhas respectivas ferramentas de desenvolvimento e foram várias tentativas até obter sucesso.

### Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.mdpara mais detalhes.

### Contato
Para dúvidas ou sugestões, entre em contato pelo email: mariannafernandes697@gmail.com.
