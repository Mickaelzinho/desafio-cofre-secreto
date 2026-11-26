# 🔓 Desafio do Cofre Secreto

Um pequeno jogo feito com **HTML, CSS e JavaScript**. O objetivo é descobrir a senha numérica de três dígitos para abrir o cofre.

## 🎮 Como jogar

1. Digite um número de 0 a 9 em cada campo.
2. Clique em **Tentar Abrir** para conferir a senha.
3. Clique em **Ver Dica** para descobrir se o primeiro número da senha é par ou ímpar.
4. Clique em **Limpar** para apagar os campos e tentar novamente.

## 🔐 Senha do jogo

A senha configurada atualmente é `6, 7, 2`.

Para alterar a senha, abra o arquivo `script.js` e edite esta linha:

```js
const senhaCofre = [6, 7, 2];
```

Use exatamente três números inteiros entre 0 e 9.

## 📁 Arquivos do projeto

- `index.html` — estrutura da página e campos do jogo.
- `style.css` — aparência e layout.
- `script.js` — lógica, validação da senha, dica e botão de limpar.

## 🚀 Como executar

1. Baixe ou clone este repositório.
2. Mantenha os três arquivos (`index.html`, `style.css` e `script.js`) na mesma pasta.
3. Abra o arquivo `index.html` no navegador.

Não é necessário instalar programas ou dependências.

## 🌐 Publicar no GitHub Pages

1. Abra **Settings → Pages** no repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save** e aguarde a publicação.
5. O GitHub mostrará o endereço público do seu jogo na mesma página.

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript

---

Projeto desenvolvido para praticar estrutura HTML, estilização CSS, variáveis, vetores, funções, condicionais e `switch/case` em JavaScript.