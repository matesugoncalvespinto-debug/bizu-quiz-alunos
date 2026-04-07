# Roteiro de Produção do Projeto  
**Turma:** 3º B  
**Grupo:** 3  
**Projeto:** **Bizu Quiz**

---

## Apresentação do projeto ao grupo

Grupo, a proposta de vocês é criar o **Bizu Quiz**, um site de perguntas e respostas inspirado em jogos de quiz, com até **10 questões** envolvendo as disciplinas básicas do Ensino Médio. A função do projeto é ajudar o usuário a revisar conteúdos escolares de forma mais leve, divertida e interativa.

O mais importante durante o desenvolvimento é não tentar fazer um sistema complicado logo no início. O melhor caminho é construir um projeto **simples, claro, funcional e organizado**, que possa ser produzido em sala de aula e concluído até agosto.

Vocês não precisam copiar exatamente um site já existente. A ideia é criar um quiz com identidade própria do grupo, usando como inspiração o modelo de perguntas e respostas. O foco deve ser montar algo que funcione bem: apresentar perguntas, permitir que o usuário escolha respostas e mostrar o resultado final.

Durante a construção do projeto, o grupo precisa dividir tarefas, registrar decisões, revisar o que foi feito e salvar as versões no GitHub. Isso ajuda a manter o trabalho organizado e evita perda de arquivos.

---

## 1. Análise simples da proposta do projeto

O projeto de vocês pretende criar um **site de quiz educativo**, com questões sobre disciplinas básicas do Ensino Médio, como Matemática, Português, História, Geografia, Biologia, Física, Química e outras que o grupo decidir incluir.

### O que esse projeto pretende resolver
Muitos alunos estudam por meio de texto, resumo e exercício no papel, mas nem sempre conseguem revisar o conteúdo de forma mais dinâmica. O Bizu Quiz pode ajudar a transformar a revisão em uma atividade mais interativa.

### Problema principal
O problema principal é a **dificuldade de revisar conteúdos escolares de maneira mais atrativa e organizada**.

### Objetivo geral da aplicação
O objetivo do site é **apresentar perguntas de disciplinas do Ensino Médio para ajudar na revisão e no treino de conhecimentos de forma divertida**.

### Utilidade do sistema no dia a dia
Esse sistema pode ser útil para:
- revisar conteúdos antes de provas;
- treinar conhecimentos de disciplinas básicas;
- aprender de forma mais leve;
- testar o próprio desempenho;
- incentivar o estudo por meio de desafios.

### Público-alvo
O público-alvo pode ser:
- estudantes do Ensino Médio;
- colegas da escola;
- pessoas que desejam revisar conteúdos escolares.

### Possíveis funções principais do sistema
O site pode incluir:
- página inicial com apresentação do quiz;
- botão para iniciar o jogo;
- perguntas com alternativas;
- escolha de disciplina ou modo geral;
- contagem de acertos;
- tela final com resultado;
- botão para reiniciar o quiz;
- mensagens de incentivo ao final.

---

## 2. Planejamento geral até agosto

Para que o projeto fique pronto até agosto, o trabalho precisa seguir uma sequência organizada. Como o grupo ainda está aprendendo, o ideal é desenvolver o sistema por partes, indo do mais simples ao mais completo.

Cada etapa foi pensada para ocupar **2 aulas de 50 minutos**.

### Ordem geral de construção
A ordem recomendada é esta:

1. entender a proposta do quiz;  
2. definir disciplinas, perguntas e regras;  
3. organizar requisitos;  
4. escolher tecnologias;  
5. planejar a estrutura das páginas;  
6. criar um esqueleto inicial;  
7. montar a primeira versão funcional;  
8. salvar e registrar no GitHub;  
9. revisar e melhorar;  
10. preparar a entrega final.

### Visão do desenvolvimento até agosto
A sequência pode seguir este ritmo:

