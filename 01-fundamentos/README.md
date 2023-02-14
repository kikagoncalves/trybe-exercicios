# EXERCÍCIOS

## Parte I - Criação de arquivos e diretórios

Dica 👀: Para a criação de arquivos vazios, você pode utilizar o comando touch nome-do-arquivo.extensao.


1. Utilizando o terminal, aplique o comando de criação de diretórios que você aprendeu: crie um diretório chamado unix_tests e navegue até ele.

2. Crie um arquivo de texto com o nome trybe.txt.

3. Crie uma cópia do arquivo trybe.txt com o nome trybe_backup.txt.

4. Renomeie o arquivo trybe.txt.

5. Dentro de unix_tests, crie um novo diretório chamado backup.

6.  Mova o arquivo trybe_backup.txt para o diretório backup.

7. Dentro de unix_tests, crie um novo diretório chamado backup2.

8. Mova o arquivo trybe_backup.txt da pasta backup para a pasta backup2.

9. Apague a pasta backup.

10. Renomeie a pasta backup2 para backup.

11. Veja qual é o path completo do diretório atual e liste todos os arquivos dentro dele.

12. Apague o diretório backup.

13. Limpe o terminal.

### Para os próximos exercícios, crie manualmente na parte gráfica do seu sistema operacional (com o mouse) um arquivo de texto chamado skills.txt com o conteúdo abaixo.

Internet
Unix
Bash
HTML
CSS
JavaScript
React
SQL

# Exercícios

14. Mostre na tela as 5 primeiras skills do arquivo skills.txt.

15. Mostre na tela as 4 últimas skills do arquivo skills.txt.

16. Apague todos os arquivos que terminam em .txt


##  Exercícios - Manipulação e busca

### Parte I

De olho na dica 👀: Crie um novo diretório chamado unix_tests_search e navegue até ele.

Na pasta unix_tests_search, baixe um arquivo com os nomes de todos os países do mundo utilizando o comando curl. Conheça mais sobre esse comando nesse link.

mkdir unix_tests_search
cd unix_tests_search
curl -o countries.txt ("https://gist.githubusercontent.com/kalinchernev/486393efcca01623b18d/raw/daa24c9fea66afb7d68f8d69f0c4b8eeb9406e83/countries")
Mostre todo o conteúdo do arquivo countries.txt na tela.
Mostre o conteúdo de countries.txt, página por página, até encontrar a Zambia.
Mostre novamente o conteúdo de countries.txt página por página, mas agora utilize um comando para buscar por Zambia.
Busque por Brazil no countries.txt.
Busque novamente por brazil, mas agora utilize o lower case e não considere letras maiúsculas ou minúsculas.

### Parte II

De olho na dica 👀: Crie um novo arquivo chamado phrases.txt e adicione algumas frases à sua escolha. Não é necessário criar o arquivo pelo terminal.

Busque pelas frases que não contenham a palavra fox.
Conte o número de palavras do arquivo phrases.txt.
Conte o número de linhas do arquivo phrases.txt.

### Parte III

De olho na dica 👀: Para contar o número de caracteres de um arquivo, não use wc -c, e sim wc -m.

Crie os arquivos empty.tbt e empty.pdf.
Liste todos os arquivos do diretório unix_tests_search.
Liste todos os arquivos que terminem com txt.
Liste todos os arquivos que terminem com tbt ou txt.
Acesse o manual do comando ls.

# Exercícios - Comandos de input e output

1. Crie a pasta unix_tests_skills e navegue até ela.

2. Crie um arquivo de texto pelo terminal com o nome skills2.txt e adicione os valores Internet, Unix e Bash, cada um em sua linha.

3. Adicione mais 5 itens à sua lista de skills e, depois, imprima a lista ordenada no terminal.

4. Conte o número de linhas do arquivo skills2.txt.

5. Crie um arquivo chamado top_skills.txt usando o skills2.txt. Ele deve conter as 3 primeiras skills em ordem alfabética.

6. Crie um novo arquivo chamado phrases2.txt pelo terminal e adicione algumas frases de sua escolha.

7. Conte o número de linhas que contêm as letras br.

8. Conte o número de linhas que não contêm as letras br.

9. Adicione dois nomes de países ao final do arquivo phrases2.txt.

10. Crie um novo arquivo chamado bunch_of_things.txt com os conteúdos dos arquivos phrases2.txt e countries.txt.

11. Ordene o arquivo bunch_of_things.txt.


# O despertar do terminal - Exercícios bônus

Para finalizar com alta energia, que tal aprender alguns comandos divertidos do Unix?

## Exercícios

De olho na dica 👀: Se você utiliza macOS🍎, vai precisar do gerenciador de pacotes brew instalado. Para isso, siga as orientações neste [link]

Após instalar o brew, instale o factor e o telnet.
Para instalar o factor, execute no terminal: brew install coreutils.
Para instalar o telnet, execute no terminal: brew install telnet.


1. Se você utiliza o Linux🐧, abra o terminal e execute o comando sudo apt-get install cmatrix. Para pessoas usuárias de macOS🍎, utilize brew install cmatrix no terminal. Depois, execute o comando cmatrix. Aperte ctrl+c para voltar ao terminal.

2. No sistema Linux, execute o comando sudo apt-get install fortune. No macOS🍎, execute brew install fortune. Após a instalação, crie um arquivo de texto chamado fortune.txt que contenha a sua sorte do dia. Utilize apenas uma linha de comando.

De olho na dica 👀: Use o comando fortune e o operador >.

3. Conte o número de palavras que a frase da sua sorte do dia tem.
De olho na dica 👀: Use o comando wc.

4. Execute o comando sudo apt-get install sl em um terminal Linux, ou brew install sl em um terminal macOS. Após a instalação, execute o comando sl. Agora, tente sl -f.

5. No sistema Linux, execute o comando sudo apt-get install cowsay, ou brew install cowsay no macOS. Após a instalação, execute o comando cowsay e algo que você queira falar. Agora, faça a vaquinha dizer a frase que está gravada no arquivo fortune.txt.

6. Descubra os fatores primos usando o comando factor e, em seguida, o número 42.

7. Veja como fica a sua sorte do dia ao contrário. Para isso, utilize o comando rev.

8. Execute o comando telnet towel.blinkenlights.nl e espere alguns segundos.

Observação 🔎: Gostou das curiosidades? Nos Recursos Adicionais você pode conferir mais alguns comandos divertidos!





