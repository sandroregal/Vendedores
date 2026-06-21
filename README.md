# Copiloto Comercial SP — Royal FIC (modelo seguro: casca + dados)

Este pacote é a **CASCA** do app: só interface, lógica e o mapa de SP.
**NÃO contém nenhum dado da Royal.** Pode ir para um repositório público sem risco.

Os números (Conquista e Retomada) ficam num arquivo separado — **copiloto_dados.json** —
que mora **apenas no seu aparelho** e é carregado pelo botão ⟳ dentro do app.

============================================================
REGRA DE OURO DE SEGURANÇA
============================================================
- No GitHub vai SÓ esta casca (sem dados).
- O arquivo `copiloto_dados.json` NUNCA entra no repositório.
  Ele é compartilhado direto com cada usuário (WhatsApp/e-mail/cabo) e carregado no app.
- Assim, mesmo que alguém descubra o link público, não vê nenhum dado da Royal.

============================================================
PASSO 1 — PUBLICAR A CASCA (uma vez)
============================================================
1. Crie um repositório, ex.: `Copiloto-SP`.
2. Suba TODOS os arquivos desta pasta na RAIZ (index.html, manifest, sw.js,
   icon-*.png, .nojekyll). **Não suba o copiloto_dados.json.**
3. Settings → Pages → Branch `main` → `/ (root)` → Save.
4. Link do time: `https://sandroregal.github.io/Copiloto-SP/`

============================================================
PASSO 2 — CARREGAR OS DADOS (cada usuário, no aparelho)
============================================================
1. Abra o link no celular e instale (Adicionar à tela inicial).
2. Salve o `copiloto_dados.json` no aparelho.
3. No app, toque em ⟳ → selecione o `copiloto_dados.json`.
4. Pronto. O app guarda os dados localmente e reabre sozinho nas próximas vezes.

============================================================
ATUALIZAR OS DADOS
============================================================
- Conquista (mensal) e Retomada (diária/semanal): gera-se um novo
  `copiloto_dados.json` a partir das bases (ANP + vendas) e distribui-se o arquivo.
- Carregar o novo arquivo pelo ⟳ substitui o anterior no aparelho.

Fase 2 (Cross-sell) ATIVA: cesta atual × cesta típica do segmento.

Identidade Royal FIC · Volume m³ · Margem R$/L · Oportunidade em p.p.
Reclassificações vigentes: ex-vendedores (Patrícia, Valéria, Maurício, Vital) = carteira
órfã a redistribuir; Neusa e Tatiana = Mesa (fora da fila); Taciana = carteira normal.