**Abril:** entendimento da proposta, planejamento, regras e estrutura  
**Maio:** montagem da base do site e organização das perguntas  
**Junho:** interatividade, pontuação e primeira versão  
**Julho:** revisão, melhorias e GitHub  
**Agosto:** versão final e apresentação

---

## 3. Levantamento de requisitos

### O que são requisitos
Requisitos são as necessidades do projeto. Eles mostram o que o sistema precisa fazer e como ele deve funcionar.

### Diferença entre requisitos funcionais e não funcionais
**Requisitos funcionais** são as ações do sistema.  
Exemplo: mostrar perguntas, registrar respostas, calcular pontuação.

**Requisitos não funcionais** são características de qualidade.  
Exemplo: ter boa organização visual, ser fácil de usar, funcionar corretamente no navegador.

### Quais requisitos esse projeto provavelmente terá
Como o projeto é um quiz educativo, ele precisa apresentar perguntas, permitir escolhas, contar acertos e mostrar o resultado final de forma clara.

### Requisitos funcionais
- O sistema deve exibir uma página inicial.
- O sistema deve permitir iniciar o quiz.
- O sistema deve mostrar perguntas com alternativas.
- O sistema deve permitir que o usuário escolha uma resposta.
- O sistema deve avançar para a próxima questão.
- O sistema deve registrar a pontuação.
- O sistema deve mostrar o resultado final.
- O sistema pode separar perguntas por disciplina.
- O sistema pode permitir reiniciar o quiz.
- O sistema pode mostrar mensagens de incentivo ao final.

### Requisitos não funcionais
- O site deve ter linguagem simples.
- O quiz deve ser fácil de usar.
- O site deve funcionar em navegador comum.
- As perguntas devem estar organizadas e legíveis.
- O visual deve ser agradável e claro.
- O sistema deve responder corretamente aos cliques do usuário.
- Os arquivos devem estar organizados.
- O projeto deve ser possível de concluir até agosto.

---

## 4. Tecnologias indicadas

Para esse projeto, a melhor escolha é usar tecnologias simples e adequadas para iniciantes.

### HTML
HTML serve para criar a estrutura do site: título, perguntas, alternativas, botões e áreas de resultado.

### CSS
CSS serve para cuidar da aparência: cores, espaçamento, tamanho das caixas e estilo do quiz.

### JavaScript
JavaScript é a parte mais importante desse projeto, porque será usado para:
- mostrar perguntas;
- verificar respostas;
- contar pontos;
- mudar de questão;
- mostrar o resultado final.

### GitHub
GitHub serve para guardar o projeto, registrar o avanço do grupo e evitar perda de arquivos.

### Tecnologias recomendadas para este projeto
- HTML
- CSS
- JavaScript
- Git e GitHub
- Editor de código, como VS Code

### Alternativa simples para ambiente escolar
A melhor opção é fazer um **site estático**, com perguntas armazenadas no próprio JavaScript. Assim, vocês não precisam usar banco de dados nem programação mais avançada.

### Por que essas tecnologias são boas para esse projeto
Porque são:
- acessíveis para iniciantes;
- suficientes para montar um quiz funcional;
- simples de testar em sala de aula;
- adequadas ao prazo até agosto.

---

## 5. Estrutura da aplicação

Como o projeto é um site de quiz, ele pode ser organizado de forma simples.

### Sugestão de estrutura de pastas e arquivos

```text
bizu-quiz/
│
├── index.html
├── quiz.html
├── resultado.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── img/
│   ├── logo.png
│   └── banner.jpg
│
└── README.md
```

### Função de cada parte do sistema
- `index.html`: página inicial do projeto;
- `quiz.html`: área onde as perguntas aparecem;
- `resultado.html`: página final com pontuação;
- `css/style.css`: aparência do quiz;
- `js/script.js`: lógica das perguntas, respostas e pontuação;
- `img/`: imagens do projeto;
- `README.md`: descrição do projeto no GitHub.

