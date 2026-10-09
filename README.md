# English Adventure — Pilot Week 1

## Objetivo
Esta versão é um protótipo de teste com pessoas de confiança. Ela não é ainda a plataforma final.

## O que está sendo testado
- A1 com interface bilíngue.
- Método: input → compreensão → recuperação → construção → produção → conversa.
- Construction Ladder.
- Real World English como exposição, não prova.
- Song of the Week e True Story of the Week.
- Human Check-in de 15 minutos.
- Learning Snapshot do professor.
- Feedback do piloto.
- Traduções em português brasileiro mais naturais e conversacionais.
- Atividade inicial de escrita com feedback por regras simples (não é IA).
- Gravação de áudio no navegador, reprodução e download local.
- História cultural com texto A1, tradução, vocabulário e áudio sintetizado.
- Links de busca para ouvir a música e consultar letras em serviços externos.

## Semana
1. Hello, This Is Me
2. I Can Understand You
3. I Can Tell You More About Me
4. Now, It's Your Turn
5. English in the Real World
6. Put It All Together
7. Let's Talk

## Como testar
1. Abra `index.html` em um navegador moderno.
2. Use Chrome/Edge/Safari para testar o áudio.
3. Idealmente teste com 3–5 pessoas diferentes.
4. Não explique demais antes de observar. Veja onde elas naturalmente travam.
5. Anote especialmente:
   - onde não entendem a instrução;
   - onde procuram a tradução;
   - onde entendem mas não conseguem falar;
   - onde a construção parece artificial;
   - onde ficam entediadas;
   - onde demonstram vontade de continuar;
   - quanto tempo cada dia realmente leva.
6. No Day 7, preencha o Human Check-in e o Pilot Feedback.
7. Use `EXPORT TEST DATA` para gerar um JSON com o feedback.

## Atualizações v1.2
- Instruções e orientações em português mais naturais em todos os dias da Semana 1.
- Texto em inglês e tradução brasileira aparecem imediatamente acima de cada botão de narração.
- O aluno pode acompanhar o texto, ouvir o áudio e depois tentar escutar novamente sem ler.
- O texto narrado usa a voz em inglês do navegador; a disponibilidade e a qualidade da voz dependem do dispositivo.
- Esta atualização não adiciona login, banco de dados, envio automático de gravações ou correção por IA.

## Importante
- O progresso fica apenas no navegador via localStorage.
- Não há login, banco de dados nem envio automático de áudio.
- A gravação usa o microfone do navegador; o aluno pode ouvir e baixar o arquivo para compartilhar manualmente com o professor.
- O feedback de escrita é uma primeira checagem baseada em regras e padrões simples; não substitui correção por IA ou por professor.
- A ofensiva de aprendizagem (streak) permanece no mapa de produto e ainda não está implementada.
- O objetivo agora é validar a experiência e a pedagogia antes de construir infraestrutura.

## Perguntas para a equipe
1. O aluno entende o que deve fazer sem ajuda?
2. O português está ajudando ou atrapalhando?
3. O aluno percebe o "brick" que está construindo?
4. O aluno entende que pode errar e continuar?
5. O input gera vontade/capacidade de falar?
6. O Construction Ladder ajuda ou parece infantil?
7. A semana parece uma jornada ou uma sequência de exercícios?
8. O professor consegue diagnosticar o gargalo em 15 minutos?
9. O que devemos remover?
10. O que devemos tornar melhor?


## Atualizações v1.3
- Atividades de escrita nos Days 2–6, alinhadas ao objetivo de cada dia.
- Feedback inicial com sugestões para identidade, origem, residência e ocupação.
- Exemplos opcionais para consulta, sem obrigar o aluno a copiar o modelo.
- Respostas de escrita guardadas localmente por dia e restauradas ao voltar à atividade.
- A escrita aparece antes do botão de concluir o dia.
- O feedback é baseado em regras simples, não em IA; respostas alternativas podem não ser reconhecidas.


## v1.4 — Microphone available throughout the week
The recording control is now available on Days 1–7. Days 2–6 have a daily speaking prompt, and Day 7 has an optional speaking sample for the teacher check-in. Recordings can be replayed and downloaded but are not uploaded automatically.
