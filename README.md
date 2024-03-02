# ***Hackmyvm Chapter 1: venus (1-50)***

## Missão 1: A usuária Sophia salvou sua senha em um arquivo oculto nesta pasta. Encontre-o e faça login como Sophia.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/026e9cd6-f70f-44b4-af54-350e1d004079)

***ls -a** lista todos os arquivos e diretórios, incluindo os ocultos, no diretório atual.*

*use o comando su sophia para entrar no user em seguida coloque a senha que você encontrou*

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

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/346d8fb8-5254-4667-a02f-29fabaaca721)

*Lembrando o fu e o ck não conta para a senha cebeção*

## Missão 13: A usuária Alice tem sua senha em uma variável de ambiente.

*aaaaaaaaaaa essa é facil em, use o comando 'env' e se vira kkkkk*

*env - é utilizado para exibir as variáveis de ambiente do sistema operacional.*

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/642c7dc4-756b-4823-ae29-78b72c90a7bf)

## Missão 14: O administrador deixou a senha do usuário anna como comentário no arquivo passwd.

Observação: A alice é seu admin.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/7d07e67a-c91b-4882-bf19-921188cf0964)

*/etc/passwd é um arquivo de texto que armazena informações sobre as contas de usuário, 
incluindo nomes de usuário, IDs de usuário (UID), diretórios home, entre outros.*

## Missão 15: Talvez o sudo possa ajudar você a ser natalia.

*Mais uma facil em*

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/c119c071-d0ac-45a4-9d22-796972743e28)

*sudo para iniciar um shell Bash como outro usuário.*

*-u <usuário>: Especifica o usuário com o qual o comando será executado.*

*/bin/bash é o caminho para o interpretador de comandos Bash no sistema de arquivos, 
e você pode usá-lo para iniciar um shell Bash manualmente ou especificá-lo em scripts Bash.*

## Missão 16: A senha do usuário eva está codificada no arquivo base64.txt.

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/fa6c7dcf-21f0-4575-90da-a02026659dcf)

*O nome do arquivo sugere que a senha é codificada em base64, então usamos o base64comando com a opção -d para decodificá-la.*

## Missão 17: A senha do usuário clara é encontrada em arquivo modificado em 1º de maio de 1968.

*Neste momento 99% das pessoas já querem desistir.*

![image](https://github.com/Paulo23k/Paulo3k-hackmyvm-venus-1-50/assets/143550827/d722a154-fb80-441a-a033-675d7c89e69d)

*! - é um operador que nega a condição seguinte. -newermt é uma opção do find que procura arquivos modificados após a data especificada. 
No caso, "1970-01-02" é a data de 2 de janeiro de 1970. Portanto, ! -newermt 1970-01-02 procura por arquivos que não foram modificados após 2 de janeiro de 1970.*

*-ls - Isso solicita ao find para listar informações sobre os arquivos encontrados no formato similar ao comando ls -dils.*

*e o resto é o resto....*

## Missão 18: A senha do usuário frida está no zip protegido por senha (rockyou.txt pode te ajudar).

*Agora piorou nossa situação, mas fique tranquilo eu estou aqui*

*Vamos ter que usar o KALI LINUX*

*Vou simplificar para vocês por que os metodos que tem na internet estão OFF*

*No terminal KALI-LINUX use esses comando:
scp -P 5000 clara@venus.hackmyvm.eu:/pwned/clara/protected.zip .*

*Coloque a senha da clara.*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/096aeeb1-0f67-4ff8-ab4c-f1f518a879b7)

*Use **pass123** para quebrar a senha.*

Comandos:

scp - *É frequentemente usado em situações em que é necessário transferir arquivos entre computadores de forma segura, 
especialmente em ambientes de rede onde a segurança é uma preocupação.*

unzip - 

## Missão 19: A senha de eliza é a única string que se repete (não classificada) em Repeat.txt.

*Agora molezinhaaa!!!*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/3c2f8e42-8889-407f-af29-4b1f817f2171)

uniq - *Normalmente é usado para remover ou relatar linhas duplicadas em um arquivo.*
-d - *Opção o modifica para mostrar apenas as linhas duplicadas.*

## Missão 20: A usuária Iris me deixou sua chave.

*Olha que maravilha*

*Em eliza se você usar o comando ls -a vai ter algo interessante.*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/07dddebe-d2c1-481f-b811-722729608bf8)

ssh - *É usado para iniciar uma sessão segura em um servidor remoto usando o protocolo SSH (Secure Shell). 
O SSH permite que você se conecte a um servidor de forma segura e execute comandos remotamente.*

-i .iris_key - *Aqui você está especificando qual chave privada (-i)d.iris_key.*
iris@localhost - *que termina localhost para o qual você está se conectando.*

## Missão 21: A usuária Eloise salvou sua senha de uma maneira específica.

*A senha para o próximo nível está no arquivo eloise, o arquivo eloise está codificado em base64, vamos ter que coverter para jpg*

*Vamos copiar o arquivo codificado em Base64 'eloise' e colar em um diretorio*

*Podemos acessar e copiar o arquivo eloise em cd /tmp/*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/0af70cc3-9509-4540-a06b-4cf27263256a)

*Pronto, o arquivo já está em jpg, agora vamos visualizar essa imagem com o kali linux.*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/5d67b465-1bf7-45b0-aa8f-a392a638c14f)

*Vamos atualizar o linux e instalar o firefox para vizualizar a imagem*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/d4b7b260-ccb0-4935-9863-27a8942fbc81)

*use **firefox eloise.jpg**, para visualizar a imagem.*

Missão 22: A usuária Lúcia foi criativa ao salvar sua senha.

*Lucia armazenou sua senha no arquivo hi.*

*Parece muito com um despejo hexadecimal, existe uma ferramenta de linha de comando do Linux que podemos usar para converter o dump hexadecimal de volta.*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/dea21a72-6259-4186-b7a4-89ca147baae7)

*Essa tava moleza né*

Missão 23: A usuária isabel deixou sua senha em um arquivo na pasta /etc/xdg mas não lembra o nome, porém possui dict.txt que pode ajudá-la a lembrar.

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/de7f64e5-3ebb-4817-aaa5-1987d44e2efa)

*While - que lê linhas do arquivo dict.txt e as armazena na variável line.* 

*IFS= remove quaisquer caracteres de espaço em branco iniciais e finais das linhas lidas.*

*read -r lê a entrada de forma que as barras invertidas não sejam interpretadas como escape.*

*$line é a variável que contém o nome do arquivo a ser lido em /etc/xdg/.*

Missão 24: A senha do usuário freya é a única string que não se repete em different.txt

*Mais uma molezinha...*

*Precisamos olhar o arquivo ‘diferente.txt’ e encontrar a única linha que não se repete, já utilizamos essa ferramenta de linha de comando chamada uniq.*

![image](https://github.com/Paulo23k/Paulo23k-hackmyvm-venus-1-50/assets/143550827/41296497-1ffb-438b-a2dc-525c625ee9b0)



















































