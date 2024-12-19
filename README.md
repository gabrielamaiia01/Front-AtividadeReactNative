# Aluno(a): Gabriela Santana Maia

# Este é um aplicativo de gerenciamento de estoque criado com React Native e Expo. Ele permite adicionar, editar, excluir produtos e exibir as informações de estoque, incluindo fotos dos produtos.

## Funcionalidades

- Adicionar, editar e excluir produtos.
- Exibir uma lista de produtos com foto, nome, descrição e quantidade.
- Seleção de imagens para os produtos.
- Conexão com uma API para persistência de dados.

## Requisitos

- Node.js
- Expo CLI
- Acesso à internet (para comunicação com a API backend)

## Configurações do IP

Para que o aplicativo funcione corretamente, é necessário configurar o IP do backend no arquivo de código. Atualize a variável `url` com o endereço correto da sua API. 

Se você estiver executando a API localmente em sua máquina, o endereço será algo como `http://192.168.100.9:3030/produtos`. Certifique-se de substituir pelo **IP correto**.

1. No arquivo de código, localize a variável `url` e atualize com o IP correto:

```javascript
const url = "http://<SEU_IP>:3030/produtos"; // Substitua <SEU_IP> pelo IP da sua máquina

