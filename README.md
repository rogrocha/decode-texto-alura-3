# Alura Text Decoder Challenge

## Descrição

O **Alura Text Decoder Challenge** é um projeto desenvolvido como parte dos desafios propostos pela plataforma de aprendizagem Alura. O objetivo deste projeto é criar um decodificador de texto capaz de criptografar e descriptografar mensagens usando algoritmos de cifra simples.

## Algoritimo

- **Initializacao**:
  
  Um dicionário de regras de substituição (`chaves`) é inicializado, onde cada vogal é mapeada para uma string única:
  - 'a' → 'ai'
  - 'e' → 'enter'
  - 'i' → 'imes'
  - 'o' → 'ober'
  - 'u' → 'ufat'
 
- **Substituição**:
  
Cada caractere no texto de entrada é substituído de acordo com as regras de substituição no dicionário `keys`.
Para cada caractere no texto de entrada:

- Se o caractere for uma chave no dicionário `keys`, ele será substituído pelo valor correspondente.
- Se o caractere não for uma chave, ele permanecerá inalterado.


## Caracteristicas
- **Validação**: Garante que o texto de entrada consiste apenas em letras minúsculas e espaços.
- **Interface Simples**: Interface amigável para interagir com o decodificador.
- **Rolagem Automática**: Rola automaticamente para áreas de entrada ou saída para melhor experiência do usuário.
- **Suporte para Área de Transferência**: Permite copiar o texto criptografado ou descriptografado para a área de transferência.

## Como usar
1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/rogrocha/decode-texto-alura
    ```
2. Navigate to the project directory:
    ```sh
    
    ```
3. Open the `index.html` file in your web browser to run the application.