### Organização básica das páginas
O sistema pode ter:
- uma tela inicial;
- uma tela de quiz;
- uma tela final de resultado.

Se o grupo quiser simplificar ainda mais, pode fazer tudo em **uma única página HTML**, mudando apenas o conteúdo com JavaScript.

---

## 6. Esqueleto inicial da aplicação

Esse esqueleto serve apenas como ponto de partida. Ele não está completo, mas ajuda o grupo a começar.

### Exemplo de `index.html`

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bizu Quiz</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

  <div class="container">
    <h1>Bizu Quiz</h1>
    <p>Teste seus conhecimentos nas disciplinas do Ensino Médio.</p>

    <div id="quiz-box">
      <h2 id="pergunta">Clique no botão para começar</h2>
      <div id="alternativas"></div>
      <button onclick="iniciarQuiz()">Iniciar Quiz</button>
      <button onclick="proximaPergunta()">Próxima</button>
      <p id="resultado"></p>
    </div>
  </div>

  <script src="js/script.js"></script>
</body>
</html>
```

### Exemplo de `css/style.css`

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f2f6ff;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  max-width: 700px;
  margin: 40px auto;
  background: white;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

h1 {
  color: #2d4fa3;
}

button {
  margin: 10px;
  padding: 10px 20px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}

.alternativa {
  display: block;
  width: 100%;
  margin: 8px 0;
  padding: 10px;
  background-color: #e8eeff;
  border-radius: 8px;
}
```

### Exemplo de `js/script.js`

```javascript
const perguntas = [
  {
    enunciado: "Qual é o resultado de 2 + 2?",
    opcoes: ["3", "4", "5", "6"],
    correta: "4"
  },
  {
    enunciado: "Quem escreveu Dom Casmurro?",
    opcoes: ["Machado de Assis", "José de Alencar", "Clarice Lispector", "Monteiro Lobato"],
    correta: "Machado de Assis"
  },
  {
    enunciado: "Qual planeta é conhecido como planeta vermelho?",
    opcoes: ["Vênus", "Marte", "Júpiter", "Saturno"],
    correta: "Marte"
  }
];

let indiceAtual = 0;
let pontuacao = 0;

function iniciarQuiz() {
  indiceAtual = 0;
  pontuacao = 0;
  mostrarPergunta();
}

function mostrarPergunta() {
  const pergunta = perguntas[indiceAtual];
  document.getElementById("pergunta").innerText = pergunta.enunciado;

  const areaAlternativas = document.getElementById("alternativas");
  areaAlternativas.innerHTML = "";

  pergunta.opcoes.forEach(opcao => {
    const botao = document.createElement("button");
    botao.className = "alternativa";
    botao.innerText = opcao;
    botao.onclick = function() {
      verificarResposta(opcao);
    };
    areaAlternativas.appendChild(botao);
  });
}

function verificarResposta(respostaEscolhida) {
  if (respostaEscolhida === perguntas[indiceAtual].correta) {
    pontuacao++;
  }
}

function proximaPergunta() {
  indiceAtual++;

  if (indiceAtual < perguntas.length) {
    mostrarPergunta();
  } else {
    document.getElementById("pergunta").innerText = "Quiz finalizado!";
    document.getElementById("alternativas").innerHTML = "";
    document.getElementById("resultado").innerText =
      "Você acertou " + pontuacao + " de " + perguntas.length + " perguntas.";
  }
}
```

### Ideias simples que podem ser adaptadas
- separar perguntas por disciplina;
- adicionar 10 questões em vez de 3;
- mostrar mensagem de erro ou acerto;
- colocar tela inicial com botão de começar;
- exibir nível de desempenho no resultado;
- permitir reiniciar o quiz.

---

## 7. Primeira versão do projeto

A primeira versão funcional não precisa estar perfeita. Ela precisa mostrar que o grupo já conseguiu transformar a ideia em um quiz real.

