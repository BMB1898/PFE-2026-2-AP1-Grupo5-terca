================================================================================
GUIA DETALHADO DO SITE — PKZ & ONE-TO-ONE
================================================================================
Documento compilado a partir das reuniões gravadas com o cliente
Data de compilação: setembro de 2026


COMO ESTE GUIA FOI MONTADO
--------------------------------------------------------------------------------
Foram usados 7 arquivos de transcrição, na verdade correspondentes a 2
conversas diferentes:

1) "áudio_PKZ.txt" — a reunião principal (briefing/descoberta). Nela,
   Henrique (fundador), Pedro (coordenador) e Eduardo, o "Dudu" (professor),
   apresentam o negócio, mostram o aplicativo interno que já existe hoje
   (feito por um colega, o Arthur, que é professor de educação física e não
   programador) e explicam as dores e necessidades reais do dia a dia.

2) Os outros 6 arquivos — uma reunião posterior, focada especificamente na
   construção do site: estrutura de páginas, textos, identidade visual, FAQ,
   forma de mostrar preço, gráficos de evolução do atleta, sistema de fila de
   espera etc.

--------------------------------------------------------------------------------
SUMÁRIO
--------------------------------------------------------------------------------
 1. Contexto do negócio
 2. One-to-One vs. PKZ — a diferença que o site precisa comunicar
 3. Arquitetura do site (sitemap)
 4. Página inicial (hub) — seção por seção
 5. Landing page — One-to-One
 6. Landing page — PKZ
 7. Textos já definidos pelo cliente (usar como estão)
 8. Perguntas frequentes (FAQ) para o site
 9. Estratégia comercial: como tratar preço no site
10. Direção visual e de conteúdo audiovisual
11. Portal do aluno/atleta (área logada) — requisitos funcionais
12. Inteligência artificial: onde e como usar
13. Serviços adicionais que podem aparecer no site
14. O que já existe no app atual (herança a aproveitar)
15. Glossário de termos do cliente
16. Pontos em aberto — confirmar com o cliente
17. Checklist-resumo final



================================================================================
1. CONTEXTO DO NEGÓCIO
================================================================================

1.1 História e origem
--------------------------------------------------------------------------------
Henrique sempre trabalhou com desenvolvimento profissional de atletas.
Antes de existir um espaço físico, ele ia de carro/moto até os alunos-
atletas e treinava dentro dos condomínios deles, às vezes reunindo um grupo
para treinar junto. Em determinado momento, a demanda cresceu tanto (região
da Barra da Tijuca) que ele não conseguia mais atender sozinho, e o estúdio
onde ele atuava também não dava conta de todo mundo. Daí veio a ideia de
montar um espaço próprio, um centro de treinamento para atletas.

Já existia, ligado a ele, um espaço chamado "Mutual" — uma academia de
personal training para adultos, atletas e não atletas, focada em performance
dentro do esporte que a pessoa pratica (futebol, corrida etc.).

Quando esse novo espaço/negócio se organizou (dentro de uma galeria), ele foi
dividido em dois lados/linhas de atuação, e por isso ganhou dois nomes:
primeiro veio o One-to-One; seis a sete meses depois nasceu o PKZ.

Hoje, no dia a dia, o cliente trata tudo simplesmente como "PKZ One-to-One":
na prática, é uma coisa só.

1.2 Quem é quem
--------------------------------------------------------------------------------
- Henrique — fundador. É quem toma as decisões finais sobre o negócio e sobre
  o site. Traz a visão comercial e de metodologia.
- Pedro — coordenador geral. Conhece a fundo o funcionamento do aplicativo
  atual e das rotinas administrativas (agendamento, relatórios, cobrança).
- Eduardo, o "Dudu" — professor/treinador. Traz a visão de quem usa o sistema
  no dia a dia, na ponta, com o aluno na frente.
- Arthur — colaborador que construiu o aplicativo interno que existe hoje.
  É professor de educação física, não é desenvolvedor, e por isso o app atual
  é descrito pelo próprio time como funcional mas "sem glamour" e limitado
  (por exemplo, não conseguiram implementar cobrança/pagamento de forma
  completa).

1.3 Estrutura: uma empresa, duas marcas
--------------------------------------------------------------------------------
São duas linhas de atuação que funcionam de forma independente no dia a dia,
mas são geridas pelas mesmas pessoas — na prática, a mesma empresa.
(Formalmente pode haver mais de um CNPJ envolvido — o cliente menciona
pacotes "que contém para todas as múltiplas empresas" — mas isso é um
detalhe societário que não deve aparecer para o público; para o usuário do
site, a mensagem é sempre "somos uma coisa só".)

Isso é uma diretriz de conteúdo explícita do cliente: o site pode (e deve)
separar a comunicação de cada marca, mas sempre deixando claro que as duas
fazem parte da mesma empresa/filosofia, aplicada de formas diferentes.

1.4 Localização e público
--------------------------------------------------------------------------------
O negócio fica na Barra da Tijuca (Rio de Janeiro), mas atende muita gente
que não mora na região (inclusive de bairros vizinhos, como o Recreio dos
Bandeirantes). Isso é relevante para a seção 9 (preço): para quem já é da
Barra, o valor cobrado não assusta tanto; para quem vem de fora, o
deslocamento + o valor juntos podem intimidar mais.

