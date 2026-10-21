# Identidade e comunicacao Senior - guia para entregas do Scout

Fonte fornecida pelo usuario: Senior Design System.txt, resumo declarado do Marketing Design System e Guia de Marca 2026. Usar como referencia de estilo; nao alegar certificacao pelo Branding. Esta referencia orienta textos e eventuais artefatos visuais, nao altera fato comercial ou documentacao tecnica.

## Linguagem
- Usar portugues brasileiro, voz ativa, tom profissional, humano e objetivo.
- Quando houver comunicacao de marca, chamar a empresa de 'a Senior' e produto pelo nome proprio oficial.
- Primeira pessoa do plural quando adequado a texto institucional; em relatorio factual, usar voz neutra.
- Explicar abreviacoes essenciais, mostrar impacto e uma acao verificavel.
- Evitar jargoes gratuitos, exagero comercial, emojis decorativos e promessas sem fonte.
- Em mensagens de erro, informar limite e acao possivel, sem culpar o usuario.

## Visual quando solicitado — preferência expressa para o Scout 360
**Direção do usuário (19/10/2026): a identidade da interface Scout é VERDE-ESMERALDA, não azul.** Este é um ajuste específico do Scout; o pacote oficial da Senior inclui azul em alguns tokens, mas isso não autoriza reintroduzi-lo na interface deste plugin. Não apresentar a adaptação como alteração aprovada do Design System corporativo.

### Paleta específica do Scout
- Cor principal / ações: **esmeralda-700 `#047857`** — uso em botões e destaques com texto branco, contraste WCAG AA (aprox. 5,48:1).
- Esmeralda de apoio: `#059669` — bordas, elementos decorativos e títulos grandes; **não** usar texto branco pequeno sobre essa cor (contraste aprox. 3,77:1).
- Esmeralda escuro: `#065F46` — títulos e conteúdo de destaque com contraste alto.
- Texto padrão: cinza neutro escuro `#3B3D3D` — **sem azul**.
- Fundo de página: verde muito claro `#ECFDF5`; cards e superfícies: branco `#FFFFFF`.
- Hover de ação: `#065F46`; contorno de foco visível: `#047857`.
- Cor institucional original da Senior: `#00968C`, preservada **nos ativos oficiais** e onde precisar identificar a marca Senior; não recolorir o logotipo para esmeralda.
- Laranja institucional `#EF8833` fica reservado a chamadas reais de conversão quando solicitado. Em botão de texto branco, usar a variante acessível `#B95E00` (o original não atende contraste AA). Não usar laranja de forma decorativa.
- Não aplicar o azul `#33466C`, os azuis claros ou o fundo azulado `#F6F9FE` da paleta corporativa ao visual personalizado do Scout. Não trocar o azul por outra cor saturada como padrão.

### Fonte, ícones e identidade corporativa
- Fonte Public Sans com poucas variações de peso, sem redistribuir arquivos de fontes; WCAG AA, foco visível e navegação por teclado.
- Ícones de linha consistentes e com rótulo, sem emojis decorativos em peças visuais.
- `assets/scout360-logo-compassado.png` - icone com bussola e degradê verde selecionado pelo usuario (primeira opcao), 1024x1024, PNG transparente. Ja nao e o logo/composerIcon do plugin; preservado no pacote. Esta ilustracao do Scout nao e identidade corporativa homologada pelo Branding.
- `assets/scout360-logo-esmeralda.png` - icone anterior preservado no pacote, mas nao e mais o logo/composerIcon atual.
- `assets/senior-simbolo-box-verde.png` — simbolo oficial da Senior, copiado sem edicao. **Logo, icone e composerIcon atuais do plugin** (decisao do usuario em 21/10/2026).
- `assets/senior-logo-verde.png` — logotipo oficial completo, copiado sem edição. Se houver futuras peças visuais, usar a marca completa com a função adequada; nunca reconstruir o logo.
- Ícone de plugin não equivale a uma interface completa. O pacote não contém app UI nem garante como cada host (Claude, Codex, ChatGPT ou outro) usa as cores fornecidas em metadados. Para uma interface própria no futuro, usar esta paleta e não importar automaticamente os estilos azuis do pacote corporativo.