### O que deve existir na primeira versão funcional
- tela inicial pronta;
- pelo menos 5 perguntas funcionando;
- alternativas clicáveis;
- sistema de pontuação;
- resultado final;
- visual básico organizado.

### O que pode estar simples ou incompleto
- número menor de perguntas no começo;
- visual ainda básico;
- poucas disciplinas;
- mensagens finais simples;
- sem efeitos visuais avançados.

### O que é mais importante nessa primeira entrega
O mais importante é que:
- o usuário consiga iniciar o quiz;
- as perguntas apareçam corretamente;
- as respostas possam ser clicadas;
- a pontuação seja mostrada ao final.

### Como saber se essa versão já pode ser apresentada
A primeira versão já pode ser mostrada quando:
- o quiz inicia sem erro;
- as perguntas aparecem;
- o sistema conta acertos;
- o resultado final é exibido;
- o grupo consegue explicar como ele funciona.

---

## 8. Orientação de commit no GitHub

### O que é commit
Commit é um registro de uma mudança feita no projeto. É como salvar uma etapa do trabalho com uma mensagem explicando o que mudou.

### Por que usar GitHub
O GitHub ajuda a:
- guardar o projeto online;
- evitar perda de arquivos;
- mostrar a evolução do grupo;
- organizar o trabalho.

### Como criar um repositório
1. Entrar no GitHub.
2. Clicar em **New repository**.
3. Escolher um nome, por exemplo: `bizu-quiz`.
4. Criar o repositório.
5. Copiar o link do repositório.

### Como organizar os arquivos antes de enviar
Antes de enviar:
- conferir os nomes dos arquivos;
- deixar tudo nas pastas certas;
- remover arquivos repetidos;
- garantir que o site abre normalmente.

### Exemplo de comandos básicos

```bash
git init
git add .
git commit -m "Estrutura inicial do projeto"
git branch -M main
git remote add origin LINK_DO_REPOSITORIO
git push -u origin main
```

### Comandos para novas atualizações

```bash
git add .
git commit -m "Adiciona perguntas e sistema de pontuação"
git push
```

### Exemplos de mensagens de commit
- `Estrutura inicial do projeto`
- `Cria tela inicial do Bizu Quiz`
- `Adiciona perguntas de Matemática e Português`
- `Implementa sistema de pontuação`
- `Melhora visual do quiz com CSS`
- `Corrige erros nas perguntas`
- `Adiciona resultado final`
- `Prepara primeira versão funcional`

### O que deve ser commitado na primeira versão
- `index.html`
- `quiz.html`, se houver;
- `resultado.html`, se houver;
- `style.css`
- `script.js`
- imagens usadas;
- `README.md`

### Exemplo simples de `README.md`

```md
# Bizu Quiz

Projeto desenvolvido pelo Grupo 3 da turma 3º B.

## Objetivo
Criar um site de quiz educativo inspirado em jogos de perguntas e respostas, com até 10 questões sobre disciplinas básicas do Ensino Médio.

## Tecnologias utilizadas
- HTML
- CSS
- JavaScript

## Funcionalidades iniciais
- Tela inicial
- Perguntas com alternativas
- Sistema de pontuação
- Resultado final
```

---

## 9. Roteiro por etapas

Agora sim vem a parte prática do trabalho. Essas etapas devem ser feitas em sequência. Cada uma foi pensada para ocupar **2 aulas de 50 minutos**.

---

### Etapa 1 — Entendendo o projeto e organizando o grupo

**Objetivo da etapa**  
Compreender a proposta do Bizu Quiz e dividir responsabilidades.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão discutir a ideia do quiz, definir o foco do projeto e organizar o trabalho entre os integrantes.

**Explicação simples do conteúdo**  
Antes de programar, é preciso saber como o quiz vai funcionar e o que ele precisa ter.