O cliente também menciona ter uma frente de intercâmbio/parceria
internacional (cita "um espaço lá... um grupo de campo, que é uma galera que
faz intercâmbio"), com mais de 60 atletas envolvidos em aprender a fazer as
avaliações. É um detalhe pontual da fala dele — vale confirmar com ele se
isso deve virar conteúdo institucional ("nossa história"/"quem somos") ou se
é apenas uma frente à parte, sem relevância para o site neste momento.



================================================================================
2. ONE-TO-ONE VS. PKZ — A DIFERENÇA QUE O SITE PRECISA COMUNICAR
================================================================================

Esse foi um dos pontos que o time perguntou diretamente ao cliente, porque a
primeira impressão da equipe ("PKZ = alto rendimento/jovem; One-to-One =
musculação") estava incompleta. A explicação do próprio Henrique foi mais
precisa e é ela que deve orientar o site:

2.1 One-to-One
--------------------------------------------------------------------------------
- Público: adultos, de 17 a 90 anos (em outro momento também descrito como
  "pessoas de todas as idades, independente do objetivo").
- Abordagem: treinamento convencional de musculação/personal training —
  exercícios com peso livre, dinâmicos, com aparelhos e configuração
  individual.
- Trabalha valências físicas de forma isolada por grupo muscular (ex.: um
  exercício de puxada para fortalecer o dorsal).
- Cuidado com atletas amadores também acontece aqui, mas de forma
  convencional (não é a proposta central).

2.2 PKZ
--------------------------------------------------------------------------------
- Público: infanto-juvenil, atletas de 7 a 15 anos (em outro momento também
  descrito como "atletas adolescentes").
- Abordagem: metodologia própria chamada "sistema complexo". Em vez de
  isolar grupos musculares, o time mapeia as exigências específicas
  (complexidades) daquele esporte e treina o atleta dentro dessas
  complexidades — de forma funcional e integrada.
  Exemplo dado pelo próprio cliente: um piloto de kart, no One-to-One,
  treinaria puxada para fortalecer o dorsal (exercício isolado). Já no PKZ,
  ele treinaria sentado, fazendo um movimento complexo enquanto
  simultaneamente precisa estabilizar a cabeça/pescoço para sustentar o
  tronco — replicando a demanda real do esporte dele.
- Processo do atleta: avaliação inicial com 16 testes físicos (entre eles:
  salto, velocidade, agilidade, velocidade de reação, foco — a lista
  completa dos 16 não foi detalhada nas gravações, vale pedir ao cliente).
  A partir daí monta-se um cronograma de treino do mês (um "mesociclo",
  dividido em "microciclos"). A cada treino, gera-se um relatório; a cada
  mês, o atleta é reavaliado para medir evolução.

2.3 Quadro-resumo
--------------------------------------------------------------------------------
                    ONE-TO-ONE                  PKZ
  Público-alvo:     Adultos (17-90 anos)        Crianças/jovens (7-15 anos)
  Foco:             Musculação/performance       Alto rendimento esportivo
                     pessoal em geral             específico
  Método:           Treino isolado por grupo     "Sistema complexo":
                     muscular, com aparelhos       movimento funcional
                                                    ligado ao esporte
  Avaliação:        Mais convencional            16 testes físicos +
                                                   reavaliações periódicas
  Capacidade/       Até 3 alunos por professor,   Até 6 atletas por horário
  turma:            por horário (conforme o       (treino em grupo — a
                     professor Eduardo)             confirmar exatamente
                                                    com o cliente se é
                                                    sempre PKZ)

2.4 O que as duas têm em comum
--------------------------------------------------------------------------------
Segundo o próprio Henrique: "os dois vão atingir um objetivo único... mas um
aplica de um jeito e o outro aplica de outro." A base é sempre a mesma:
trabalhar o atleta a partir das valências físicas + a lógica do esporte
específico + a metodologia central da casa. Isso é aplicável a qualquer
esporte (o cliente usa o exemplo hipotético de um piloto de kart: nunca
apareceu na prática, mas se aparecesse, a mesma lógica de adaptação seria
usada). Essa mensagem — "metodologia única, aplicada de forma flexível para
qualquer esporte e qualquer fase da vida" — é um ótimo pilar de copy para o
site.



================================================================================
3. ARQUITETURA DO SITE (SITEMAP)
================================================================================

3.1 Conceito geral
--------------------------------------------------------------------------------
A ideia validada com o cliente (inclusive citando que partiu de orientação
do professor da turma) é um modelo em 3 camadas:

  CAMADA 1 — HUB (página inicial única)
      Apresenta a empresa como um todo. É o primeiro contato de QUALQUER
      visitante, cliente ou não. A partir dela, a pessoa escolhe entre
      One-to-One e PKZ (dois grandes botões/seções, com uma transição
      animada de cor ao clicar/passar o mouse).
              |
              +--> CAMADA 2 — LANDING PAGE DE CADA MARCA
              |      Uma página só sobre One-to-One (com o tema visual dela)
              |      e uma página só sobre PKZ (com o tema visual dela).
              |      Aqui entram: metodologia, diferenciais, FAQ, professores,
              |      depoimentos, um botão de WhatsApp específico daquela
              |      marca, e o convite para logar/cadastrar.
              |              |
              |              +--> CAMADA 3 — PORTAL DO ALUNO/ATLETA
              |                     Área restrita, exige login. Uma para
              |                     One-to-One ("portal adulto") e outra para
              |                     PKZ ("portal atleta"/pais). Aqui ficam
              |                     agendamento, relatórios, gráficos de
              |                     evolução, cobrança etc. (detalhado na
              |                     seção 11).

Regra de ouro dita explicitamente pelo cliente: quem entra no site pode ser
qualquer pessoa (curiosa, nunca ouviu falar da empresa) ou já pode ser
cliente. Por isso, o conteúdo institucional/explicativo (o que é a empresa, o
que é a metodologia, FAQ) deve ficar mais acessível/mais acima, e a parte
"de banco" (login, área de associado, agendamento, relatórios) deve ficar
mais restrita e mais abaixo/dentro da área de login — "porque é muito
restrito para quem já é cliente... para quem não é, a gente quer só mostrar
o que é a empresa."

3.2 Menu de navegação (definido pelo próprio time em conversa com o cliente)
--------------------------------------------------------------------------------
    1to1   |   PKZ   |   Planos   |   Agendar   |   Cadastro

3.3 Observação importante de nomenclatura
--------------------------------------------------------------------------------
A cada marca corresponde um WhatsApp diferente, mas quem atende dos dois
lados é a mesma pessoa. Decisão do cliente: não expor nenhum número de
telefone na página do hub — o número específico de cada marca só deve
aparecer dentro da landing page daquela marca ("talvez a gente vai ter que
fazer a divisão aqui... só coloca dentro daquela [landing page]").



================================================================================
4. PÁGINA INICIAL (HUB) — SEÇÃO POR SEÇÃO
================================================================================

Ordem sugerida, na sequência em que foi discutida com o cliente (do topo da
página para baixo). Onde havia hesitação/mudança de ideia ao longo da
conversa, deixei isso anotado.

1) HERO (topo da página)
   - Vídeo (preferência do cliente a foto estática, principalmente se for
     algo animado) ou, alternativamente, imagem de fundo com baixa opacidade
     mostrando cenas de treino ao fundo (referência dada pelo próprio time:
     "tipo o efeito da logo da Marvel, várias cenas simultâneas com
     opacidade baixa ao fundo" — o cliente gostou da ideia e pediu para virar
     vídeo, não foto, se for possível).
   - Frase de abertura curta que gere curiosidade — inspiração citada
     explicitamente pelo cliente: o jeito como o site do Nubank abre com uma
     frase de efeito e "obriga" a pessoa a descer para entender mais.
   - Botão de contato direto e visível — o cliente pediu explicitamente um
     "botão direto pro WhatsApp" aqui, de fácil acesso (mas sem expor o
     número em si).
   - Eles já têm vídeos corporativos prontos (formato diagonal e vertical)
     que podem ser reaproveitados e atualizados.

2) SOBRE A EMPRESA (uma seção só, antes de dividir nas duas marcas)
   - Texto curto explicando "o que somos" — voltado para quem não conhece
     nada da empresa ainda (o cliente insiste neste ponto: nem todo visitante
     é cliente, muita gente só está curiosa).
   - Fotos/vídeos reais de treino (ver seção 10 sobre direção visual e
     consentimento de imagem).
   - (O cliente considerou colocar aqui também avaliações/depoimentos e "um
     pouco da nossa história" — mas depois, ao repensar a estrutura, o time
     sugeriu não colocar isso na página principal e sim como conteúdo mais
     introdutório dentro de cada landing page específica. Recomendo validar
     com o cliente qual das duas versões prevaleceu.)

3) DIVISÃO ENTRE AS DUAS MARCAS
   - Dois blocos/botões grandes: "One-to-One" e "PKZ".
   - Ao clicar (ou passar o mouse), efeito de transição que muda a cor —
     ideia explícita do time, aprovada pelo cliente.
   - Cada bloco leva à landing page específica daquela marca.

