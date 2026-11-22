# MW4 DMZ — Guia de Camuflagens

Site estático responsivo com 35 armas e 770 entradas de camuflagens, filtros, pesquisa, acompanhamento de progresso e backup em JSON.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `mw4-dmz-guia`).
2. Envie os quatro arquivos **index.html**, **style.css**, **script.js** e **data.js** para a raiz do repositório.
3. Vá em **Settings → Pages → Build and deployment**.
4. Em **Source**, escolha **Deploy from a branch**; selecione **main** e **/(root)**; salve.
5. Aguarde o GitHub mostrar o link do site.

Também é possível abrir `index.html` diretamente no navegador. A fonte Google Fonts depende de internet, mas há fontes de fallback. O site não precisa de backend. O progresso é salvo com `localStorage`, localmente por navegador/dispositivo; use **Exportar progresso** para fazer backup.

## Importante

Conteúdo **não oficial** reunido a partir de rastreadores comunitários, compilado em 22/11/2026. Números de desafios podem estar incorretos ou variar por arma/atualização. Oito camuflagens militares por arma são placeholders de nível, e os requisitos globais de maestria precisam de verificação no jogo. A seção "Não oficial" indica essa limitação. O site não é afiliado aos criadores do jogo.

Fontes de referência:
- https://upblazed.com/tools/mw4-camo-tracker/dmz
- https://mw4camotracker.com/guides/special-camo-challenges

## Modos
DMZ: dados da comunidade (não oficiais). Warzone e Multijogador: navegação e arsenal implementados; requisitos ainda não verificados, portanto não são inventados. Para adicionar desafios confirmados, preencher `window.MW4_DATA.otherModes.warzone` e `.multiplayer` com objetos `{id,weapon,kind,camo,challenge,verified}`.