**Passo a passo da execução**
1. Ler a proposta do projeto.
2. Conversar sobre como o quiz vai funcionar.
3. Definir o número inicial de perguntas.
4. Definir se haverá disciplinas separadas ou quiz geral.
5. Dividir tarefas entre os integrantes.
6. Registrar as decisões.

**O que deve ser entregue ao final da etapa**  
Um resumo com objetivo, público-alvo, quantidade de perguntas e divisão de tarefas.

**Checklist do grupo**
- [ ] O grupo entendeu a proposta  
- [ ] O formato do quiz foi definido  
- [ ] A quantidade inicial de perguntas foi escolhida  
- [ ] As tarefas foram divididas  
- [ ] As decisões foram registradas  

**Dificuldades comuns e como resolver**  
Se houver muitas ideias, escolham primeiro a versão mais simples que possa funcionar.

**Resultado esperado ao final**  
Grupo organizado e com foco claro do projeto.

---

### Etapa 2 — Escolha das disciplinas, perguntas e regras

**Objetivo da etapa**  
Definir o conteúdo do quiz.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão escolher as disciplinas, montar as perguntas e decidir as regras do jogo.

**Explicação simples do conteúdo**  
Sem perguntas organizadas, o quiz não existe. Essa etapa é a base do conteúdo.

**Passo a passo da execução**
1. Escolher as disciplinas que entrarão no projeto.
2. Escrever perguntas e alternativas.
3. Marcar qual é a resposta correta.
4. Conferir se as perguntas estão claras.
5. Organizar tudo em um documento ou tabela.

**O que deve ser entregue ao final da etapa**  
Lista inicial de perguntas com alternativas e respostas corretas.

**Checklist do grupo**
- [ ] As disciplinas foram escolhidas  
- [ ] As perguntas foram escritas  
- [ ] As alternativas foram organizadas  
- [ ] As respostas corretas foram marcadas  
- [ ] O conteúdo foi revisado  

**Dificuldades comuns e como resolver**  
Evitem perguntas confusas ou alternativas muito parecidas sem necessidade.

**Resultado esperado ao final**  
Conteúdo do quiz organizado e pronto para ser colocado no sistema.

---

### Etapa 3 — Planejamento visual das telas

**Objetivo da etapa**  
Desenhar a estrutura do site antes de programar.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão rascunhar a tela inicial, a tela do quiz e a tela de resultado.

**Explicação simples do conteúdo**  
Essa etapa ajuda a imaginar como o usuário verá o sistema.

**Passo a passo da execução**
1. Desenhar a tela inicial.
2. Desenhar a área onde a pergunta aparecerá.
3. Marcar onde ficarão as alternativas.
4. Planejar o botão de próxima questão.
5. Esboçar a tela final com pontuação.

**O que deve ser entregue ao final da etapa**  
Rascunho simples das telas do sistema.

**Checklist do grupo**
- [ ] A tela inicial foi desenhada  
- [ ] A tela do quiz foi planejada  
- [ ] A tela de resultado foi pensada  
- [ ] O visual básico foi escolhido  

**Dificuldades comuns e como resolver**  
Não tentem fazer uma arte perfeita. Façam apenas um modelo simples para guiar a construção.

**Resultado esperado ao final**  
Modelo visual pronto para orientar o desenvolvimento.

---

### Etapa 4 — Montagem da base em HTML

**Objetivo da etapa**  
Criar a estrutura inicial do site.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão criar os arquivos e montar a base do quiz no navegador.

**Explicação simples do conteúdo**  
HTML organiza o que aparece na tela.

**Passo a passo da execução**
1. Criar a pasta do projeto.
2. Criar os arquivos principais.
3. Montar a tela inicial.
4. Criar a área da pergunta e das alternativas.
5. Inserir botões e áreas de resultado.

**O que deve ser entregue ao final da etapa**  
Estrutura inicial do quiz funcionando no navegador.