4) TEXTO CURTO DE DEFINIÇÃO DE CADA MARCA
   O cliente foi explicitamente solicitado a fornecer, para cada marca, uma
   frase de 2 a 3 linhas para aparecer junto a cada bloco/seção no hub (ver
   seção 7 — o texto do One-to-One já foi fornecido pelo cliente; o de PKZ
   ainda está pendente de fechamento final).



================================================================================
5. LANDING PAGE — ONE-TO-ONE
================================================================================

Estrutura sugerida (mistura o que foi dito nas duas reuniões):

1) Hero temático de One-to-One — vídeo/imagem de treino de musculação/
   personal, com o WhatsApp específico do One-to-One visível aqui.
2) Tagline oficial já definida pelo cliente (ver seção 7).
3) Explicação da metodologia: treino individualizado, foco em aparelhos e
   configuração, para todas as idades (17 a 90 anos), qualquer objetivo.
4) FAQ específico (metodologia de treino, valores, horários — ver seção 8).
5) Seção "professores" (o cliente topou a ideia, mas pediu que ficasse aqui,
   na página específica, e não na página inicial/hub): foto de cada
   professor, nome, anos de experiência, especialidade.
6) Depoimentos/avaliações de alunos.
7) Chamada para login/cadastro → entra no Portal do Aluno (seção 11).



================================================================================
6. LANDING PAGE — PKZ
================================================================================

Estrutura sugerida:

1) Hero temático de PKZ — vídeo/imagem de treino esportivo/infanto-juvenil,
   com o WhatsApp específico do PKZ visível aqui.
2) Tagline/definição de PKZ (a fechar — ver seção 7 e seção 16).
3) Explicação do "sistema complexo" e do público (7 a 15 anos), reforçando o
   exemplo do piloto de kart como ilustração de como a metodologia se adapta
   a qualquer esporte.
