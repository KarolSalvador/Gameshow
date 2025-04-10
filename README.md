# Game Show - Jogo de Perguntas e Respostas

Este é um jogo simples de perguntas e respostas, onde os jogadores podem testar seus conhecimentos em diversas áreas. As perguntas são exibidas uma de cada vez e o jogador escolhe uma resposta. Ao final, é mostrado o número de acertos.

## Funcionalidades

- Exibição de perguntas e opções de respostas.
- Controle de progresso do jogo (quantas perguntas foram respondidas).
- Contagem de acertos.
- Exibição de resultado final após todas as perguntas serem respondidas.

## Tecnologias Utilizadas

- **HTML** para estruturação da página.
- **CSS** para estilização.
- **JavaScript** para a lógica do jogo.

## Estrutura do Código

### Parte 1: Lista de Perguntas e Respostas

As perguntas e respostas estão organizadas em um array de objetos, onde cada objeto contém uma pergunta e um array de respostas possíveis. A resposta correta é indicada pela propriedade `correto: true`.

### Parte 2: Manipulação do DOM

Utilizamos `document.querySelector` para acessar os elementos HTML onde as perguntas, respostas e o progresso são exibidos. Também criamos botões dinamicamente para cada resposta.

### Parte 3: Controle do Jogo

O índice da pergunta atual é controlado pela variável `indiceAtual`, e o número de acertos é contado com a variável `acertos`. Quando uma resposta é clicada, o jogo avança para a próxima pergunta ou exibe o resultado final.

### Parte 4: Funções

- **carregarPergunta()**: Responsável por exibir a pergunta atual e as opções de resposta.
- **finalizarJogo()**: Exibe a tela final com o número de acertos do jogador.

## Como Rodar o Projeto

1. Clone este repositório para seu computador:

    ```bash
    git clone https://github.com/seuusuario/game-show.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd game-show
    ```

3. Abra o arquivo `index.html` em seu navegador.

## Link para o Jogo

Você pode jogar diretamente na web através deste [link](https://gameshow-ten.vercel.app/)

## Próximos Passos

- Adicionar mais perguntas e categorias ao jogo.
- Melhorar a interface com mais animações e feedback visual.
- Implementar pontuação bônus ou tempo limitado para cada resposta.

## Contato

Se você tiver dúvidas ou sugestões, entre em contato comigo!

- [LinkedIn](https://www.linkedin.com/in/karolsalvador/)

---

**#game #quiz #javascript #webdevelopment #project #html #css #javascriptgame #vercel**
