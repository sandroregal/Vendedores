# Copiloto Comercial SP — Royal FIC (casca/PWA)

App instalável (PWA) que orienta a equipe comercial SP em quatro frentes:
**Conquista** (espaço em branco ANP), **Retomada** (carteira em risco por recência/ciclo),
**Cross-sell** (cesta incompleta por segmento) e **Pacing**.

> **Privacidade:** este repositório **não contém nenhum dado da Royal nem nomes**.
> A base histórica é carregada **uma única vez no próprio aparelho** (arquivo
> `historico_SP.json`, entregue à parte) e fica guardada só no celular (IndexedDB).
> O YVIEWCOPA do dia também é lido **no aparelho** — nada sobe para a internet.

## Arquivos do repositório
- `index.html` — app (interface + motor de cálculo + mapa). Sem dados.
- `manifest.webmanifest`, `sw.js` — PWA (instalação + cache do shell).
- `icon-192.png`, `icon-512.png`, `icon-maskable.png` — ícones (logo oficial em selo branco).
- `.nojekyll` — necessário no GitHub Pages.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `copiloto-sp`).
2. Envie **todos os arquivos desta pasta** para a **raiz** do repositório.
3. **Settings → Pages → Branch: `main` / `/ (root)` → Save**.
4. Aguarde ~1 min. O endereço será `https://SEU-USUARIO.github.io/copiloto-sp/`.

## Usar no celular (1ª vez)
1. Abra o endereço no **Chrome**.
2. Menu **⋮ → Adicionar à tela inicial / Instalar app**.
3. Abra o app pelo ícone. Ele pedirá a **base histórica**:
   toque em **Carregar base histórica** e selecione o **`historico_SP.json`**.
   (fica salvo no aparelho; só precisa fazer isso uma vez)

## Dia a dia
- Toque em **⟳** (canto superior) e selecione o **YVIEWCOPA.CSV** do dia.
- O app recalcula tudo no aparelho e guarda o resultado (abre offline depois).
- A referência ("hoje") é sempre a **última data do YVIEWCOPA** carregado.

## Atualizar a base histórica (eventual)
Quando houver novos meses fechados, gera-se um novo `historico_SP.json`.
No app, é só carregá-lo de novo (substitui a base no aparelho).