4) Explicação resumida do processo do atleta: avaliação (16 testes) →
   cronograma de treino do mês → treinos com relatório → reavaliação mensal
   → gráfico de evolução.
5) FAQ específico (mesma lógica da seção 8, adaptada ao público de pais).
6) Seção "professores"/especialistas (mesma lógica da página do One-to-One).
7) Depoimentos/avaliações (idealmente de pais, já que o público real que
   decide/paga costuma ser o responsável, não a criança).
8) Chamada para login/cadastro → entra no Portal do Atleta (pais/
   responsáveis) (seção 11).



================================================================================
7. TEXTOS JÁ DEFINIDOS PELO CLIENTE (usar como estão)
================================================================================

O próprio Henrique chegou a rascunhar, com ajuda de IA (usou o próprio chat),
uma definição para o One-to-One e leu para o time durante a reunião. Esse
texto pode ir direto para o site:

  "One to One: treinamento individualizado para potencializar o que torna
  você único."

Ele complementou (esse trecho da gravação ficou um pouco impreciso):
o conceito é que a tecnologia e a metodologia da casa servem tanto para
amadores quanto para não amadores, com o objetivo de transformar potencial
em performance — e que cada marca representa "o que somos" individualmente,
mas juntas formam a empresa como um todo.

Para PKZ, o cliente NÃO chegou a fechar, nas gravações disponíveis, uma
frase equivalente de 2-3 linhas. Isso ficou como pendência (ver seção 16).
Sugestão minha, só como ponto de partida para validar com ele (não é uma
frase dita por ele) — algo no mesmo espírito do texto do One-to-One:

  "PKZ: metodologia de alto rendimento que transforma jovens atletas em
  versões mais fortes, rápidas e completas de si mesmos, dentro do esporte
  que escolheram praticar."



================================================================================
8. PERGUNTAS FREQUENTES (FAQ) PARA O SITE
================================================================================

Estas são, segundo o próprio cliente, as dúvidas que mais chegam por
WhatsApp. Ele foi bem específico sobre quais devem ou não aparecer
abertamente no site (ver seção 9 sobre preço).

1) "Como funciona o treinamento de vocês?"
   - Resposta-base: metodologia própria que combina valências físicas +
     lógica do esporte específico do aluno/atleta + a metodologia central da
     casa, adaptável a qualquer modalidade esportiva (inclusive hipotéticas
     ainda não atendidas, como um piloto de kart).

2) "Quais são os valores / como funciona o pagamento?"
   - Ver seção 9 — recomendação do próprio cliente é NÃO detalhar valores
     exatos publicamente no FAQ.

3) "Quais são os horários de funcionamento?"
   - Dúvida recorrente ("isso acontece pra caramba", nas palavras do
     cliente) — deve ter resposta clara e visível.

4) "Vocês atendem [esporte específico, ex.: kart]?"
   - Nunca aconteceu na prática, mas o cliente quer que o site já deixe
     claro que a metodologia é flexível e se adapta a qualquer esporte —
     boa oportunidade para reforçar o diferencial da casa.

Sugestão: no PKZ especificamente, também vale antecipar no FAQ (ou em texto
de apoio) a explicação de por que um gráfico de evolução pode "cair" mesmo
quando o atleta melhorou — ver o exemplo da simetria de salto na seção 11.10,
porque essa é uma dúvida real que pais têm ao olhar números soltos.



================================================================================
9. ESTRATÉGIA COMERCIAL: COMO TRATAR PREÇO NO SITE
================================================================================

Esse ponto foi discutido em detalhe e a orientação do cliente é bem clara:

- Existe um valor "tabulado" de referência: R$ 1.800 pelo pacote principal
  (que inclui, potencialmente, mais de um serviço/empresa — ver seção 13).
- Esse valor é flexível para cima e para baixo dentro de um teto máximo,
  dependendo do que a pessoa quer incluir. Exemplos citados pelo próprio
  cliente:
    * Não quer acompanhamento com psicólogo → valor diminui.
    * Quer treinar 2x/semana em vez de 3x/semana → valor diminui.
    * Retirar outros itens do pacote → valor diminui.
- Decisão do cliente: NÃO expor o valor exato como uma "pergunta frequente"
  fixa no site. Motivo, nas palavras dele: colocar o preço solto "pode até
  acabar espantando" — principalmente quem não é da Barra da Tijuca (para
  quem já mora perto, R$ 1.800 não impressiona tanto, porque há opções mais
  caras na região; para quem vem de fora, o deslocamento somado ao valor
  intimida).
- Estratégia preferida: atrair a pessoa para conhecer o trabalho primeiro
  (aula experimental), e só depois apresentar o valor junto com o "pitch" —
  mostrando o valor percebido/atribuído do serviço antes de reduzir tudo a um
  número. Nas palavras do cliente: "a gente prefere que a pessoa conheça o
  nosso trabalho, porque aí consegue ver o valor atribuído, não o valor que
  vai ser quantificado através da espécie [do dinheiro]."

Recomendação de conteúdo: o site pode ter uma página "Planos" (já prevista
no menu) que fale em termos de pacotes/benefícios e chame para agendar uma
aula experimental ou falar no WhatsApp para montar o pacote sob medida — sem
listar tabela de preço fechada publicamente.



================================================================================
10. DIREÇÃO VISUAL E DE CONTEÚDO AUDIOVISUAL
================================================================================

