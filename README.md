# Desafio Criativo - Feedback de Clientes Bancarios com IA

## Objetivo do Projeto

Este projeto foi desenvolvido para o desafio criativo da DIO, com foco na construcao de um prompt capaz de orientar uma IA na analise de feedbacks de clientes bancarios.

A proposta e transformar comentarios de clientes em insights uteis para apoiar decisoes de melhoria em canais digitais, atendimento e experiencia do cliente.

## Passo 1: Intencao

Quero que a IA analise feedbacks de clientes bancarios sobre canais digitais, atendimento, Pix, cartao de credito e aplicativo para identificar temas recorrentes, reclamacoes frequentes, elogios, sentimento dos clientes e oportunidades de melhoria.

O resultado sera usado por uma equipe de experiencia do cliente, atendimento e canais digitais para apoiar a priorizacao de melhorias no aplicativo, nos processos de atendimento e na comunicacao com os clientes.

A entrega deve conter um resumo executivo, uma tabela com os principais temas identificados, exemplos de evidencias nos comentarios e recomendacoes praticas.

O resultado sera considerado bom se for claro, organizado, baseado apenas nos dados fornecidos, respeitar dados sensiveis e ajudar a equipe a tomar decisoes de melhoria.

## Passo 2: Contexto e Restricoes

Contexto: Estou trabalhando com feedbacks de clientes bancarios relacionados ao aplicativo, Pix, cartao de credito, conta digital e atendimento por chat.

Dados disponiveis: A base contem data do comentario, canal de atendimento, texto do feedback, produto citado e nota de satisfacao de 1 a 5.

Critérios de analise: A IA deve classificar os feedbacks por tema, sentimento, urgencia, produto citado e possivel impacto na experiencia do cliente.

Cuidados e restricoes:

- Use apenas os dados fornecidos;
- Nao invente numeros, causas ou conclusoes;
- Nao exponha dados pessoais ou sensiveis;
- Se houver informacao insuficiente, indique a limitacao;
- Nao ignore comentarios negativos;
- Diferencie reclamacoes, elogios e sugestoes;
- Use linguagem simples, direta e voltada para tomada de decisao.

## Passo 3: Prompt Final

```text
Atue como analista de dados e experiencia do cliente em uma instituicao bancaria.

Sua tarefa e analisar feedbacks de clientes bancarios sobre aplicativo, Pix, cartao de credito, conta digital e atendimento por chat para identificar temas recorrentes, sentimento dos clientes, urgencia dos problemas e oportunidades de melhoria.

Contexto: A analise sera usada por equipes de experiencia do cliente, atendimento e canais digitais para priorizar melhorias nos produtos e reduzir atritos na jornada dos clientes. O objetivo e transformar comentarios soltos em insights claros, seguros e acionaveis.

Dados disponiveis: Serao fornecidos registros contendo data do comentario, canal de atendimento, texto do feedback, produto citado e nota de satisfacao de 1 a 5.

Instrucoes de analise:

1. Classifique os feedbacks por tema, sentimento, urgencia, produto citado e possivel impacto na experiencia do cliente.
2. Identifique os principais padroes, problemas, elogios e oportunidades de melhoria.
3. Aponte evidencias nos dados fornecidos, usando exemplos curtos de comentarios.
4. Sugira acoes praticas para a equipe de experiencia do cliente, atendimento e canais digitais.
5. Destaque os problemas que podem afetar confianca, seguranca, acesso ao dinheiro ou continuidade do uso do servico.

Formato da resposta:

1. Resumo executivo com ate 5 linhas.
2. Tabela com as colunas: Tema, Produto/Canal, Sentimento, Urgencia, Evidencia e Acao sugerida.
3. Lista com as 3 prioridades mais importantes.
4. Lista de limitacoes da analise, caso os dados sejam insuficientes.

Restricoes:

- Use apenas os dados fornecidos.
- Nao invente numeros, causas, percentuais ou conclusoes.
- Nao exponha dados pessoais, dados bancarios, documentos, telefones, e-mails ou qualquer informacao sensivel.
- Se algum comentario tiver dados sensiveis, anonimize antes de citar.
- Informe claramente quando nao houver dados suficientes para uma conclusao.
- Use linguagem simples, objetiva e voltada para tomada de decisao.
```

## Exemplo de Uso do Prompt

O prompt pode ser usado com uma base simples de comentarios como:

```text
Data: 10/05/2026
Canal: Aplicativo
Produto: Pix
Nota: 2
Feedback: O Pix demorou para confirmar e fiquei inseguro se o dinheiro tinha sido enviado.

Data: 11/05/2026
Canal: Chat
Produto: Cartao de credito
Nota: 1
Feedback: Esperei muito tempo no atendimento e nao consegui resolver a contestacao da compra.

Data: 12/05/2026
Canal: Aplicativo
Produto: Conta digital
Nota: 5
Feedback: O app ficou mais rapido e consegui pagar minhas contas sem dificuldade.
```

## Critérios de Qualidade

O resultado ideal deve:

- Ser facil de entender;
- Separar problemas, elogios e sugestoes;
- Trazer evidencias reais dos comentarios;
- Respeitar privacidade e dados sensiveis;
- Evitar conclusoes sem base;
- Gerar recomendacoes praticas;
- Ajudar na priorizacao de melhorias.

## Principais Aprendizados

- Um bom prompt precisa ter objetivo claro;
- Contexto melhora a qualidade da resposta da IA;
- Restricoes evitam respostas inventadas ou inseguras;
- Em dados bancarios, privacidade e seguranca devem ser prioridade;
- A IA deve apoiar a analise, mas as conclusoes precisam estar baseadas nos dados fornecidos.

## Conclusao

Este desafio mostrou como estruturar um prompt completo para analise de feedbacks bancarios com apoio de IA. A solucao combina intencao, contexto, criterios de analise, formato esperado e cuidados com dados sensiveis.

O resultado final pode apoiar equipes de negocio, atendimento e experiencia do cliente na transformacao de comentarios em acoes praticas de melhoria.
