# Convite de 15 anos da Driellen

Versão preparada para publicação na Vercel usando Vite. A arte original fica em `public/convite.png` e é servida sem alterações.

## Estrutura necessária

```text
convite-driellen/
├── index.html
├── package.json
├── vercel.json
├── .gitignore
└── public/
    └── convite.png
```

## Testar no computador

Instale o Node.js 22 e, dentro desta pasta, execute:

```bash
npm install
npm run dev
```

Para testar o build de produção:

```bash
npm run build
npm run preview
```

O build deve criar a pasta `dist/`.

## Publicar na Vercel

Envie todos os arquivos desta pasta para a raiz do repositório GitHub. No painel da Vercel, verifique:

- **Root Directory:** a pasta que contém `package.json` (normalmente `.` / raiz do repositório).
- **Framework Preset:** Vite.
- **Install Command:** `npm install`.
- **Build Command:** `npm run build`.
- **Output Directory:** `dist`.

O arquivo `vercel.json` já define os comandos de instalação, build e a pasta de saída. Caso o painel da Vercel esteja com opções sobrescritas, use os mesmos valores acima ou remova as sobrescritas para que a configuração do projeto seja aplicada.

Se o repositório antigo tiver um `vite.config.js`, `vite.config.ts` ou configurações React antigas que importem plugins que não estão neste projeto, remova esses arquivos antigos ao substituir o site pelo projeto deste pacote. Eles não são necessários para este convite estático.

## WhatsApp

O botão de confirmação abre o WhatsApp para `+55 14 99144-0905` com a mensagem `Eu confirmo a minha presença para o seu aniversário!!!`.
