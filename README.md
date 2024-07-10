# Projeto Busca Cep
Este é um projeto que desenvolvi junto com o curso de programação orientada a objeto em java, da Escola de programação da alura
## Índice

1. [Pré-requisitos](#pré-requisitos)
2. [Licença](#licença)
3. [Como usar](#uso)
4. [Contato](#contato)

## Pré-requisitos
- JDK 17
- InteliJ
- Gson
- Postman 

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/MarcosLucasVieira/ProjetoViaCep.git
    ```
2. Link para a intalação do Gson:
 ```
https://mvnrepository.com/artifact/com.google.code.gson/gson
o link irá baixar um arquivo .jar, vc precisa adcionar ele aos seus "Project Structure" (via intellij)
clique em Modules
depois clique em + e vá até o diretorio onde baixou o Gson.
Após isto é só clickar em "OK"
```
3 . Link para o dowloading do PostMan:
https://www.postman.com/downloads/

4. Link para o Dowloading do IntelliJ:
https://www.jetbrains.com/idea/download/?section=windows

## Uso 
O programa é bem dinâmico para o uso, assim que instalar tudo no terminal ira pedir para que digite o numero do Cep que deseja buscar, e ele irá retorna no terminal o numero e também irá criar um arquivo Json em sua pasta já com SettPrettyPrinting para melhor entendimento do usuário, a API pode ser gerada diversas vezes assim podendo fazer consulta e enquanto armazena as irformações em arquivo.json. 

As Excepition foram tratadas com a Class Excepition, e trazendo um retorno que o cep não foi possivel ser encontrado, caso tenha erro de digitação, ou para testes mesmo. 

## Licença

Este projeto está licenciado sob a MIT License.

### Contato
Email: marcosVieira23dev@gmail.com    
LinkedIn: (https://www.linkedin.com/in/marcos-lucas-vieira-a1b61b200/)
