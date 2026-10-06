# Currículo — Codex 18 v6: os 18 conceitos essenciais

## Passo 0 (respostas herdadas do curso v2 `curso-codex-18`, aprovado pelo usuário para reaproveitar)

1. **Aluno:** profissional de 30+ que já usa ChatGPT ou Claude no navegador e nunca abriu o Codex. Não programa. Usa computador no trabalho (o Codex roda no computador; o celular só acompanha).
2. **Profissões-alvo (`p[data-ex]`):**
   - `consultora` — **Paula, 45, consultora de RH**, trabalha sozinha. Pasta `paula-escritorio` (clientes, propostas, modelos de e-mail, posts do LinkedIn).
   - `lojista` — **Jorge, 52, dono de uma loja de materiais de construção**. Pasta `loja-jorge` (planilha de estoque `estoque.csv`, catálogo, promoções da semana, página simples da loja).
3. **Tecnologia que já usa:** chat de IA no navegador, e-mail, planilha, WhatsApp. Nunca usou terminal.
4. **Sai fazendo:** usa o Codex num projeto próprio, com AGENTS.md, skills, plugins e permissões certas; escolhe modelo e esforço pela tarefa; delega em paralelo (subagentes) e no horário marcado (tarefas agendadas).
5. **Tempo por sessão:** ~15 min por aula (teto 18).

Perfil técnico (o assunto exige falar em terminal, plugin, branch): todo termo da sentinela + `termos` do curso.json é definido com `.gterm` em cada aula em que aparece. Caminho principal = aplicativo do Codex (cliques); terminal só como alternativa, nunca obrigatório.

**Regra dura: não citar nenhuma fonte** (vídeo, canal, autor, criador). Curso autoral.
**Fatos permitidos:** tabela FATOS de `~/projetos/curso-codex-18/context/SPEC.md` (Codex 0.159.2 conferido). Conteúdo de cada conceito: `~/projetos/curso-codex-18/context/CONTEUDO.md` (troque Rui → Jorge, `loja-rui` → `loja-jorge`). Recursos do app: "o nome do botão pode mudar entre versões". Nada de preço em dinheiro.

## Aulas (promessa · tipo da prática · gancho)

### Módulo 1 · Fundamentos — o Codex deixa de ser um chat
1. **Projetos: a pasta que lembra de você** — Você consegue abrir uma pasta sua no Codex e receber uma resposta que cita os arquivos dela. · prompt · "Toda conversa nova ainda chega sem saber suas regras."
2. **AGENTS.md: as regras da casa** — Você consegue escrever um AGENTS.md de 10 linhas e ver o Codex seguir uma regra dele numa conversa nova. · prompt · "Ele obedece, mas você não vê o que ele faz por dentro."
3. **O ciclo do agente** — Você consegue abrir o registro de um pedido e dizer quais arquivos ele leu e em que ordem. · analise (ou prompt) · "Ele para quando acha que acabou; e se você quiser que ele insista?"
4. **/goal: um objetivo até o fim** — Você consegue escrever um objetivo verificável, com o que ele não pode fazer, e rodá-lo numa tarefa pequena. · prompt · "Até aqui tudo rodou no seu computador. E quando você sair de casa?"

### Módulo 2 · Ambientes — onde o trabalho acontece
5. **Local, nuvem e celular** — Você consegue dizer se um link abre para outra pessoa e mandar uma tarefa ao Codex pelo celular. · analise + tarefa · "Testar mudança grande no projeto original dá medo."
6. **Worktrees: cópias para testar sem medo** — Você consegue pedir uma cópia de trabalho, testar nela e decidir se junta ou descarta. · prompt · "Onde ficam as preferências que valem para todo projeto?"
7. **A pasta .codex: configurações** — Você consegue achar as duas pastas .codex e pedir ao Codex que mude uma preferência no lugar certo. · prompt · "Uma dessas preferências é o modelo — qual escolher?"

### Módulo 3 · Controle — força, custo e confiança
8. **Modelos: força e custo** — Você consegue escolher o modelo certo para três tarefas do seu dia e trocar no meio da conversa. · tarefa · "Dentro do mesmo modelo ainda dá para pensar mais ou menos."
9. **Esforço e modo rápido** — Você consegue montar sua tabela tarefa → modelo → esforço. · tarefa · "Agora: quanto ele pode fazer sem perguntar?"
10. **Permissões: quanto ele faz sozinho** — Você consegue escolher o modo de permissão para cada pasta e registrar uma ação proibida. · prompt · "Ele já é seguro; agora, que repita bem o que deu certo."
11. **Skills: receitas reutilizáveis** — Você consegue transformar uma tarefa que deu certo numa skill e chamá-la de novo. · prompt · "Onde essa receita mora, e como levar as suas de outra ferramenta?"
12. **A pasta .agents e a vinda do Claude Code** — Você consegue dizer onde está cada skill (projeto ou global) e pedir a adaptação de um projeto feito no Claude Code. · prompt · "As receitas estão prontas; falta ligar seus aplicativos."
13. **Plugins: conecte seus aplicativos** — Você consegue conectar um aplicativo, usá-lo num pedido e saber como desconectar. · tarefa · "E o site que não tem plugin nenhum?"

### Módulo 4 · Ferramentas e escala — o Codex trabalhando por você
14. **Navegador: o Codex usa sites por você** — Você consegue pedir uma tarefa num site sem integração, com o limite do que ele pode fazer. · prompt · "Ele usa sites; e se ele fizer um para você?"
15. **Sites: do localhost para o mundo** — Você consegue publicar uma página simples e decidir quem pode abrir. · prompt · "Uma tarefa grande sozinho demora; dá para dividir."
16. **Subagentes: delegue em paralelo** — Você consegue pedir uma pesquisa dividida em três ajudantes com modelo mais barato e juntar o resultado. · prompt · "E o que se repete toda semana?"
17. **Tarefas agendadas: o Codex no piloto** — Você consegue criar uma tarefa semanal que só prepara rascunho. · prompt · "Falta comandar tudo isso sem teclado."
18. **Modo de voz: tudo junto** — Você consegue fazer um pedido falado que usa vários conceitos do curso e montar sua rotina semanal. · tarefa · (fim: rotina pronta)
