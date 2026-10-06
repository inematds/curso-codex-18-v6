# Brief para autores de aula — Codex 18 v6

## Leia antes (nesta ordem)
1. `~/.claude/skills/formato-curso-v6/SKILL.md`
2. `~/.claude/skills/formato-curso-v6/references/CONTEUDO-INICIANTE.md` (inclui §1b e §2b, o perfil técnico)
3. `~/.claude/skills/formato-curso-v6/references/V6-DESIGN.md` (visuais com markup pronto)
4. `~/.claude/skills/formato-curso-v6/references/CHECKLIST-V6.md` (a rubrica que o script mede)
5. **Aula-modelo aprovada (10/10):** `~/.claude/skills/formato-curso-v6/examples/aula-1-oswork.html`. Copie a estrutura e o tom (não o conteúdo). Molde vazio: `~/.claude/skills/formato-curso-v6/assets/aula-template.html`.
6. **Currículo deste curso:** `~/projetos/curso-codex-18-v6/context/curriculo.md` (aluno, profissões, promessa, tipo e gancho de cada aula).
7. **Perfil/termos:** `~/projetos/curso-codex-18-v6/curso.json` (`perfil: tecnico` + `termos`). Todo termo da lista-sentinela (terminal, plugin, Git, branch, login, API, script, servidor, arquivo de configuração, instalar, download…) e de `termos` que aparecer na aula precisa de `.gterm` na própria aula (1ª vez). Use a MESMA `data-def` do termo em todas as aulas — definições padrão abaixo.

## Conteúdo de origem (fatos reais; não invente)
- **Fatos e comandos permitidos:** tabela FATOS em `~/projetos/curso-codex-18/context/SPEC.md` (Codex 0.159.2 conferido). Nenhum outro comando, flag ou número.
- **O que cada conceito ensina:** `~/projetos/curso-codex-18/context/CONTEUDO.md`.
- **Profundidade e exemplos:** o curso v2 do mesmo assunto, `~/projetos/curso-codex-18/context/corpos/modulo-T-M.html` (aula N do v6 = conceito N; mapa: aulas 1–4 → modulo-1-1..1-4; 5–7 → modulo-2-1..2-3; 8–13 → modulo-3-1..3-6; 14–18 → modulo-4-1..4-5). Use só como referência de fatos e ideias; o v6 é outro formato (≤900 palavras, 3–4 steps, visual real em cada step).
- **Regra dura: não citar nenhuma fonte** — nenhum vídeo, canal, autor, criador, YouTube, "num vídeo". Curso autoral. Nada de preço em dinheiro (nem "$"). Recursos do app do Codex: escreva "o nome do botão pode mudar entre versões" quando descrever onde clicar.
- **Caminho principal = aplicativo do Codex** (cliques, caixa de mensagem). Terminal só como alternativa opcional num `.terminal`, nunca obrigatório na prática.

## Profissões dos exemplos (`p[data-ex]`)
Alterne entre `data-ex="consultora"` — **Paula, 45, consultora de RH**, pasta `paula-escritorio` — e `data-ex="lojista"` — **Jorge, 52, dono de loja de materiais de construção**, pasta `loja-jorge` (planilha `estoque.csv`, catálogo, promoções da semana). No v2 o lojista se chamava Rui: **aqui é Jorge**, sempre. Situações novas em cada step; telas de "resposta boa" nunca inventam dado ausente do pedido.

## Telas simuladas
`.tela` com `tela-top` "Codex" (janela genérica, sem marca). Mensagem do aluno = o pedido real em português; resposta do Codex = o começo real da resposta, incluindo quando cabível uma linha tipo "Li paula-escritorio/AGENTS.md e clientes/acme.md" (mostra o ciclo). `.janela` para pastas (`paula-escritorio/`, `AGENTS.md`, `.codex/`, `.agents/skills/…`).

