<p><img src="assets/senior-logo-verde.png" alt="Senior" height="60"></p>

# Senior Scout 360

Inteligencia comercial B2B multissetorial baseada em evidencias, com verificacao documental de produtos Senior quando pertinente.

O Scout 360 investiga empresas e oportunidades B2B, organiza evidencias, mapeia processos, tecnologia, pessoas e riscos e recomenda a proxima validacao comercial. Ele separa fato verificado, indicio, informacao do usuario e hipotese, e nunca inventa CNPJ, decisor, sistema instalado, orcamento ou score.

## Skills

| Skill | Quando usar |
| --- | --- |
| `inteligencia-de-conta` | Pesquisa e leitura comercial de uma conta ou prospect |
| `investigar-grupo-economico` | CNPJ, matriz, filiais, socios e grupo economico |
| `analisar-operacao-e-processos` | Como a empresa opera, cadeia de valor e friccoes |
| `investigar-tecnologias-e-concorrencia` | ERP, sistemas, fornecedores, integracoes e concorrentes |
| `mapear-pessoas-e-decisao` | Participantes, influenciadores e processo decisorio |
| `auditar-evidencias-comerciais` | Conferir fontes, alegacoes e contradicoes de um dossie |
| `avaliar-aderencia-portfolio-senior` | Ligar um problema confirmado a capacidade documentada da Senior |
| `consolidar-dossie-executivo` | Dossie executivo integrado de uma empresa ou grupo |
| `analisar-reuniao` | Uma reuniao, transcricao ou ata |
| `revisar-oportunidade` | Historico completo de uma oportunidade (CRM, propostas, reunioes) |
| `fechamento-de-trimestre` | Forecast ou revisao executiva de final de periodo |
| `proximo-movimento-comercial` | So a proxima acao ou as proximas perguntas |

As regras comuns ficam em `references/`: contrato de evidencias, roteamento, uso da Documentacao Senior e identidade visual.

## Instalação no Claude Code

Repositório público: https://github.com/brunolimaff-jpg/senior-scout-360-claude.
Qualquer pessoa pode instalar com o comando abaixo, sem convite e sem autenticação no GitHub. É necessário ter Git e Claude Code instalados. O uso do Claude Code continua sujeito à autenticação e ao plano exigidos pela plataforma.

No Claude Code 2.1.275 ou mais novo, execute na conversa do Claude Code:

```text
/plugin install senior-scout-360 --marketplace brunolimaff-jpg/senior-scout-360-claude
```

Em versões anteriores com suporte a plugins, execute os dois comandos separadamente:

```text
/plugin marketplace add brunolimaff-jpg/senior-scout-360-claude
/plugin install senior-scout-360@senior-scout-360-marketplace
```

Reinicie o Claude Code após instalar. Para conferir o uso, peça uma das análises da seção abaixo ou use `/senior-scout-360:inteligencia-de-conta`.

### Atualizações

Para atualizar manualmente pelo terminal:

```bash
claude plugin marketplace update senior-scout-360-marketplace
```

```bash
claude plugin update senior-scout-360@senior-scout-360-marketplace
```

Reinicie o Claude Code para carregar a atualização. A publicação de um commit no GitHub não garante que todas as instalações sejam atualizadas automaticamente. Para ativar a atualização automática, abra `/plugin`, entre em **Marketplaces**, selecione `senior-scout-360-marketplace` e escolha **Enable auto-update**.

Ao publicar uma nova versão, aumente `version` em `.claude-plugin/plugin.json` e mantenha `.codex-plugin/plugin.json` com a mesma versão. O catálogo usa a versão do manifesto do plugin.

### Teste local sem instalação

Descompacte o pacote e inicie o Claude Code pelo terminal:

```bash
claude --plugin-dir caminho/senior-scout-360
```

Esse modo não configura atualizações pelo catálogo.

## Uso

Basta pedir em linguagem natural, por exemplo:

- "Pesquise a empresa X e prepare uma leitura comercial completa."
- "Analise esta transcricao de reuniao."
- "Compile tudo desta conta para o fechamento do trimestre."

## Limites

- Opera somente leitura: nao envia mensagens nem altera CRM.
- Nao inclui MCP, API, RAG ou banco de dados; a pesquisa externa depende das ferramentas disponiveis no host.
- Afirmacoes sobre produtos Senior exigem documentacao oficial ou o plugin Documentacao Senior, quando instalado.
- Nao calcula Score PORTA, probabilidade ou ranking.

## Compatibilidade

O pacote funciona no Claude Code (`.claude-plugin/plugin.json`) e no Codex (`.codex-plugin/plugin.json`).

Os logotipos da Senior em `assets/` sao marcas da Senior Sistemas e foram incluidos sem edicao.