Diretrizes explícitas dadas pelo cliente:

- Vídeo é preferível a foto estática sempre que possível, especialmente no
  hero da home ("se quiser, se for animado então... seria mais legal").
  Eles já têm vídeos corporativos prontos (formatos diagonal e vertical) que
  podem ser atualizados/reaproveitados.

- Referência estética dada pelo próprio time e aprovada pelo cliente: efeito
  parecido com a logo de abertura dos filmes da Marvel — várias cenas de
  treino simultâneas ao fundo, com opacidade baixa, por trás do texto/
  conteúdo principal.

- Cuidado explícito do cliente: não "personificar" demais a empresa nele
  próprio (Henrique). Ele prefere fotos/vídeos mais conceituais — mostrando
  a ação de treino, com pelo menos a camisa/uniforme da marca aparecendo —
  em vez de fotos centradas nele como pessoa/rosto principal da marca.

- Uso de imagem de alunos/atletas reais: precisa de autorização/consentimento
  prévio dessas pessoas (ponto levantado pelo próprio time e confirmado pelo
  cliente — "a gente tem facilidade" para conseguir essa autorização, já que
  são alunos da casa).

- Sites citados como referência de inspiração de estrutura (não de
  identidade visual em si, mas de forma de contar a história rolando a
  página, seção por seção): Nubank e Apple. A lógica: cada seção "instiga"
  a pessoa a descer e descobrir mais, ao invés de entregar tudo de uma vez.

- Importante: qualquer mockup/wireframe mostrado ao cliente durante essas
  reuniões foi tratado pelo próprio time como "meramente ilustrativo" — ou
  seja, nenhuma cor, fonte ou leiaute específico ali deve ser tomado como
  decisão final de design, apenas como referência de estrutura/organização
  de conteúdo.

- Recado direto do coordenador Pedro sobre a importância disso tudo: "a
  gente entende as nossas demandas, que elas são gigantes, mas a gente
  talvez falte um pouco de glamour nessas apresentações... precisamos que a
  nossa marca seja enxergada de uma forma mais coesa, palpável e funcional."
  Ou seja: o principal ganho esperado com o site/novo sistema é elevar a
  percepção visual da marca, sem perder a robustez funcional que já existe
  hoje (ainda que de forma tosca) no aplicativo interno.



================================================================================
11. PORTAL DO ALUNO/ATLETA (ÁREA LOGADA) — REQUISITOS FUNCIONAIS
================================================================================

Esta seção reúne tanto o que já existe hoje no aplicativo interno (feito
pelo Arthur) quanto o que o cliente pediu para melhorar. A ideia é usar o
que já funciona como base e resolver os problemas relatados.

11.1 Cadastro e login
--------------------------------------------------------------------------------
- Botão de "Cadastro" já previsto no menu principal do site.
- Ao se cadastrar, o aluno/responsável gera login e senha.
- Duas áreas de login separadas conceitualmente: "portal adulto" (One-to-
  One) e "portal atleta" (PKZ, geralmente acessado pelos pais/responsáveis).

11.2 Perfil / "pasta do aluno" (já existe hoje, migrar e melhorar)
--------------------------------------------------------------------------------
Hoje a pasta do aluno no app atual contém:
- Cadastro (dados básicos do aluno).
- Créditos (ver 11.3).
- Agenda (dias em que já treinou / dias em que vai treinar).
- Frequência.
- Arquivos anexos (ex.: laudos/avaliações externas, como uma avaliação de
  fisioterapia que não é gerada pelo próprio sistema — hoje eles anexam
  manualmente; seria bom manter essa função).
- Relatórios (de treino e de teste físico).

11.3 Sistema de créditos
--------------------------------------------------------------------------------
- Cada aluno tem uma cota de créditos semanal (exemplo citado: 5 créditos
  por semana).
- Os créditos são renovados no fim de semana e NÃO são cumulativos (o que
  não foi usado na semana não passa para a próxima).

11.4 Agendamento
--------------------------------------------------------------------------------
Este foi apontado como o foco principal do software da empresa até hoje, e
o ponto onde eles já sentem mais confiança no que construíram — mas ainda
querem evoluir.
- Objetivo central, validado por feedback real de alunos: dar autonomia
  total para o aluno ver vagas disponíveis e marcar/desmarcar sozinho, sem
  precisar mandar mensagem toda hora (muitos alunos relatam ficar "sem
  graça" de remarcar repetidamente por WhatsApp por causa de rotina
  corrida).
- Capacidade por horário:
    * One-to-One: até 3 alunos por professor, por horário (segundo o
      professor Eduardo).
    * PKZ: até 6 atletas por horário (treino simultâneo em grupo).
- A agenda geral (visão da equipe) pode ser filtrada por estúdio: só PKZ, só
  One-to-One, ou todos juntos.
- Fluxo do professor: seleciona o profissional responsável, confirma a
  sessão, marca presença do aluno — só depois de marcar presença é que a
  opção de preencher o relatório daquela sessão é liberada.

11.5 Fila de espera e notificações de vaga
--------------------------------------------------------------------------------
- Pedido explícito do cliente: um sistema de fila de espera claro para quando
  não há vaga no horário desejado.
- Ao notificar alguém da fila que abriu uma vaga, considerar o tempo de
  deslocamento até o local (exemplo dado: um aluno que mora no Recreio dos
  Bandeirantes consegue chegar em cerca de 10 minutos) — o cliente sugere um
  prazo de aviso de 10 a 20 minutos de antecedência para a pessoa conseguir
  chegar.
