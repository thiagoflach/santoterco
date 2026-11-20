# Santo Terço

Aplicativo web para acompanhar a reza do terço no celular, seguindo a estrutura do "Terço da Obra".

- Toque em qualquer lugar do terço para passar para a próxima conta.
- Os mistérios do dia são escolhidos automaticamente pelo dia da semana (e podem ser trocados tocando no nome).
- "Ver oração" mostra o texto da oração do momento.
- Ajustes: tema claro ou escuro; orações em latim (padrão) ou português.

## Arquivos

- `index.html`: a tela e a estrutura do terço (ordem dos passos e contas marcadas).
- `oracoes.js`: os textos das orações (latim e português), os nomes dos mistérios e a lista de imagens. Para corrigir um texto, edite só aqui.
- `imagens/`: uma imagem por mistério (ex.: `gozosos-1.jpg`).

## Pendências

- **Botão "Auxílio" (Ladainha em latim) desativado** enquanto aguarda autorização de uso do áudio do Spotify.
  O botão aparece apagado e não toca nada. Toda a configuração está guardada em `oracoes.js`, na seção
  **AUXÍLIO** (episódio `6evbEetOndo4JrdJABFVUg`, de 16:38 a 19:28,5). Para reativar, troque
  `"ativo": false` por `"ativo": true`.
