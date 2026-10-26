# AGENTS.md — Diário de Vibe Coding

Este repositório é um diário de estudo do [Vibe Coding 101 (easy-vibe)](https://github.com/datawhalechina/easy-vibe). O produto aqui é o registro, não um app.

## Regra principal

Uma sessão de estudo = um registro em `journal/AAAA-MM-DD-slug.md` = um commit com a data no assunto.

## No começo da sessão

Confirme em uma linha qual capítulo do curso está sendo estudado e o que o usuário vai tentar construir.

## No fim da sessão

1. Entreviste o usuário com as quatro perguntas, uma de cada vez. Não invente respostas.
   - O que eu tentei
   - O que quebrou
   - Como resolvi
   - O que eu faria diferente
2. Preencha o registro com as respostas, em português e sem floreio. Registre também o próximo passo.
3. Coloque o link do capítulo no cabeçalho e o resultado (print, GIF ou demo) em `projetos/<slug>/`.
4. Adicione a linha na tabela de progresso do `README.md`.
5. Sugira a mensagem de commit; não execute Git de escrita:
   `docs(jornada): AAAA-MM-DD - <resumo curto>`

## Qualidade do registro

- Nada de "aprendi sobre X". O texto precisa dizer o que foi tentado, o erro concreto e como saiu dele.
- Se a sessão não deu certo, registre assim mesmo. O que quebrou também é resultado.

## Regras do curso

- O curso é CC BY-NC-SA 4.0. Parafraseie o conteúdo e linke a fonte; não copie trechos.
- Títulos de capítulos podem ficar em inglês; o registro é em português.
- Nunca commite `.env`, chaves de Supabase/Stripe ou qualquer segredo.

## Estrutura

- `journal/` — um arquivo por sessão
- `projetos/<slug>/` — print/GIF e, se for o caso, o código do app
- `recursos.md` — links que o usuário reabriu
- `TEMPLATE.md` — modelo do registro