- Esse mesmo prazo deve orientar a política de quanto tempo antes a pessoa
  ainda pode remarcar ou cancelar um agendamento.

11.6 Lembretes via WhatsApp
--------------------------------------------------------------------------------
- Pedido explícito (Eduardo): enviar mensagem automática de WhatsApp
  confirmando/lembrando o agendamento feito, especialmente quando marcado
  com bastante antecedência (exemplo citado: aluno agenda no domingo para
  terça-feira às 18h — mensagem de lembrete evita esquecimento).
- O lembrete deve indicar dia, horário e o serviço agendado (ex.: musculação,
  fisioterapia, nutricionista — reforça que o "pacote" pode incluir mais de
  um tipo de atendimento, não só treino físico).

11.7 Relatórios de treino (pós-sessão)
--------------------------------------------------------------------------------
- Preenchidos pelo professor logo depois da sessão (hoje é tratado como
  obrigatório).
- Os campos do relatório mudam dependendo do tipo de sessão — o time já
  diferenciou os campos entre o estúdio geral (One-to-One) e o treino de
  atletas (PKZ), justamente para o preenchimento ser rápido no dia a dia do
  professor.
- Exemplo real de relatório preenchido (One-to-One): objetivo da sessão
  (força/hipertrofia), grupo muscular trabalhado (membros inferiores/perna),
  intensidade (moderada), desempenho dentro do esperado, dor/desconforto
  (sim/não), conduta sugerida para a próxima aula.
- Depois de salvo, o próprio aluno passa a ter acesso a esse relatório e ao
  histórico dos últimos treinos — transparência para quem paga.
- Existe também uma avaliação do aluno sobre o professor/aula (mão dupla),
  para manter um ciclo de feedback constante.

11.8 Campo "Observação relevante" — recurso crítico, destacar na prioridade
--------------------------------------------------------------------------------
Este foi um dos pontos mais reforçados nas duas reuniões, tanto pelo
coordenador Pedro/professor Eduardo quanto na conversa específica sobre o
site:
- Precisa existir um campo específico no relatório para anotar qualquer
  informação relevante para a PRÓXIMA sessão — por exemplo, "sentiu dor na
  cadeira extensora, atenção com exercícios de quadríceps" ou "treinou com
  ênfase em salto ontem, hoje focar em outro objetivo".
- O pedido mais forte (repetido em ambas as reuniões): essa observação
  precisa aparecer de forma automática e visível DIRETO na tela de
  agendamento/agenda — não deve depender do professor lembrar de abrir o
  relatório completo do aluno para descobrir isso manualmente.
- Motivo prático citado por Eduardo: com vários alunos por dia e pouco tempo
  entre um atendimento e outro, o professor muitas vezes nem tem tempo de
  procurar o nome do aluno e abrir o histórico — e o próprio aluno também
  nem sempre lembra o que treinou no dia anterior. Ter esse resumo já visível
  na agenda evita repetir treino ou ignorar uma dor relatada.
- Ideal, segundo o cliente: ao lado do nome do aluno/atleta agendado,
  mostrar um resumo rápido de "o que foi treinado na última sessão" e
  "observações relevantes", com opção de abrir o relatório completo se
  precisar de mais detalhe.
- Isso vale tanto para o One-to-One quanto, especialmente, para o PKZ — já
  que ali é comum o mesmo atleta ser atendido por professores diferentes em
  dias diferentes, cada um com seu estilo dentro da metodologia central
  (o próprio cliente compara isso a linguagens de programação diferentes
  chegando ao mesmo resultado).

11.9 Testes físicos e reavaliação (PKZ)
--------------------------------------------------------------------------------
- Problema histórico (hoje já resolvido parcialmente no app atual, mas vale
  manter/reforçar): antes, o controle de quando cada aluno estava "vencendo"
  o prazo para reavaliação era feito manualmente em planilha — gerava atraso
  e prejudicava a percepção dos pais sobre a evolução, mesmo quando o treino
  em si estava indo bem.
- O sistema atual já identifica quem está com teste atrasado, e já sabe
  diferenciar, no dia agendado, se aquela sessão deve ser um "treino" normal
  ou um "teste" de reavaliação.

11.10 Gráficos de evolução física — como apresentar (ponto muito detalhado
pelo cliente)
--------------------------------------------------------------------------------
- Referência usada pelo próprio cliente, duas vezes, em ambas as reuniões:
  o modelo de relatório de laboratórios de exame (ele cita o Sérgio Franco)
  — quando você repete um exame ao longo do tempo, o laboratório mostra um
  gráfico de evolução do marcador, não só a comparação entre dois pontos
  isolados.
- Problema do sistema atual: só é possível comparar ponto a ponto (ex.:
  teste 1 vs. teste 4), perdendo a visão do que aconteceu nos testes 2 e 3
  no meio do caminho. O cliente prefere mostrar a linha do tempo completa.
- ALERTA IMPORTANTE levantado pelo próprio cliente: um gráfico com só os
  números pode passar uma mensagem errada se não vier acompanhado de
  contexto. Exemplo real contado por ele: um atleta pulava 3,58 m com uma
  perna e 4,50 m com a outra (assimetria grande). Na reavaliação seguinte,
  passou a pular 2,80 m com as duas pernas igualmente. Olhando só o número,
  parece que o desempenho caiu — mas na verdade o atleta corrigiu uma
  assimetria grave, o que é uma melhora real e mais importante do que saltar
  mais alto de forma desequilibrada. "Se você botasse só isso no gráfico, o
  pai ia ficar assustado."
