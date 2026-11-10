# ATOPAV Engenharia

Site em React 19, React Router, Vite 8 e Tailwind CSS v4.

## Executar localmente

Use Node.js 22 e pnpm 10.34.3, conforme `.mise.toml`.

```powershell
mise install
pnpm install --frozen-lockfile
pnpm dev
```

O Vite informa o endereço local no terminal. Para validar a compilação:

```powershell
pnpm run build
pnpm preview
```

## Rotas e SEO

As rotas ficam em `src/routes.tsx`; os metadados de páginas institucionais usam `src/hooks/usePageMetadata.ts`. Os URLs publicados e aliases preservados estão em `SITE_MAP.md`. A hospedagem de produção precisa encaminhar rotas da SPA para `index.html` e entregar 404 para caminhos inexistentes.

## Revisão antes de publicar

Consulte `PENDENCIAS_REVISAO.md`. O Google Analytics só carrega após consentimento explícito. O formulário não envia dados a um servidor e não confirma leads; prepara uma mensagem do WhatsApp que o visitante ainda precisa enviar.