---

1.  **No-Code:** O que é o desenvolvimento **no-code** e qual a sua principal vantagem em relação ao desenvolvimento tradicional?
O **desenvolvimento no-code** é uma abordagem que permite criar aplicações, sites, sistemas e automações **sem precisar escrever código manualmente**, utilizando plataformas visuais com interfaces de arrastar e soltar (drag-and-drop), formulários configuráveis e blocos pré-programados.

👉 **Principal vantagem em relação ao desenvolvimento tradicional:**
Ele **acelera a criação e o lançamento de soluções digitais**, permitindo que pessoas sem conhecimento avançado em programação (como empreendedores, analistas ou equipes de negócio) possam desenvolver produtos de forma mais ágil e com menor custo, sem depender exclusivamente de desenvolvedores.

Em resumo: **No-code = mais acessibilidade + mais velocidade**, enquanto o desenvolvimento tradicional dá mais **flexibilidade e controle total** sobre o código.


2.  **Linguagem de Programação:** Cite uma linguagem de programação de back-end comumente utilizada em conjunto com **HTML**, **CSS** e **JavaScript** para criar aplicações web completas.
Uma linguagem de programação de **back-end** muito utilizada em conjunto com **HTML, CSS e JavaScript** é o **Python** (geralmente com frameworks como **Django** ou **Flask**).

Ele é bastante usado porque:

* É fácil de aprender e escrever.
* Possui muitos frameworks que aceleram o desenvolvimento.
* Integra bem com bancos de dados e APIs.

👉 Outras opções comuns: **Node.js (JavaScript no back-end)**, **PHP**, **Java** e **C#**.

3.  **HTML:** Qual o principal objetivo do **HTML**? Qual a diferença entre uma tag `<h1>` e `<h6>`?
O **HTML (HyperText Markup Language)** tem como principal objetivo **estruturar o conteúdo de uma página web**, organizando textos, imagens, links, tabelas, vídeos e outros elementos para que os navegadores consigam exibi-los de forma correta.

🔹 **Diferença entre `<h1>` e `<h6>`:**

* As tags `<h1>` a `<h6>` representam **títulos e subtítulos hierárquicos**.
* `<h1>` é o título mais importante da página (geralmente usado apenas uma vez para indicar o assunto principal).
* `<h6>` é o nível mais baixo de título, usado para subtítulos de menor relevância.

👉 Em resumo: `<h1>` = título principal (maior destaque), `<h6>` = título de menor importância (menor destaque).

4.  **CSS:** Como o **CSS** contribui para o desenvolvimento web? Qual a função da propriedade `margin`?
O **CSS (Cascading Style Sheets)** é responsável por **definir a aparência e o estilo** de uma página web. Ele complementa o HTML, que estrutura o conteúdo, permitindo controlar cores, fontes, espaçamento, alinhamento, tamanhos, posicionamento de elementos e até animações.

🔹 **Contribuições principais do CSS para o desenvolvimento web:**

* Separa a **estrutura (HTML)** da **apresentação (design)**.
* Proporciona **consistência visual** em várias páginas.
* Facilita a **responsividade** (adaptação a diferentes telas: celular, tablet, desktop).
* Melhora a **experiência do usuário** ao tornar o site mais agradável e intuitivo.

🔹 **Função da propriedade `margin`:**
A propriedade `margin` define o **espaçamento externo** de um elemento, ou seja, a distância entre o elemento e os outros ao seu redor.

Exemplo:

```css
div {
  margin: 20px; /* adiciona 20px de espaço em todos os lados do elemento */
}
```

👉 Se `padding` é o **espaço interno** (entre o conteúdo e a borda), `margin` é o **espaço externo** (entre a borda e os elementos vizinhos).


5.  **JavaScript:** Qual a função do **JavaScript** em uma página web? Qual a diferença entre `let`, `const` e `var`?
O **JavaScript (JS)** é a linguagem de programação que dá **dinamismo e interatividade** às páginas web.
Enquanto o **HTML** estrutura o conteúdo e o **CSS** cuida do estilo, o **JavaScript** permite:

* Manipular elementos do HTML (ex.: esconder/mostrar conteúdos, alterar textos e estilos).
* Criar interações com o usuário (cliques, formulários, animações).
* Trabalhar com dados (armazenar, validar, buscar em APIs).
* Construir aplicações web completas no front-end e também no back-end (com Node.js).

---

### 🔹 Diferença entre `var`, `let` e `const`:

Esses três são usados para declarar variáveis, mas têm diferenças importantes:

1. **`var`**

   * Escopo: **global** ou **de função** (não respeita bloco `{ }`).
   * Pode ser **redefinida** e **reatribuída**.
   * É a forma **antiga** de declarar variáveis (menos recomendada hoje).

2. **`let`**

   * Escopo: **de bloco** (respeita `{ }`).
   * Pode ser **reatribuída**, mas não **redefinida no mesmo escopo**.
   * Mais seguro que `var`.

3. **`const`**

   * Escopo: **de bloco** (igual ao `let`).
   * **Não pode ser reatribuída** (valor fixo).
   * Boa prática: usar `const` sempre que o valor não precisar mudar.

---

✅ **Exemplo prático:**

```javascript
var x = 10;
var x = 20; // permitido (redeclaração)

let y = 30;
// let y = 40; // ❌ erro (não pode redeclarar no mesmo escopo)
y = 40; // ✔ pode reatribuir

const z = 50;
// z = 60; // ❌ erro (não pode reatribuir)
```

👉 Resumindo:

* Use `var` raramente (por compatibilidade).
* Use `let` quando o valor pode mudar.
* Use `const` quando o valor for fixo.


6.  **Git:** O que é **Git** e qual a sua principal finalidade no desenvolvimento de software?
O **Git** é um **sistema de controle de versão distribuído** usado no desenvolvimento de software.

👉 **Principal finalidade:**
Permitir que desenvolvedores **controlem o histórico de alterações do código**, colaborem em equipe e gerenciem diferentes versões de um projeto de forma segura e organizada.

---

### 🔹 Benefícios principais do Git:

* **Histórico completo**: registra quem fez cada alteração, quando e por quê.
* **Trabalho em equipe**: vários desenvolvedores podem trabalhar no mesmo projeto sem sobrescrever o código uns dos outros.
* **Branches (ramificações)**: permite criar linhas de desenvolvimento independentes (ex.: nova funcionalidade, correção de bug) sem afetar o código principal.
* **Reversão**: é possível voltar a versões anteriores do código, se necessário.
* **Integração com plataformas**: como GitHub, GitLab e Bitbucket, que facilitam colaboração remota e revisão de código.

---

✅ Em resumo:
O **Git** é como uma “linha do tempo” do código que ajuda equipes a **trabalhar juntas, evitar perdas de progresso e manter o projeto organizado**.


7.  **Git:** Qual a diferença entre os comandos `git pull` e `git push`?

8.  **Git:** Explique o que é uma `branch` no **Git** e para que ela serve.

9.  **GitHub:** O que é **GitHub** e como ele se relaciona com o **Git**?

10. **GitHub:** Qual a importância de um `README.md` em um repositório do **GitHub**?

11. **Hospedagem:** O que é **hospedagem de projetos web**?

12. **Hospedagem:** Qual a diferença entre hospedagem **gratuita** e **paga**?

13. **Hospedagem:** Cite dois exemplos de serviços de hospedagem web.

14. **HTML e CSS:** O que significa a "separação de preocupações" ao usar **HTML** e **CSS** juntos?

15. **Git e GitHub:** Qual a vantagem de usar o **Git** localmente para gerenciar seu projeto antes de publicá-lo no **GitHub**?
