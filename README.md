# ***Hackmyvm Chapter 1: venus (1-50)***

## Missão 1: A usuária Sophia salvou sua senha em um arquivo oculto nesta pasta. Encontre-o e faça login como Sophia.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/026e9cd6-f70f-44b4-af54-350e1d004079)

***ls -a** lista todos os arquivos e diretórios, incluindo os ocultos, no diretório atual.*

*Observação: Depois que colocar a senha de um user faça isso...*

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/9c95ce13-da10-4589-9d6d-81efcbf3946a)

## Missão 2: A usuária angela salvou sua senha em um arquivo mas não lembra onde… ela só lembra que o arquivo se chamava whereismypazz.txt

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/d3631999-8403-43e1-a749-e72244406467)

***find** é muito flexível e pode ser combinado com várias opções para realizar buscas complexas em uma árvore de diretórios.*

## Missão 3: A senha do usuário emma está na linha 4069 do arquivo findme.txt

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/d3940b1a-9e38-4290-9847-b46be18fcb2d)

***sed -n** '..' arquivo.txt: Isso imprimirá apenas a primeira linha do arquivo.*

## Missão 4: A usuária mia deixou sua senha no arquivo - 

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/2e2476f3-b299-417e-8306-07b6d126745a)

*Simplesmente dizemos ao cat para procurar o arquivo no diretório atual. Podemos fazer isso prefixando o nome do arquivo com a string **'./'***

## Missão 5: Parece que a usuária camila deixou sua senha dentro de uma pasta chamada hereiam.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/e58f0d9a-41ef-4661-be31-07acbf5fa29a)

*Agora como você pode ver usamos os comando da missão 2 + missão 1*

## Missão 6: A usuária luna deixou sua senha em um arquivo dentro da pasta muack.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/4a048ec2-289f-46af-94c6-55975b2e1385)

*Quando você executa find **-type f** em um diretório, o comando irá percorrer recursivamente todos os subdiretórios desse diretório
e listar todos os arquivos regulares que encontrar, exibindo seus caminhos completos.*

## Missão 7: A usuária Eleanor deixou sua senha em um arquivo que ocupa 6.969 bytes.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/34b8fa8c-1bef-48f5-b2b3-70afd0b3e2a9)

***-size** no comando find é usado para localizar arquivos com um determinado tamanho.*
Você pode especificar o tamanho dos arquivos que deseja encontrar com diferentes unidades de medida, como kilobytes (k), megabytes (M), gigabytes (G), etc.

## Missão 8: A usuária Victoria deixou sua senha em um arquivo cujo dono é o usuário violino.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/e8f785ac-0403-4583-be04-1df8d3194c02)

***-user** no comando find é usado para localizar arquivos pertencentes a um usuário específico.
Você pode usá-lo para encontrar arquivos que são propriedade de um determinado usuário.*

## Missão 9: A usuária isla deixou sua senha em um arquivo zip.

*Para descompactar um arquivo zip, precisamos ter permissões de gravação para o destino. 
Como não temos permissões de gravação no diretório inicial atual, criamos uma pasta temporária dentro da pasta '/tmp'.*

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/1ffcc148-8c07-4035-8b2a-a3cc6364242c)

*Comandos:*

*mkdir - é usado para criar um novo diretório*

*unzip - é uma ferramenta de linha de comando que é usada para descompactar arquivos no formato ZIP*

## Missão 10: A senha do usuário violeta está na linha que começa com a9HFX (esses 5 caracteres não fazem parte da senha dela.).

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/d9aec4f5-4a1a-4a3e-924e-507b62e78df1)

*Comandos:*

*grep - é usado para pesquisar padrões em texto. Ele está procurando por linhas que começam com "a9HFX" no conteúdo do arquivo "passy".*

*^ - representa o início de uma linha.*

| *Este é o operador de pipe, que redireciona a saída do comando anterior*

## Missão 11: A senha da usuária lucy está na linha que termina com 0JuAZ (esses últimos 5 caracteres não fazem parte da senha dela)

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/f6e2f449-0f5a-4615-81d1-c0b8f091f583)

*cat end | grep 0JuAZ$ irá exibir todas as linhas do arquivo "end" que terminam exatamente com "0JuAZ".*

*$ - é um caractere especial que representa o final de uma linha.*

## Missão 12: A senha da usuária elena está entre os caracteres fu e ck

*Passo 1: A string que comece com 'fu', a expressão para isso é ^fu*

*Passo 2: Agora vem qualquer número de caracteres, a expressão para isso é* .*

*Passo 3: A string deve terminar com 'ck' então a expressão para isso é ck$*



















