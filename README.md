# English Adventure — A1.01 a A1.07 (versão revisada de teste)

## Alterações desta revisão
- Layout reorganizado com visual mais próximo de uma experiência de aprendizagem polida: hero, cartões, hierarquia, sidebar e responsividade.
- Campo de escrita claramente identificado em cada unidade.
- Campo separado para preparar a fala da missão.
- Gravação de áudio restaurada em cada unidade: iniciar, parar, ouvir, baixar e enviar ao professor após login.
- Autenticação Supabase e painel do professor conectados ao projeto/bucket usados no piloto anterior.
- Removido o botão “Usar exemplo como apoio” e removido o preenchimento automático por modelo.
- Leitura em voz alta procura primeiro vozes inglesas conhecidas por serem mais naturais/femininas. Se o dispositivo não disponibilizar uma voz adequada, a interface informa isso em vez de escolher automaticamente uma voz claramente genérica.

## Como testar
1. Crie um site separado no Netlify, sem substituir o site publicado.
2. Faça deploy deste ZIP.
3. Teste login, gravação, reprodução local e envio com uma conta de aluno de teste.
4. Entre com uma conta de professor e teste a área de gravações.
5. Confira também a permissão de microfone em HTTPS e as regras RLS do Supabase.

## Limitações importantes
- A qualidade e a disponibilidade das vozes dependem do sistema operacional e do navegador; a página não consegue instalar uma voz natural no dispositivo.
- O código usa a chave publicável do Supabase no navegador, como esperado para cliente web; nunca adicionar service-role key ao front-end.
- O envio depende das políticas atuais do projeto Supabase, do bucket privado `student-audios`, da tabela `audio_submissions` e dos perfis em `profiles`. O deploy ainda precisa ser testado de ponta a ponta.
- O conteúdo A1.01–A1.07 ainda deve ser comparado linha a linha com a Planilha-Mãe antes de ser considerado pedagogicamente final.
- Esta versão é uma prévia independente. Não substitua a versão de produção antes de validar o teste.
