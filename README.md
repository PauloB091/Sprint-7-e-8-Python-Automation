# Python para Automacao de Testes

Repositorio documentando o estudo de Python aplicado a automacao de testes, cobrindo logica de programacao, ferramentas de desenvolvimento e testes automatizados com Selenium.

Python Basico

- Sintaxe basica, variaveis e tipos de dados
- Estruturas condicionais (if, elif, else)
- Lacos de repeticao (for, while)
- Funcoes e escopo
- Listas, tuplas, dicionarios e conjuntos
- Tratamento de excecoes (try, except, finally)

Logica de Programacao

- Raciocinio logico aplicado a resolucao de problemas
- Algoritmos e fluxo de execucao
- Estrutura de dados basicas
- Boas praticas de codificacao

Ferramenta PyCharm

- Configuracao de interpretador e virtual environment
- Atalhos uteis: Ctrl+Shift+F10 (executar), Ctrl+D (duplicar linha), Ctrl+Alt+L (formatar)
- Depuracao com breakpoints
- Integracao com Git pelo IDE

Git e GitHub

- Comandos principais: git init, git add, git commit, git push, git pull
- Branchs e merge
- .gitignore para projetos Python
- Commits semanticos e versionamento

PyTest

- Estrutura de arquivos de teste (test_*.py)
- Asserts e validacoes
- Fixtures para setup e teardown
- Marcadores (mark) para categorizacao
- Execucao via terminal e relatorios

Seletores CSS e XPath

CSS: seletores por tag, classe, ID, atributo e combinacoes
XPath: caminho absoluto vs relativo, //, @, contains(), text()

| Tipo | CSS | XPath |
| Por ID | #login | //*[@id='login'] |
| Por classe | .btn-primary | //*[@class='btn-primary'] |
| Por atributo | [data-test='submit'] | //*[@data-test='submit'] |
| Por texto | - | //button[text()='Enviar'] |

Selenium WebDriver

- Instalacao e configuracao do WebDriver
- Localizacao de elementos (find_element, find_elements)
- Acoes: click, send_keys, submit
- Esperas implicitas e explicitas (WebDriverWait)
- Navegacao entre abas e janelas

Page Object Model (POM)

Conceito: cada pagina da aplicacao vira uma classe. A Page Object mapeia os elementos e acoes da pagina, enquanto os casos de teste utilizam esses objetos para executar as validacoes.

Estrutura do Repositorio

python-basico/        Exercicios de fundamentos da linguagem
logica-programacao/   Algoritmos e estrutura de dados
pytest-tests/         Testes com PyTest
selenium-tests/       Automacao com Selenium WebDriver
  pages/              Page Objects
  tests/              Casos de teste
requirements.txt      Dependencias do projeto

Ferramentas

| Ferramenta | Utilizacao |
| Python | Linguagem de programacao principal |
| PyCharm | IDE para desenvolvimento |
| Git/GitHub | Controle de versao e hospedagem do repositorio |
| PyTest | Framework de testes |
| Selenium WebDriver | Automacao de testes em navegadores |
