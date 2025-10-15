
# AutoLinker – MVP (Vite + React + Tailwind)

MVP web para conectar locadoras e motoristas de aplicativo. Inclui:
- Listagem de veículos com filtros por **modelo** e **valor semanal**
- Detalhe do veículo em modal
- Painel da locadora (ativar/desativar veículos)

## Rodando localmente

```bash
npm install
npm run dev
```
Abra http://localhost:3000 no navegador.

## Deploy na Vercel (recomendado)

```bash
npm install -g vercel
vercel login
vercel
```

A Vercel detecta Vite automaticamente. Você também pode configurar domínio próprio depois.

## Estrutura

- `src/App.tsx`: aplicação principal
- `src/main.tsx`: ponto de entrada
- `index.html`: template
- `tailwind.config.js` `postcss.config.js`: configuração do Tailwind
- `vercel.json`: diretório de saída (dist) e build command