## Definições padrão (`data-def`, copie igual)
- AGENTS.md: "arquivo de texto na pasta do projeto com as regras da casa. O Codex lê antes de cada conversa nova."
- Markdown: "texto simples com marcas leves: # para título, - para lista, **dois asteriscos** para negrito. Arquivos terminam em .md."
- harness: "o programa que dá ao modelo de IA ferramentas (ler arquivo, rodar comando, abrir site) e o ciclo de trabalho. O Codex é um harness."
- worktree: "uma cópia de trabalho do projeto, feita pelo Git, para testar mudanças sem mexer no original."
- localhost: "endereço que aponta para o próprio computador. Só abre na máquina onde a página está rodando."
- token: "pedaço de texto que o modelo lê ou escreve, mais ou menos 4 letras ou três quartos de uma palavra."
- sandbox: "área isolada onde os comandos do Codex rodam sem acesso ao resto do computador."
- MCP: "padrão aberto para ligar agentes de IA a ferramentas e aplicativos externos."
- skill: "receita reutilizável: um arquivo SKILL.md com o nome, quando usar e os passos de uma tarefa."
- SKILL.md: "o arquivo da skill: no topo, nome e quando usar; embaixo, as instruções."
- subagente: "ajudante que o Codex principal dispara para fazer uma parte do trabalho em paralelo."
- config.toml: "arquivo de preferências do Codex, em texto, com linhas do tipo chave = valor."
- plugin / plugins: "conexão pronta entre o Codex e um aplicativo, como e-mail, agenda ou drive. Você entra uma vez com a sua conta."
- terminal: "janela de texto onde você digita comandos para o computador. No Codex é opcional: o aplicativo faz o mesmo com cliques."
- Git: "programa que guarda o histórico de versões de uma pasta e permite cópias paralelas."
- branch: "linha paralela de mudanças dentro do Git. A linha principal costuma se chamar main."
- login: "entrar com o seu usuário e senha num serviço."
- API: "porta que um programa oferece para outro programa conversar com ele. Cobra por uso, à parte da assinatura."
- arquivo de configuração: "arquivo de texto onde ficam as preferências de um programa."
(Precisou de outro termo da sentinela? Defina em ≤2 frases concretas e avise no relatório.)

## Cena da aula
`figure.cena` aponta para `assets/img/aula-N.webp` (sendo gerada agora). A descrição de cada cena está em `~/projetos/curso-codex-18-v6/context/cenas.tsv` — escreva o `alt` em português descrevendo essa cena e o que ela ensina. Se a imagem ainda não existir na sua cópia, crie um placeholder WebP 1280×720 só na cópia (o auditor mede o peso) e siga.

## Material complementar (opcional, recomendado)
Depois da `.fecho`, um `details.complementar` com 1–2 `.comp-sec` aprofundando o conceito a partir do módulo v2 correspondente (V6-DESIGN §3.7), sem fontes.

## Verificação (numa cópia isolada; NUNCA monte no repositório real)
```bash
S=/tmp/claude-1000/-home-nmaldaner-projetos-wifi/66577a61-052b-4e28-9b01-e9311ae7bd0e/scratchpad/v6-aulas-<SUAS-AULAS>
rm -rf $S && cp -r ~/projetos/curso-codex-18-v6 $S && rm -rf $S/.git $S/aulas/*
# coloque SÓ as suas aulas em $S/aulas/ e deixe em $S/curso.json → "modulos" apenas UM módulo com elas
python3 ~/.claude/skills/formato-curso-v6/scripts/montar-curso.py $S
node ~/.claude/skills/formato-curso-v6/scripts/auditar-curso.cjs $S/curso.html
node ~/.claude/skills/formato-curso-v6/scripts/testar-motor.cjs $S/curso.html
```
Itere até **toda aula ≥9/10, sem falha nos critérios 7, 8 e 10**, e o motor sem erro. Depois faça o **leitor simulado** (`references/TESTE-HUMANO.md` §1) em cada aula e corrija qualquer "travei".

## Entrega
Copie de volta SOMENTE `aulas/aula-N.html` das suas aulas para `~/projetos/curso-codex-18-v6/aulas/`. Não mexa em curso.json, assets, landing, nem nas aulas dos outros. Sem commit. Sem API paga.
Relate: nota do auditor por aula, o que corrigiu, resultado do leitor simulado, termos novos que definiu e dúvidas de conteúdo.
