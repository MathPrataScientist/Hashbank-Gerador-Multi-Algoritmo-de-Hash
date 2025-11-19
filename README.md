# Hashbank-Gerador-Multi-Algoritmo-de-Hash
O Hashbank é um script Python simples e interativo projetado para gerar hashes criptográficos de diferentes tipos a partir de uma entrada fornecida pelo usuário. Ele oferece uma seleção de algoritmos de hash populares e modernos para diversas finalidades, como integridade de dados, segurança em blockchain e proteção de senhas. 
# Funcionalidades
O script permite escolher entre os seguintes algoritmos de hash:

1: SHA-256: Amplamente usado em segurança e tecnologia Blockchain (ex: Bitcoin), excelente para verificação de integridade de arquivos.

2: SHA-3 (Keccak): Uma evolução mais recente e padronizada da família SHA.

3: BLAKE3: Conhecido por ser um algoritmo moderno, seguro e extremamente rápido.

4: SHA512: Um algoritmo de hash de 512 bits que oferece um alto nível de força criptográfica.

5: Argon2: Altamente recomendado para o armazenamento seguro de senhas, devido à sua resistência contra ataques de força bruta e dicionário.

# Pré-requisitos
Para executar o Hashcript, você precisará ter o Python instalado e as seguintes bibliotecas Python:

blake3

argon2-cffi

Instalação das dependências
Você pode instalar as bibliotecas necessárias usando o pip:

Bash

pip install blake3 argon2-cffi

# Como Usar
Salve o código em um arquivo Python (ex: hashcript.py).

Execute o script no terminal:

Bash

python hashcript.py
O script exibirá um menu com as opções de algoritmos de hash.

Digite o número da opção desejada (1 a 5) e pressione Enter.

Digite a mensagem/senha que você deseja hashear quando solicitado.

O hash gerado será exibido na tela.

# Tecnologias Utilizadas
Python 3.x

Biblioteca padrão hashlib (para SHA-256, SHA-3, SHA512)

Biblioteca blake3

Biblioteca argon2-cffi (para Argon2)

# Observações
O script utiliza o argon2 para o hash de senhas (Opção 5), pois é o algoritmo vencedor da Password Hashing Competition e é projetado especificamente para ser resistente a ataques. Para as outras opções, ele usa algoritmos de hash criptográfico que são ideais para verificação de integridade e outras aplicações não relacionadas a senhas.