**Checklist do grupo**
- [ ] Os arquivos foram criados  
- [ ] A tela inicial existe  
- [ ] A área do quiz foi montada  
- [ ] Os botões foram inseridos  

**Dificuldades comuns e como resolver**  
Se algum elemento não aparecer, revisar a organização do HTML.

**Resultado esperado ao final**  
Base do sistema pronta no navegador.

---

### Etapa 5 — Aparência do site com CSS

**Objetivo da etapa**  
Melhorar o visual do quiz.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão aplicar estilo ao projeto.

**Explicação simples do conteúdo**  
CSS deixa o quiz mais bonito e mais fácil de usar.

**Passo a passo da execução**
1. Escolher cores.
2. Ajustar fonte e espaçamento.
3. Estilizar caixa da pergunta.
4. Melhorar aparência das alternativas.
5. Ajustar botões e resultado.

**O que deve ser entregue ao final da etapa**  
Quiz com aparência organizada.

**Checklist do grupo**
- [ ] O site tem cores definidas  
- [ ] O texto está legível  
- [ ] As alternativas estão organizadas  
- [ ] O visual está melhor que a estrutura inicial  

**Dificuldades comuns e como resolver**  
Evitem exagerar nos efeitos. O mais importante é a clareza.

**Resultado esperado ao final**  
Site mais apresentável.

---

### Etapa 6 — Lógica do quiz com JavaScript

**Objetivo da etapa**  
Fazer o quiz funcionar de verdade.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão programar perguntas, respostas e pontuação.

**Explicação simples do conteúdo**  
JavaScript será usado para controlar o comportamento do quiz.

**Passo a passo da execução**
1. Criar a lista de perguntas no código.
2. Mostrar a primeira pergunta na tela.
3. Fazer o usuário clicar em uma alternativa.
4. Verificar se a resposta está correta.
5. Contar pontos.
6. Avançar para a próxima questão.

**O que deve ser entregue ao final da etapa**  
Pelo menos parte do quiz funcionando com perguntas e respostas.

**Checklist do grupo**
- [ ] O JavaScript foi conectado ao HTML  
- [ ] As perguntas aparecem na tela  
- [ ] As alternativas podem ser clicadas  
- [ ] A pontuação começa a ser contada  

**Dificuldades comuns e como resolver**  
Se algo não funcionar, revisar nomes das variáveis, funções e a ordem do código.

**Resultado esperado ao final**  
Quiz com funcionamento básico real.

---

### Etapa 7 — Primeira versão funcional

**Objetivo da etapa**  
Juntar todas as partes já desenvolvidas.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão reunir estrutura, visual e lógica em uma versão apresentável.

**Explicação simples do conteúdo**  
Primeira versão funcional é a primeira forma concreta do projeto.

**Passo a passo da execução**
1. Revisar a tela inicial.
2. Conferir se as perguntas aparecem corretamente.
3. Testar respostas e pontuação.
4. Exibir resultado final.
5. Corrigir erros visíveis.

**O que deve ser entregue ao final da etapa**  
Primeira versão do Bizu Quiz pronta para ser mostrada.

**Checklist do grupo**
- [ ] O quiz inicia corretamente  
- [ ] As perguntas aparecem  
- [ ] A pontuação funciona  
- [ ] O resultado final aparece  
- [ ] O visual está aceitável  

**Dificuldades comuns e como resolver**  
Priorizem o funcionamento antes de tentar deixar tudo bonito.

**Resultado esperado ao final**  
Primeira entrega real do projeto.

---

### Etapa 8 — Organização no GitHub

**Objetivo da etapa**  
Salvar e registrar a evolução do projeto.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão organizar os arquivos, criar o repositório e enviar a primeira versão.

**Explicação simples do conteúdo**  
GitHub serve para guardar o projeto e mostrar a evolução do trabalho.

