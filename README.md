# Dog Evolution

Site institucional responsivo da Dog Evolution, com a identidade verde e turquesa da marca, fotos, quatro serviços, perguntas frequentes, localização e contato pelo WhatsApp.

## Desenvolvimento local

Sem dependências ou compilação. Na pasta do projeto:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Abra http://127.0.0.1:4173.

## Publicar na Vercel

Importe este repositório, selecione o framework **Other**, mantenha o diretório raiz em `./` e publique. O arquivo `vercel.json` configura o conteúdo estático na raiz; não é necessário comando de build nem variáveis de ambiente.

## Estrutura

- `index.html`: conteúdo e acessibilidade.
- `style.css`: estilos de base.
- `welcome.css`: identidade clara e adaptações responsivas.
- `app.js`: menu, detalhes dos serviços, formulário e decoração em Canvas.
- `assets/`: logo e fotografias.

O formulário prepara uma mensagem no WhatsApp. O visitante confere e envia no próprio WhatsApp; o site não armazena os dados do formulário.

Conteúdo comercial e fotografias baseados no site oficial https://www.dogevolutionbc.com.br/. As fontes Manrope e DM Sans são carregadas pelo Google Fonts, com alternativas locais.
