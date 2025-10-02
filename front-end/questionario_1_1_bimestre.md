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
Boa! 🚀 Essa é uma dúvida super comum no uso do **Git**.

---

### 🔹 Diferença entre `git pull` e `git push`:

* **`git pull`** → Serve para **atualizar o repositório local** com as alterações que estão no repositório remoto (ex.: no GitHub).

  * Ele basicamente faz dois passos:

    1. **`git fetch`** → busca as alterações do remoto.
    2. **`git merge`** → aplica essas alterações no seu código local.
  * 👉 Em resumo: **puxa código do remoto para o local**.

---

* **`git push`** → Serve para **enviar as alterações locais** (commits) para o repositório remoto.

  * Normalmente usado após `git add` + `git commit`.
  * 👉 Em resumo: **empurra código do local para o remoto**.

---

✅ Exemplo prático de fluxo:

```bash
# Você fez alterações no código local:
git add .
git commit -m "Adiciona nova funcionalidade"

# Agora envia para o repositório remoto:
git push

# Se alguém da equipe fez alterações no remoto:
git pull
```

---

👉 **Metáfora simples:**

* `git pull` = **baixar atualizações**.
* `git push` = **enviar suas atualizações**.


8.  **Git:** Explique o que é uma `branch` no **Git** e para que ela serve.
Uma **branch** no **Git** é uma **ramificação do código** que permite desenvolver funcionalidades, correções ou experimentos **de forma isolada** sem afetar o código principal (normalmente a `main` ou `master`).

---

### 🔹 Para que serve uma branch?

* **Organização:** separar o desenvolvimento de novas features, correções de bugs ou testes.
* **Trabalho em equipe:** cada desenvolvedor pode trabalhar em sua própria branch sem atrapalhar os outros.
* **Segurança:** evita mexer diretamente no código estável da aplicação.
* **Controle de versões paralelo:** várias linhas de desenvolvimento podem existir ao mesmo tempo.

---

✅ **Exemplo prático de uso:**

```bash
# Criar uma nova branch chamada "feature-login"
git branch feature-login

# Trocar para essa branch
git checkout feature-login

# Ou em um só comando (mais usado)
git checkout -b feature-login
```

Assim você pode desenvolver o **sistema de login** sem alterar o código que está rodando em produção.
Quando terminar, junta (faz o **merge**) essa branch de volta na `main`.

---

👉 Em resumo:
Uma **branch** é como uma **cópia paralela da linha do tempo do código**, usada para trabalhar em algo novo sem arriscar o que já está funcionando.


9.  **GitHub:** O que é **GitHub** e como ele se relaciona com o **Git**?
O **GitHub** é uma **plataforma online de hospedagem de repositórios Git**.
Ele funciona como uma “rede social para desenvolvedores”, permitindo armazenar projetos na nuvem e colaborar com outras pessoas de forma simples.

---

### 🔹 Como ele se relaciona com o **Git**:

* O **Git** é a **ferramenta** de controle de versão, que roda localmente no seu computador.
* O **GitHub** é um **serviço remoto** que usa o Git para guardar e sincronizar repositórios na nuvem.
* Com o GitHub, você pode **compartilhar código**, **sincronizar com sua equipe**, **fazer revisões (Pull Requests)** e até **automatizar deploys**.

---

✅ Exemplo de fluxo:

1. Você cria e versiona seu projeto com **Git** localmente.
2. Usa `git push` para **enviar** o código para o **GitHub**.
3. Outro desenvolvedor dá `git pull` para **baixar** o mesmo código do GitHub.

---

👉 Em resumo:

* **Git** = a ferramenta de controle de versão.
* **GitHub** = um serviço que usa Git para **armazenar e colaborar** em projetos na nuvem.


10. **GitHub:** Qual a importância de um `README.md` em um repositório do **GitHub**?
O arquivo **`README.md`** é considerado o **cartão de visitas** de um repositório no GitHub. Ele é escrito em **Markdown (.md)** e aparece automaticamente na página inicial do projeto.

---

### 🔹 Importância do `README.md`:

* **Apresentação do projeto** → explica o que é, para que serve e quais problemas resolve.
* **Facilita a colaboração** → fornece instruções para outros desenvolvedores contribuírem.
* **Documentação básica** → pode incluir como instalar, configurar e usar o projeto.
* **Profissionalismo** → repositórios com um bom README passam mais credibilidade.
* **Comunicação rápida** → evita que alguém precise “vasculhar o código” para entender o projeto.

---

✅ Geralmente, um bom `README.md` contém:

* Nome e descrição do projeto
* Como instalar e executar
* Tecnologias utilizadas
* Exemplos de uso
* Como contribuir
* Licença

---

👉 Em resumo:
O `README.md` é essencial porque torna o repositório **claro, acessível e colaborativo**, ajudando tanto novos usuários quanto desenvolvedores que queiram contribuir.


11. **Hospedagem:** O que é **hospedagem de projetos web**?
A **hospedagem de projetos web** é o serviço que permite disponibilizar um site, sistema ou aplicação na **internet**, para que qualquer pessoa consiga acessá-lo pelo navegador através de um endereço (URL).

---

### 🔹 Como funciona:

* O código do projeto (HTML, CSS, JS, banco de dados, APIs etc.) é armazenado em um **servidor web**.
* Esse servidor fica **online 24h**, respondendo às requisições dos usuários quando eles digitam o endereço do site.
* A hospedagem garante recursos como espaço em disco, memória, banco de dados, e suporte a linguagens de programação.

---