- Solução proposta e validada com o cliente: todo gráfico de evolução deve
  vir acompanhado de uma aba/seção de "observações" explicando o contexto
  dos números — não apenas o número cru.
- Ideia de automação (desejo explícito do cliente, ver também seção 12):
  usar IA para gerar automaticamente essa análise textual a partir dos
  parâmetros de cada teste, cruzando 3-4 amostragens e explicando o que
  aconteceu (ex.: "o atleta melhorou X, mas por causa da correção de Y") —
  com uma opção de edição manual pela equipe, caso a IA erre.
- Ideia visual ainda em aberto/decisão não fechada: representar os atributos
  do atleta de forma mais lúdica/didática para os pais, no estilo dos
  atributos de jogador em jogos de futebol (referência citada: FIFA) — uma
  visualização tipo "card de atributos" em vez de tabela de números. O
  próprio time descreveu isso como algo "que a gente ainda está decidindo".

11.11 Cobrança e pagamentos
--------------------------------------------------------------------------------
- Hoje é um ponto fraco: a cobrança é feita por fora, por uma funcionária,
  usando uma plataforma de terceiros com identidade visual diferente da
  empresa. Não está integrada ao aplicativo/site.
- Pedido do cliente: uma área de cobrança dentro do portal do aluno, onde
  ele possa:
    * ver se as mensalidades estão em dia;
    * ver a data de vencimento;
    * ver a forma de pagamento cadastrada;
    * trocar a forma de pagamento (ex.: sair do débito e ir para cartão de
      crédito) de forma autônoma, sem precisar pedir para a equipe.
- Motivação, nas palavras da equipe: "a gente quer dar autonomia" — mesmo
  princípio usado no agendamento.



================================================================================
12. INTELIGÊNCIA ARTIFICIAL: ONDE E COMO USAR
================================================================================

A empresa já usa IA de forma bem intensa no dia a dia (hoje via ChatGPT e
também via Claude), e tem clareza sobre onde isso ajuda e onde já deu
problema. Vale considerar isso no desenho técnico do site/sistema:

- Uso atual: organizar e tabular os resultados dos 16 testes físicos por
  categoria de idade; gerar relatórios de teste em formato de texto e depois
  em formato de dashboard/gráfico.
- Problema já enfrentado: ao pedir para a IA gerar um relatório visual com
  foto do aluno, ela por vezes trocou o rosto de uma pessoa pelo de outra
  (ex.: relatório do aluno "Johnny" saiu com o rosto do próprio Henrique).
  Por isso, hoje eles evitam colocar foto em relatórios gerados por IA.
- Desejo principal do cliente para o novo sistema: eliminar a necessidade de
  "conversar" manualmente com a IA toda vez (copiar dados, escrever prompt,
  revisar). O ideal é que, ao inserir os dados de um aluno específico no
  sistema, o relatório/gráfico com a análise em texto seja gerado
  automaticamente — com uma tela de edição manual disponível para a equipe
  corrigir eventuais erros da IA antes de liberar para o cliente final.
  Nas palavras dele: "quanto mais automatizar, de verdade, pra gente seria
  melhor."
- Uso futuro/aspiracional (menos prioritário, mas vale registrar): análise
  de desempenho esportivo (scout) a partir de vídeo de jogos — hoje feito
  100% manualmente (assistindo partida por partida e marcando manualmente
  passes certos/errados, finalizações certas/erradas etc.), o que consome
  um tempo enorme da equipe, inclusive tirando professores da função de dar
  aula. O coordenador Pedro pediu explicitamente ajuda da equipe de
  desenvolvimento para pensar em formas de tornar esse processo mais
  autônomo e menos manual (ver seção 13).



================================================================================
13. SERVIÇOS ADICIONAIS QUE PODEM APARECER NO SITE
================================================================================

Além do treinamento físico em si, o "pacote principal" (ver seção 9) pode
incluir outros serviços — o site deveria deixar isso visível, mesmo sem
detalhar preço:

- Fisioterapia
- Nutrição
- Psicologia (citado como item opcional dentro do pacote)

