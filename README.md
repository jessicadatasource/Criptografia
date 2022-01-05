# Criptografia
Projeto de Criptografia de senha com automação.

O script tem como funcionalidades:
> Criptografa a informação contida no arquivo raiz do projeto "minhaSenha.txt" e grava em um outro arquivo "encryptPWD.txt"
> Gera uma chave e grava em um outro arquivo "refkey.txt"

Agora é possível excluir o arquivo "minhaSenha.txt" com a senha e trabalhar
ou compartilhar o projeto somente com o arquivo criptografado, em uma comunicação mais segura.

Descriptografia
> Ler a minhaSenha criptografada e armazena em 2 variáveis  (usuário e senha)


Preparação ao ambiente virtual Python
> python
> pip install jupyter notebook (IDE)

Bibliotecas:
> pip install cryptography (Protegendo suas chaves de API)


Automação:
O projeto tem uma pequena automação para startar o jupyter notebook. Basta clicar no arquivo "Clique aqui" que o programa inicializa.

Obs: Para iniciar o projeto pela automação é necessário setar o caminho da pasta dentro do arquivo "activate_jn.bat" "clique aqui"e nos campos abaixo:

==============================
*o aquivo (activate_jn.bat) está dentro da pasta: api_dados\Scripts

------------------------------
set VIRTUAL_ENV=C:\Criptografia\api_dados\Scripts
.
.
.
cd "C:\Criptografia\api_dados"

==============================