### 🔹 Tipos de hospedagem:

* **Hospedagem compartilhada** → vários sites no mesmo servidor (mais barata).
* **VPS (Servidor Virtual Privado)** → mais recursos e autonomia.
* **Dedicada** → servidor exclusivo para um projeto.
* **Cloud Hosting (nuvem)** → escalável, paga-se apenas pelo uso (ex.: AWS, Azure, Google Cloud).
* **Hospedagem gratuita para projetos estáticos** → ex.: GitHub Pages, Netlify, Vercel.

---

👉 Em resumo:
A **hospedagem web** é como **alugar um espaço na internet** para colocar seu projeto disponível ao público.


12. **Hospedagem:** Qual a diferença entre hospedagem **gratuita** e **paga**?
Boa pergunta! 🚀

A **diferença entre hospedagem gratuita e paga** está principalmente nos **recursos, limitações e suporte** oferecidos.

---

### 🔹 **Hospedagem Gratuita**

* 💰 **Custo:** não há cobrança.
* 🌍 **Uso comum:** projetos pessoais, portfólios, testes e aprendizado.
* ⚠️ **Limitações:**

  * Espaço em disco e tráfego reduzidos.
  * Pode exibir propagandas.
  * Domínios geralmente ficam como subdomínios (ex.: `meusite.github.io`).
  * Recursos de banco de dados e back-end restritos.
  * Pouco ou nenhum suporte técnico.

**Exemplos:** GitHub Pages, Netlify, Vercel (para sites estáticos).

---

### 🔹 **Hospedagem Paga**

* 💰 **Custo:** mensal ou anual, varia conforme o plano.
* 🌍 **Uso comum:** sites profissionais, e-commerces, sistemas em produção.
* ✅ **Vantagens:**

  * Mais espaço em disco, memória e largura de banda.
  * Suporte a múltiplas tecnologias (PHP, Python, Node.js, bancos de dados etc.).
  * Domínio personalizado (ex.: `meusite.com`).
  * Certificado SSL (https) incluído em muitos planos.
  * Suporte técnico especializado.
  * Maior segurança, estabilidade e escalabilidade.

**Exemplos:** HostGator, Locaweb, Hostinger, AWS, Google Cloud, Azure.

---

👉 **Resumo rápido:**

* **Gratuita** = ótima para começar, mas com limitações.
* **Paga** = ideal para projetos profissionais que precisam de desempenho, suporte e personalização.


13. **Hospedagem:** Cite dois exemplos de serviços de hospedagem web.
Dois exemplos de serviços de hospedagem web são:

* **GitHub Pages** → gratuito, usado principalmente para hospedar sites estáticos (HTML, CSS e JavaScript).
* **HostGator** → serviço pago, que oferece hospedagem compartilhada, VPS e dedicada para sites e sistemas.

👉 Outros exemplos bem populares são **Netlify, Vercel, Heroku, AWS (Amazon Web Services), Google Cloud** e **Azure**.


14. **HTML e CSS:** O que significa a "separação de preocupações" ao usar **HTML** e **CSS** juntos?
Boa! Essa é uma ideia central no desenvolvimento web moderno. 🚀

A **"separação de preocupações"** ao usar **HTML** e **CSS** significa dividir as responsabilidades de cada tecnologia para manter o código **mais organizado, claro e fácil de manter**:

* **HTML** → cuida da **estrutura e do conteúdo** da página (títulos, parágrafos, imagens, links, formulários etc.).
* **CSS** → cuida da **apresentação e do estilo** (cores, fontes, espaçamento, layout, responsividade etc.).

---

### 🔹 Exemplo:

```html
<!-- HTML (estrutura) -->
<h1>Bem-vindo ao meu site</h1>
<p>Este é um parágrafo de exemplo.</p>
```

```css
/* CSS (estilo) */
h1 {
  color: blue;
  font-size: 32px;
}

p {
  color: gray;
  line-height: 1.5;
}
```

👉 Se misturássemos tudo (sem CSS separado), o código ficaria **mais confuso e difícil de reutilizar**.
Com a separação, podemos **alterar o design** sem mudar o conteúdo, e vice-versa.

---

✅ **Resumindo:**
A separação de preocupações é o princípio de deixar o **HTML focado no conteúdo** e o **CSS focado no estilo**, tornando o desenvolvimento **mais limpo, reutilizável e sustentável**.


15. **Git e GitHub:** Qual a vantagem de usar o **Git** localmente para gerenciar seu projeto antes de publicá-lo no **GitHub**?
Boa questão! 🚀

Usar o **Git localmente** antes de publicar no **GitHub** traz várias vantagens:

---

### 🔹 Vantagens do Git local:

1. **Controle total do histórico** → você pode criar *commits*, voltar versões, experimentar branches sem depender da internet.
2. **Segurança** → mesmo sem conexão, seu histórico de alterações está guardado na sua máquina.
3. **Organização** → você pode trabalhar em diferentes funcionalidades separadamente (com branches) e só enviar para o GitHub quando estiver pronto.
4. **Velocidade** → operações como commit, merge e checkout são instantâneas localmente, sem precisar sincronizar com o servidor.
5. **Flexibilidade** → você decide *quando* compartilhar suas alterações com a equipe/publicar no GitHub.

---

👉 Em resumo:
O **Git local** funciona como um **laboratório pessoal**, onde você organiza e testa suas alterações com segurança.
Depois, ao usar o **GitHub**, você consegue **compartilhar e colaborar** com outros desenvolvedores, mantendo o projeto sincronizado na nuvem.

