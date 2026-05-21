# 🗓️ Meu Dashboard Pessoal

> Projeto desenvolvido durante o **Sprint IA da PrograMaria**, com o objetivo de construir algo do zero usando Inteligência Artificial como co-piloto — o chamado **Vibe Coding**.

---

## 💡 Sobre o Projeto

Este é um dashboard pessoal de produtividade com visual **pixel art / 16-bit**, feito inteiramente com HTML, CSS e JavaScript puros — sem frameworks, sem bibliotecas complexas, só a web mesmo.

A ideia nasceu dentro do programa **Sprint IA da [PrograMaria](https://www.programaria.org/)**, uma iniciativa que incentiva mulheres a criarem projetos reais usando IA como ferramenta de apoio no desenvolvimento. O projeto foi iniciado no **Antigravity** e evoluído com o auxílio do **Claude (Anthropic)** como co-piloto de código.

### O que é Vibe Coding?

Vibe Coding é uma forma de desenvolver software onde você descreve o que quer em linguagem natural para uma IA, e ela te ajuda a escrever, corrigir e evoluir o código. Você não precisa saber tudo de programação — você precisa saber o que quer construir e aprender junto com a ferramenta.

> Este projeto é prova de que **qualquer pessoa pode criar algo funcional e bonito**, mesmo começando do zero.

---

## ✨ Funcionalidades

- **Login com Google** — autentica com sua conta e puxa seus dados reais
- **Modo Demo** — testa o dashboard sem precisar de conta Google
- **Agenda integrada** — visualiza e cria eventos, com sincronização opcional ao Google Calendar
- **E-mails não lidos** — contador conectado ao Gmail via API
- **Horas de estudo** — calculadas automaticamente pelos eventos do calendário
- **Pomodoro Timer** — timer de foco de 25 minutos com controles de start/pause/reset
- **Kanban pessoal** — lista de tarefas com checkboxes, edição e exclusão
- **Assuntos da Semana** — notícias de tecnologia buscadas em tempo real via IA
- **Dev Tip do Dia** — dicas técnicas que rodam direto no dashboard
- **Tech Inspirations** — frases de mulheres e ícones da tecnologia com rotação automática
- **Múltiplos temas** — 6 paletas de cores para personalizar o visual
- **Persistência de dados** — tudo salvo no navegador, nada se perde ao fechar a aba
- **Relógio internacional** — exibe o horário em diferentes fusos

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Para que serve |
|---|---|
| **HTML5** | Estrutura das páginas e componentes |
| **CSS3** | Visual pixel art, temas de cores, responsividade |
| **JavaScript** | Toda a lógica do dashboard, interações e dados |
| **Google OAuth 2.0** | Login seguro com conta Google |
| **Gmail API** | Leitura de e-mails não lidos |
| **Google Calendar API** | Leitura e criação de eventos |
| **Anthropic API (Claude)** | Busca de notícias tech em tempo real |
| **Chart.js** | Gráfico de fluxo de e-mails |
| **LocalStorage** | Salvar dados do usuário no navegador |
| **Git & GitHub** | Versionamento e hospedagem do código |

---

## 🚀 Como Rodar Localmente

### Pré-requisitos

Você só precisa de:
- Um navegador (Chrome, Firefox, Edge...)
- Um editor de código (recomendado: [VS Code](https://code.visualstudio.com/))

### Passo a passo

**1. Clone o repositório**
```bash
git clone https://github.com/seu-usuario/meu-dashboard.git
```

**2. Acesse a pasta**
```bash
cd meu-dashboard
```

**3. Crie o arquivo de configuração**

Crie um arquivo chamado `config.js` na raiz do projeto com o seguinte conteúdo:
```js
const CONFIG = {
  GOOGLE_CLIENT_ID: "SEU_CLIENT_ID_AQUI.apps.googleusercontent.com",
  GOOGLE_API_KEY:   "SUA_API_KEY_AQUI",
};
```

> ⚠️ Sem esse arquivo, o login com Google não vai funcionar. Mas você ainda pode usar o **Modo Demo** normalmente!

**4. Abra o projeto**

Basta abrir o arquivo `index.html` no navegador. Sem servidor, sem instalação.

---

## 🔑 Configurando as Credenciais do Google (opcional)

Para usar o login com Google, Gmail e Calendar, você precisa criar credenciais no Google Cloud Console:

1. Acesse [console.cloud.google.com](https://console.cloud.google.com/)
2. Crie um novo projeto
3. Ative as APIs: **Gmail API** e **Google Calendar API**
4. Em "Credenciais", crie um **OAuth 2.0 Client ID** (tipo: Aplicativo Web)
5. Crie também uma **API Key**
6. Cole os valores no seu `config.js`

---

## 🔒 Segurança

O arquivo `config.js` contém informações sensíveis (suas chaves de API) e está listado no `.gitignore` — ou seja, **nunca será enviado ao GitHub**. Cada pessoa que clonar o projeto precisa criar o próprio `config.js` com suas credenciais.

---

## 👩‍💻 Sobre o Desenvolvimento

Este projeto foi desenvolvido com o apoio de **Inteligência Artificial como co-piloto**:

- **[Antigravity](https://antigravity.dev/)** — onde o projeto foi iniciado
- **[Claude (Anthropic)](https://claude.ai/)** — auxiliou na evolução do código, correção de bugs, integração com APIs e boas práticas

A experiência mostrou que IA não substitui o aprendizado — ela **acelera** e **democratiza** o acesso ao desenvolvimento de software.

---

## 🌸 PrograMaria

A **[PrograMaria](https://www.programaria.org/)** é uma organização que acredita que a diversidade transforma a tecnologia. O Sprint IA é um dos seus programas que incentiva mulheres a aprenderem tecnologia na prática, construindo projetos reais.

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais e pessoais.

---

Feito com 💜 e muito Vibe Coding.