Além disso, existe um serviço adicional de análise de desempenho esportivo e
scout (hoje mais focado em futebol), oferecido de forma manual e trabalhosa.
Vale considerar destacá-lo como um diferencial de serviço da PKZ no site,
com a ressalva de que, tecnicamente, a própria empresa ainda está buscando
uma forma de tornar esse processo mais eficiente/automatizado — não é
necessariamente algo para prometer como "recurso automático" no site agora,
mas pode aparecer como um serviço existente ("análise de desempenho e
scout esportivo").



================================================================================
14. O QUE JÁ EXISTE NO APP ATUAL (HERANÇA A APROVEITAR)
================================================================================

Resumo do que o aplicativo interno (feito pelo Arthur) já faz hoje, para não
reinventar o que já funciona — só melhorar a experiência e o visual:

- Dashboard com número de alunos ativos, atividades do mês, treinos feitos.
- Obrigatoriedade de relatório de treino ao final de cada sessão.
- Avaliação mútua aluno-professor.
- Pasta do aluno (cadastro, créditos, agenda, frequência, arquivos anexos,
  relatórios).
- Sistema de créditos semanais não cumulativos.
- Identificação automática de quem está atrasado para reavaliação física.
- Agenda geral filtrável por estúdio (PKZ / One-to-One / todos).
- Fluxo de marcação de presença → liberação do relatório.
- Campo de observação relevante para a próxima sessão.
- Anexo de laudos/avaliações externas (ex.: fisioterapia).

O que falta/precisa melhorar (na visão da própria equipe do cliente):
- Visual "sem glamour", pouco coeso com a marca.
- Observações relevantes enterradas — exigem busca manual em vez de
  aparecerem direto na agenda.
- Nenhuma área de cobrança/pagamento integrada.
- Relatórios de teste físico muito numéricos, difíceis de interpretar para
  quem não é da área.
- Comparação de testes só ponto a ponto, sem visão de linha do tempo
  completa.
- Análise de vídeo/scout esportivo 100% manual.



================================================================================
15. GLOSSÁRIO DE TERMOS DO CLIENTE
================================================================================

- Valências físicas: capacidades físicas básicas trabalhadas no treino
  (força, velocidade, agilidade, mobilidade etc.), a base da metodologia,
  adaptadas conforme o esporte de cada aluno/atleta.
- Sistema complexo: metodologia própria do PKZ que treina o atleta através
  de movimentos funcionais que reproduzem as exigências reais do esporte
  praticado, em vez de isolar grupos musculares separadamente.
- Mesociclo / microciclo: termos de periodização esportiva — o mesociclo é o
  planejamento do mês; os microciclos são os blocos semanais dentro dele.
- Aula experimental: aula de apresentação oferecida antes de fechar
  pacote/valor, parte da estratégia comercial (seção 9).
- Pacote principal: pacote de R$ 1.800 (valor de referência, flexível) que
  pode reunir mais de um serviço (treino + fisioterapia + nutrição +
  psicologia), ajustável para cima ou para baixo.
- Portal adulto / Portal atleta: nomes de trabalho usados para as duas áreas
  logadas (One-to-One e PKZ, respectivamente).
- Observação relevante: campo do relatório de treino dedicado a informações
  que devem ser repassadas para a próxima sessão/próximo professor.



================================================================================
16. PONTOS EM ABERTO — CONFIRMAR COM O CLIENTE
================================================================================

Itens que, pelas gravações disponíveis, ainda não tinham uma decisão
fechada — recomendo validar diretamente com o Henrique antes de finalizar:

1. Tagline final de 2-3 linhas para PKZ (o One-to-One já foi fechado pelo
   cliente; o de PKZ ficou pendente — ver seção 7).
2. Ordem exata das seções do hub: se "avaliações" e "um pouco da nossa
   história" ficam na página inicial (hub) ou dentro de cada landing page
   específica — a conversa oscilou entre as duas opções ao longo da reunião.
3. Formato final da visualização de atributos do atleta nos gráficos de
   evolução (linha do tempo tradicional vs. formato "card de atributos" ao
   estilo de jogo — ainda "em decisão" segundo o próprio time).
4. Lista completa dos 16 testes físicos do PKZ (só uma amostra foi citada
   nas gravações).
5. Se a frente de intercâmbio internacional citada por Henrique deve virar
   conteúdo institucional no site ou não.
6. Confirmar se a capacidade de "6 atletas por horário" é realmente
   específica do PKZ (foi dito em um trecho separado, sem contexto explícito
   de qual marca).
7. Nome real da ferramenta/sistema interno mencionado de forma pouco clara
   na gravação (pode ser útil para mapear integrações futuras).



================================================================================
17. CHECKLIST-RESUMO FINAL
================================================================================

PÁGINAS
[ ] Hub (página inicial única, com as duas marcas)
[ ] Landing page One-to-One
[ ] Landing page PKZ
[ ] Página "Planos" (sem tabela de preço fechada)
[ ] Portal do aluno (One-to-One)
[ ] Portal do atleta/responsável (PKZ)

CONTEÚDO/COPY
[ ] Tagline One-to-One (pronta, ver seção 7)
[ ] Tagline PKZ (pendente, ver seção 16)
[ ] Texto "quem somos" institucional
[ ] FAQ (metodologia, valores — sem número fechado, horários)
[ ] Seção professores (foto, nome, anos de experiência, especialidade)
[ ] Depoimentos/avaliações

FUNCIONALIDADES DO PORTAL
[ ] Cadastro/login
[ ] Agendamento com visualização de vagas em tempo real
[ ] Fila de espera com notificação considerando tempo de deslocamento
[ ] Lembretes automáticos via WhatsApp
[ ] Relatório de treino pós-sessão (campos diferentes por marca)
[ ] Campo "observação relevante" visível direto na agenda
[ ] Avaliação mútua aluno-professor
[ ] Gráfico de evolução em linha do tempo (não só ponto a ponto), com aba de
    observações/contexto
[ ] Geração assistida por IA de relatórios/gráficos, com edição manual
[ ] Área de cobrança e pagamento (status, vencimento, troca de forma de
    pagamento)
[ ] Upload de laudos/avaliações externas

IDENTIDADE VISUAL
[ ] Vídeo (preferencialmente) no hero da home
[ ] Efeito de cenas de treino ao fundo com baixa opacidade
[ ] Fotos conceituais (não centradas na figura do fundador)
[ ] Autorização de imagem para alunos/atletas usados em fotos e vídeos
[ ] Transição de cor ao selecionar One-to-One / PKZ

================================================================================
FIM DO GUIA
================================================================================