**Passo a passo da execução**
1. Organizar os arquivos.
2. Criar ou acessar a conta no GitHub.
3. Criar o repositório.
4. Fazer o primeiro commit.
5. Enviar o projeto.

**O que deve ser entregue ao final da etapa**  
Repositório criado com a primeira versão publicada.

**Checklist do grupo**
- [ ] O repositório foi criado  
- [ ] Os arquivos foram organizados  
- [ ] O commit foi feito  
- [ ] O projeto foi enviado ao GitHub  

**Dificuldades comuns e como resolver**  
Revisar os comandos com calma e conferir se estão na pasta certa.

**Resultado esperado ao final**  
Projeto salvo online.

---

### Etapa 9 — Revisão e melhorias

**Objetivo da etapa**  
Aprimorar o quiz e corrigir problemas.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão revisar perguntas, layout e funcionamento geral.

**Explicação simples do conteúdo**  
Um quiz educativo precisa ser claro, correto e fácil de usar.

**Passo a passo da execução**
1. Revisar ortografia das perguntas.
2. Conferir respostas corretas.
3. Melhorar o visual.
4. Ajustar erros de funcionamento.
5. Pedir para outra pessoa testar.

**O que deve ser entregue ao final da etapa**  
Versão mais clara, revisada e melhorada do quiz.

**Checklist do grupo**
- [ ] As perguntas foram revisadas  
- [ ] As respostas corretas foram conferidas  
- [ ] O layout foi melhorado  
- [ ] O quiz foi testado por outra pessoa  

**Dificuldades comuns e como resolver**  
Peçam para alguém jogar o quiz e observem onde a pessoa se confunde.

**Resultado esperado ao final**  
Quiz mais confiável e mais pronto para a entrega.

---

### Etapa 10 — Testes finais e apresentação

**Objetivo da etapa**  
Preparar o projeto para a entrega final.

**O que o grupo vai fazer nessas duas aulas**  
Vocês vão testar o quiz, corrigir detalhes e organizar a apresentação.

**Explicação simples do conteúdo**  
Apresentar bem também faz parte do projeto.

**Passo a passo da execução**
1. Testar início, perguntas e resultado.
2. Conferir visual e funcionamento.
3. Revisar textos.
4. Dividir a fala da apresentação.
5. Treinar o que cada integrante vai explicar.

**O que deve ser entregue ao final da etapa**  
Versão final pronta e apresentação organizada.

**Checklist do grupo**
- [ ] O quiz está funcionando  
- [ ] O resultado final aparece corretamente  
- [ ] O grupo sabe explicar o projeto  
- [ ] A apresentação foi organizada  

**Dificuldades comuns e como resolver**  
Dividam a apresentação entre os integrantes para evitar sobrecarga.

**Resultado esperado ao final**  
Projeto pronto para entrega em agosto.

---

## Resumo geral das entregas por etapa

**Etapa 1:** definição do objetivo, formato do quiz e organização do grupo  
**Etapa 2:** escolha das disciplinas, perguntas e regras  
**Etapa 3:** rascunho das telas  
**Etapa 4:** estrutura do site em HTML  
**Etapa 5:** aparência do site em CSS  
**Etapa 6:** lógica do quiz com JavaScript  
**Etapa 7:** primeira versão funcional  
**Etapa 8:** publicação no GitHub  
**Etapa 9:** revisão e melhorias  
**Etapa 10:** testes finais e apresentação

---

## Lista final do que o grupo precisa ter pronto até agosto

- objetivo do projeto bem definido;
- formato do quiz definido;
- disciplinas escolhidas;
- perguntas e respostas organizadas;
- estrutura do site pronta;
- visual organizado;
- sistema de perguntas funcionando;
- pontuação funcionando;
- primeira versão funcional concluída;
- arquivos organizados;
- repositório no GitHub;
- README do projeto;
- versão final revisada;
- apresentação preparada.
