@def title = "Causalidade nas ciências"
@def tags = ["syntax", "code"]

~~~
<a name="causalidade"></a>
~~~
# Causalidade e Ciência

## Debates nas redes sociais

Recentemente, me deparei com um texto nas redes sociais ( https://www.instagram.com/p/CknajL0NX9r/ ), publicado pelos colegas Léo Avila ( https://www.instagram.com/tudosobredor/ ) e Leo Costa ( https://www.instagram.com/leo_costa_pbe/ ). O título chamou a minha atenção devido à afirmação categórica de abertura:  

"Não existe dor de causa emocional: entenda os motivos". O texto sugere uma possível confusão entre causalidade e correlação, sugerindo um papel modulador para as emoções. Apesar de trazer mensagens e informações úteis, achei a mensagem principal muito radical e dotada de possíveis mal-entendidos.
Fiz um breve comentário: "Texto equivocado". Para minha surpresa, o autor respondeu com uma leve ironia, desafiando-me a escrever uma versão própria, que ele publicaria. Decidi aceitar o "desafio". Lembrando da [última vez](https://medium.com/d-van/my-study-is-much-bigger-than-yours-87b9d802d3f4) em que algo parecido aconteceu, precisei escrever [simulações](https://github.com/EBHbr/meta-res) para demonstrar um ponto. Apesar do trabalho envolvido, gosto de participar de discussões acadêmicas. São mais raras do que deveriam nos veículos clássicos de publicação (jornais revisados por pares) e as redes sociais parecem contribuir para mudar isso. Bom, vamos ao ponto.  

## Armadilhas causais

A noção de causalidade costuma ser apresentada sem uma abordagem adequada das bases filosóficas necessárias.  Como esperado de um tema popular, existem controvérsias e mal entendidos.  

Existe uma razão para o conceito ser bastante discutido e instrumentalizado nas ciências de saúde. Em geral, estamos interessados em intervir para mudar um desfecho negativo ou neutralizar fatores de influencia negativa. Diante de um paciente com síndrome coronariana aguda, é vantajoso saber que a perfusão inadequada do miocárdio está causando os sintomas. Revertendo a "causa", mudamos também o destino daquele indivíduo. Aqui, "causa" está entre aspas, pois diversas armadilhas cercam o construto de causalidade.  

Ainda que seja instrumentalmente útil, basta um breve descuido para chegar a conclusões equivocadas. Em especial, recomendo que o uso dessa abstração seja restrito a um certo paradigma experimental. Como mostra o caso específico que motivou esse texto, elaborações mais gerais podem ser fonte de erros.  

Por exemplo, é válido dizer que, num estudo empírico, reverter uma determinada condição **causou** uma redução no número de desfechos. Porém, na maioria das vezes, é errado dizer genericamente que a condição é causa do desfecho. Vamos entender melhor este aparente paradoxo a seguir. 

## Diferentes noções de causalidade

O primeiro ponto que devemos entender: existem múltiplas definições para causalidade. Algumas abstrações são puras ao ponto de evitar essa confusão. O mais proverbial exemplo está em entidades tratadas pela matemática, como números reais, categorias e conjuntos. Ainda que a definição varie conforme aplicações, a ideia fundamental é basicamente única. Em contraposição, causalidade é uma ideia relativamente heterogênea na filosofia.  

Uma das primeiras concepções surge com Aristóteles, que define causalidade em quatro tipos de explicação: matéria, forma, eficiente (agente) e final (propósito). Este texto não se propõe a explicar o desenvolvimento histórico do termo. As referências  ao final deste artigo indicam as entradas sobre causalidade na física e na metafísica da enciclopédia Stanford de filosofia.  

Para esclarecer a confusão, considero necessário falar de três perspectivas: (1) Causalidade apoiada sobre o contrafactual, uma concepção muito usada nas ciências de saúde; (2) Os diferentes níveis de causalidade propostos por Tinbergen na etologia (estudo do comportamento animal); (3) As críticas de Ernst Mach e Bertrand Russell à causalidade como construto, revitalizadas por contemporâneos (Neo-Machianos e Neo-Russellianos).   

## Causalidade e contrafactuais

Quando usamos a noção de contrafactuais para falar em causalidade, consideramos o cenário em questão caso o fator relevante fosse removido. A grosso modo, dizemos que um fator A é causa de B se a neutralização/remoção de A anula B. Por exemplo, podemos dizer que o sabor doce no café é causado quando acrescentamos açúcar. No contrafactual, quando removemos a etapa de colocar mel, nosso café se apresenta como amargo.  

Esta definição instrumental é muito importante para as ciências sociais e de saúde e é comumente operacionalizada usando a estrutura teórica antes citada com grafos direcionados e variáveis aleatórias (ver Judea Pearl, 2009). O trabalho recente de Pearl formaliza causalidade para algumas aplicações empíricas. Em específico, essa abordagem usa grafos direcionados (directed acyclic graphs, DAGs) para modelar a relação entre variáveis aleatórias. É um ferramental poderoso para explicar correlações entre medidas empíricas, permitindo o cálculo de efeitos atribuídos a intervenções e fatores de risco em saúde.  

Ainda que apresente uma admirável plataforma para pesquisa científica, é necessário muito cuidado ao utilizá-la.  

Especificamente, é fácil esquecer que a escolha de elementos para esta descrição de realidade é arbitrária. Isto é, ainda que um fator funcione como agente causal num certo modelo concebido, é importante saber que o modelo em si contém elementos que não correspondem ao fenômeno real. Em outras palavras, existe uma variedade infinita de possíveis modelos.  

O mais adequado é pensar em explicações específicas a um contexto. Isto é, falar em causalidade exige que o modelo de realidade usado seja especificado de antemão. 

## "Corra, Lola, corra!" - Efeito borboleta, causalidade em diferentes níveis  e Tinbergen

No clássico cult do cinema alemão "Run Lola Run" (German: Lola rennt, lit. "Lola Runs", 1998), acompanhamos a protagonista em diversas realidades alternativas. Repetidas vezes, a história volta ao início e algo ligeiramente diferente acontece. Por exemplo, numa primeira narrativa, Lola passa por um homem e seu cachorro. Numa realidade alternativa, Lola esbarra neles. O objetivo do filme é mostrar como pequenas alterações na linha do tempo podem ter efeitos enormes a longo prazo. 

A matemática trata sistemas assim como "caóticos", isto é, sistemas nos quais pequenas perturbações nas condições iniciais geram diferenças grandes no estado final. Formalmente, isso é medido através dos expoentes de Lyapunov, mas não queremos ir tão fundo por enquanto. Aqui, basta guardar a dúvida:"poderia o bater de asas de uma borboleta na América do Sul pode causar um furacão no Japão"?

Assim sendo, na maioria dos fenômenos reais, é impossível estabelecer uma relação unívoca entre a complexa realidade e um elemento que abstraímos para elaborar nossa descrição. É possível considerar infinitos fatores cujos contrafatuais anulariam (ou garantiriam) uma observação empírica. Retornando ao caso do café doce, podemos pensar, Aristotelicamente, que o sabor doce tem como causa material a presença de mel. Por outro lado, também podemos pensar em outras "causas" a depender da perspectiva adotada e da ontologia dos elementos que queremos usar. Pensando em dinâmicas sociais, podemos pensar que a "causa" para um café doce na mesa do desjejum é a visita de um parente distante que gosta de tomá-lo assim, enquanto os residentes da casa preferem café amargo. Note que as duas causas não são incompatíveis: não colocar mel (causa material) seria o suficiente (contrafactual) para não termos café doce. Da mesma forma, a ausência do parente distante teria o mesmo efeito. Como colocado anteriormente, a cadeia hipotética de elementos influenciando o desfecho é limitada apenas por nossa imaginação. Um economista pode ainda associar a doçura do café ao preço acessível do mel naquela região. Isto é, preços inacessíveis também configurariam um contrafactual culminando em café amargo. 

Esse pluralismo é a causa (risos) para a concepção aristotélica em diferentes níveis de explicação. Quando pensamos em fisiologia animal, cabe citar Tinbergen, um etólogo que propôs hierarquia semelhante. Ao refletir sobre determinado atributo, Tinbergen coloca 4 níveis de entendimento:
 (1) função adaptativa; (2) história filogenética; (3) mecanismos fisiológicos subjacentes e (4) história do desenvolvimento (ontogenese).  

Pensando sobre as manchas de uma onça pintada, quais as causas para que existam? Podemos dizer que elas existem pois favorecem sobrevivência através de camuflagem (função adaptativa). Também podemos dizer que as onças pintadas são um ramo filogenético de outro felino com manchas parecidas, sendo estas, portanto, uma herança com modificações aleatórias. Sem contradições, podemos dizer que as manchas escuras refletem a luz de maneira diferente porque os pêlos possuem mais pigmentos escuros. Por fim, podemos considerar ainda que as manchas são causadas pela expressão diferencial de genes relacionados à melanina conforme uma cascata molecular específica mediada por hormônios.  

Espero que aos poucos fique claro ao leitor: estabelecer fatores causais em um fenômeno diz mais sobre o seu modelo de realidade do que sobre o fenômeno em si. É o que Norton (um "Neo-Russelliano") chama de causas dominantes. 

Aí reside o erro fundamental do texto dos colegas: afirmações genéricas sobre a existência de dor com causa emocional. Um breve contra-exemplo é capaz de ilustrar o ponto. Suponha que temos um paciente passando por pós-cirúrgico e que, devido à cirurgia, contrações abdominais seja dolorosas. Ao ouvir uma piada, o paciente é tomado por uma emoção de felicidade, gargalha, e ativa o reto abdominal, resultando em dor. Nesta concepção, é óbvio que a dor foi causada por uma emoção e que a dor não existiria num cenário contra-factual sem a piada. Um outro contra-exemplo: em virtude de depressão grave resistente a tratamento, um paciente passa a apresentar sérias restrições de locomoção, tendo dores crônicas em longo prazo. A despeito dos mecanismos físicos intermediários que se instalam, podemos afirmar que o quadro mental (emocional) causou a dor.  

Em ambos os casos, o behaviorista B.F. Skinner reclamaria do uso de mentalismos. Aliás, Skinner gostaria muito dessa discussão. Segundo ele, o uso de construtos mentais (e.g.emoções, pensamentos) não tem lugar na ciência do comportamento. Os behavioristas radicais defendem a construção de um modelo de realidade eliminando tais conceitos do jargão completamente (eliminativismo). Isso não significa que neguem a existência de emoções e pensamentos como fenômenos, mas sim que estes não fazem parte de um modelo de realidade ideal. Note que, ao dizer, "pensamentos não causam comportamento", Skinner não implica que estados mentais estão desatrelados de comportamentos observáveis. Novamente, a escolha de uma ontologia para os fatores causais diz mais sobre o modelo de teórico proposto por Skinner (e.g. ontologia das causas dominantes válidas). Emoções e pensamentos seriam conceitos inadequados, ou pseudo-fenômenos. Essa perigosa conflação de conceitos levou a um mal-entendido entre cognivistas (em especial, Noam Chomsky) e behavioristas que durou (ou dura?) décadas.  

Em específico, certas asserções genéricas e contudentes feitas dentro de um paradigma costumam chocar aqueles alheios ao programa. Isso aconteceu no célebre embate entre Chomsky e Skinner e também no título da publicação que motivou esse texto.

Para um cognivista, é estranho ouvir que a fome não causa o comportamento de buscar alimento. Assim como é estranha para muitos profissionais e pacientes a afirmativa de que emoções não causam dor. 

## Fragilidades da causalidade, Isaac Newton, Ernst Mach e Bertrand Russell

Dando alguns passos para trás, não culpo os colegas pela confusão. Em verdade, esse erro fundamental é presente em discussões acadêmicas de círculos considerados sofisticados. Por exemplo, é comum acompanharmos manchetes e calorosas declarações sobre descobertas contundentes relacionadas à doenças. 

"Descoberta a causa do Alzheimer". "Pesquisadores demonstram que depressão tem causa genética". "A causa da obesidade é genética e não está em hábitos alimentares". "A causa dos transtornos mentais está no cérebro". A lista é imensa. Com certa tristeza, noto que isso sinaliza um fracasso da empreitada científica acadêmica. A aquisição e valorização de detalhes técnicos em diferentes áreas tem fomentado a formação de super-especialistas, com pouco incentivo para entender questões fundamentais. Em contrapartida, muitos incentivos para supervalorizar suas linhas de pesquisa e atuação. Especialmente, quando executadas com auxílio de tecnologia avançada (e.g. biologia molecular, neuroimagem, aceleradores de partícula, etc...)

Nesse sentido, vale um resgate histórico para entender o contexto. De fato, as tradições herméticas que precederam à ciência como conhecemos já têm algo de reducionista. O lema alquímico "solve et coagula" (Dissolver e coagular) remete à ideia de separar entidades em partes menores para entender seu funcionamento. A evolução do reducionismo como forma de abordagem padrão na ciência ficou ainda mais destacada com a cristalização da "causalidade" como abstração importante. Ao passo em que oferece um conjunto de processos padronizados para considerar ideias, a ideia de causa sistematiza estudos e, consequentemente, também pode cegar pesquisadores para uma visão mais abrangente. Então, passa a ser comum subverter os objetivos principais. Restringimos o espaço de modelos da realidade com base numa gramática simplória pautada em causalidade.

O matemático e filósofo Bertrand Russell escreveu, em 1912, o artigo “On the Notion of Cause”, com críticas contudentes à ideia de causalidade para descrever fenômenos físicos. Outro importante polímata, Ernst Mach, foi influente para reconsiderarmos noções clássicas de causalidade. Muitos creditam a ele os fundamentos conceituais que permitiram as descrições pouco ortodoxas advindas da Teoria da Relatividade. 
Os verbetes da enciclopédia Stanford linkados nas referências são uma boa fonte sumarizando os desafios envolvidos em adotar causalidade para a realidade física, conforme postos por filósofos contemporâneos (e.g. Neo-Russellianos, ou Neo-Machianos). Além dos problemas com **causas dominantes** e **definições vagas**, alguns obstáculos para a causalidade incluem as premissas de determinismo, localidade e assimetrias temporais.  

Uma anedota interessante é relacionada à Isaac Newton em seu Principia (Philosophiæ Naturalis Principia Mathematica). Muitos contemporâneos questionaram Newton quanto às razões por trás das propriedades do movimento descritas. Na segunda edição da obra (1713), um ensaio (General Scholium) foi adicionado, contendo o seguinte trecho:   
*I have not as yet been able to discover the reason for these properties of gravity from phenomena, and **I do not feign hypotheses** .* 

**"I do not feign hypotheses"** é mais conhecida na forma em latim, *Hypotheses non fingo*. Cronologicamente, Newton antecede em séculos as discussões mais profundas de Russell sobre causalidade, porém notamos aversão a um reducionismo sobre fatores causais específicos. Ele priorizava outras características, como um modelo descritivo da realidade que trouxesse alta precisão para as medidas, simplicidade e elegância. 

É interessante contrastar suas motivações com a de muitos pesquisadores contemporâneos que trabalham à sombra do paradigma causal em ciência sociais e biológicas. Estes tem como objeto de estudo entidades muito complicadas, incluindo o funcionamento de fenômenos sociais (e.g. dinâmicas economicas) e  biológicos de alta complexidade (e.g. corpo humano). Por um lado, essa é uma premissa razoável para aceitar algum pessimismo quanto à possibilidade de modelos e entendimentos mais globais. Assim, parece adequado aceitar o reducionismo em contextos limitados. 

Em contrapartida, essa premissa é uma desculpa conveniente para abandonar empreitadas intelectualmente difíceis. Ao invés de estudar o fenômeno em sua completude em busca de modelos elegantes, é comum a ocorrência de retratos demasiadamente toscos, que usam robustez de pormenores técnicos para defender conclusões finais dúbias através de conflações semânticas. Em saúde e ciências sociais, essa lacuna costuma ser mascarada com o uso de modelos estatísticos e testes de hipótese  .

Um exemplo proverbial se dá em nosso estudo de caso sobre causalidade.  A título de comparação, os modelos físicos clássicos possuem discrepâncias muito pequenas entre previsões e medidas. Uma equação que errasse em grande magnitude as posições de uma órbita não receberia atenção. Apesar disso, modelos de natureza semelhante passam incólumes em saúde e ciências sociais. O pulo do gato está em fazer uma conflação entre conclusões sobre o modelo e o jargão usado em linguagem natural. 

### Caso exemplo
Como ilustração, farei o papel de advogado do diabo, pensando num modelo que busca defender o fato de que "dor é causada por fatores emocionais". 
Uma estratégia comum é montar um experimento e então fazer uso de modelos estatísticos para testar associações com desfechos. Em nosso experimento imaginário, estimulamos uma reação emocional (e.g. com um vídeo engraçado ou estressor) através de uma condição randomizada (e.g. o vídeo sorteado para o indivíduo pode ser neutro) e medimos se houve resposta de dor nos participantes. 
Podemos levar em conta um dos cenários descritos antes. Supomos que uma parte dos participantes tem lesão prévia de coluna vertebral/medula e adaptações posturais causadas pela evocação de emoções sejam acompanhadas de dor. 
Um modelo estatístico simples geralmente é capaz de capturar essa associação e, através de uma amostra suficientemente grande, podemos declarar com pompa técnica  ( p<0.001; HDI = ....; AIC...; F1 score = ...) que emoções causam dor.  
Dois problemas principais existem aí: (1) conclusões exageradas são tiradas a partir do modelo e (2) há uma conflação entre descrição do modelo e interpretação via linguagem natural. 

Sobre o modelo, boa parte apresenta adequação baixíssima (e.g. R^2 próxima a 0), porém uma amostragem suficientemente grande permite fazer testes de hipótese. Nestes, a magnitude dos efeitos e correlações (e.g. "medição X de emoção numa escala está associada a um aumento Y numa escala de dor") é identificada com uma conclusão mais categórica (e.g. "emoções causam dor"). Em seguida, a hipótese "validada" é apresentada à comunidade leiga e acadêmica como verdade, de forma genérica e fora do contexto experimental.   

Se fôssemos respeitar um alto rigor científico, o trabalho apenas demonstra que é possível associar estatisticamente a evocação de emoções por vídeo ao relato de dor em um grupo de indivíduos. A baixa adequação do modelo para descrever a realidade deveria pesar fortemente na interpretação. Isto é, o modelo não é bom para retratar o fenômeno, que dirá tirar conclusões genéricas sobre causas. 

O que noto frequentemente em discussões acadêmicas é que muita atenção é dada aos pormenores dos modelos e pouca atenção é direcionada a questões mais elementares. Afinal, quais premissas estão por trás do experimento? Que elementos foram elencados para compor o modelo de realidade? É comum também misturar elementos de ontologia completamente diferente (e.g. renda mensal, contagem de hemoglobina, número de filhos, altura, IMC) com base no "poder explicativo" (desempenho dos parâmetros), o que deveria ser realizado com muita cautela.  

Novamente, é com certa infelicidade que digo que boa parte da pesquisa acadêmica contemporânea é conduzida desta maneira. Parte-se do reducionismo (elencar elementos de interesse) para um paradigma experimental padronizado. Em seguida, ajusta-se um modelo estatístico de adequação baixa, porém suficiente para testar hipóteses internas (e.g. "O valor do parâmetro Beta1 neste modelo é diferente de 0"). Por fim, faz-se uma conflação entre afirmação sobre os parametros do modelo e elementos elencados inicialmente para um contexto universal e genérico. O resultado é um verdadeiro "papo de surdo e mudo", com escolas divergentes quanto à **verdadeira** causa do fenômeno. Sob a luz dos argumentos anteriores, sabemos que existem infinitas possibilidades de concepção reducionista (causas dominantes). O leitor deve perceber que a tarefa de descobrir *causas verdadeiras* é [fútil](https://en.wikipedia.org/wiki/Not_even_wrong).

Seria a existência do mel a culpada pelo café doce nas mesas? Talvez a solução seja extinguir essa substância da face da terra. Ou talvez a causa seja o preço acessível demais, então a solução é aumentar impostos sobre o mel. Ou ainda, parentes distantes confraternizando podem estar causando o café adocicado. Nesse caso, melhor recomendar isolamento social. 

E sobre a dor crônica de coluna, qual a causa? Seriam as adaptações evolutivas do Homo sapiens para andar em postura ereta? Seria uma postura inadequada sustentada durante muito tempo no trabalho? Talvez um esforço excepcional realizado durante uma mudança? Mas, daí, a causa seria o esforço ou a falta de fortalecimento muscular prévio? 

Uma ressalva frequente é a de que fenômenos são "multicausais" ou de "causa multifatorial". Entretanto, isso frequentemente expressa a crença subjacente de que seria possível enumerar exaustivamente as possíveis causas para o fenômeno. Como vimos, em verdade, elas são pontencialmente infinitas, limitadas pela nossa imaginação e pelo modelo de realidade escolhido. 

## Considerações finais e uma colher de chá
Uma outra vulnerabilidade do texto citado é tentar fazer afirmações categóricas sobre a não existência de algo. Essa é uma aventura perigosa. 
Ainda que se encontre uma regularidade nas observações (e.g. todas as dores vistas até o momento não tem causa emocional), não é possível extrapolar o caso geral. Esse é o chamado problema da indução.  

De fato, linhas inteiras em filofia da ciência são baseadas nas dificuldades dessas declarações. O falsificacionismo de Karl Popper é apresentado em "Lógica da pesquisa científica" a partir disso. Um exemplo clássico está nos cisnes (aves), os quais eram considerados todos brancos até o achado empírico de cisnes negros.  

Fazer afirmações categóricas sobre a não-existência de entitades físicas é seguro somente quando temos uma impossibilidade lógica flagrante (e.g. não existe cachorro banguela com grandes dentes caninos).  

Sobre o texto dos colegas, dou uma "colher de chá". O texto começa falando em causalidade vs. correlação, e até contextualiza bem o papel das emoções na dor. Por outro lado, a afirmação categórica da manchete foi de mal gosto ao tentar buscar causas genéricas para o fenômeno. Remete a um cartesianismo nada interessante que dificulta um pouco a colaboração entre profissionais atuantes na saúde mental e outros profissionais de saúde. Uma declaração mais parcimoniosa e menos nociva seria de que, ao pensar em etiologias e causas reversíveis para a dor, é mais vantajoso considerar as emoções como moduladoras de um quadro prévio.  

Enfim, ficou claro que sou simpático a Russell e Mach quanto ao uso da noção de causa em ciências. Por um lado, é uma boa abordagem reducionista na operacionalização de certos modelos experimentais. Eu faço uso em [certos contextos](https://www.sciencedirect.com/science/article/abs/pii/S0306460321003166). Por outro lado, não é uma plataforma inspiradora para entender fenômenos em suas características mais fundamentais. Por sua natureza pragmática, muitas vezes, a gramática causal constitui uma barreira entre o pesquisador e a essência mais sutil da realidade.  

Por ignorância, eu costumava desprezar alguns filósofos críticos das estruturas de pesquisa engessadas, como Fayarabend e Russell. Para mim, eram arautos da pseudo-ciência. Abandonar esse pré-conceito e lê-los de cabeça aberta foi fundamental para conceber [uma ideia legal em meu doutorado](https://www.trends.org.br/journal/trends/article/doi/10.1590/2237-6089-2019-0067).

# Referências

Pearl, J. (2009). Causality. Cambridge university press.

Frisch, Mathias, "Causation in Physics", The Stanford Encyclopedia of Philosophy (Spring 2022 Edition), Edward N. Zalta (ed.), URL = <https://plato.stanford.edu/archives/spr2022/entries/causation-physics/>. 
Em especial, a sessão **'2. (Neo)-Russellian Challenges apresenta argumentos contra o uso da causalidade'**. A sessão **3. Interventionist accounts of causation** aborda a concepção de Judea Pearl. 

Gallow, J. Dmitri, "The Metaphysics of Causation", The Stanford Encyclopedia of Philosophy (Fall 2022 Edition), Edward N. Zalta & Uri Nodelman (eds.), URL = <https://plato.stanford.edu/archives/fall2022/entries/causation-metaphysics/>. 

Argôlo, Felipe Coelho. "Invariantes temporais do comportamento na dicotomia Kraepliniana: análise de discurso livre, estados afetivos, experiências psicóticas e possibilidades terapêuticas." (2021).

Sonnert, Gerhard (2005). Einstein and Culture (illustrated ed.). Humanity Books. ISBN 978-1-59102-316-6.

Popper, K. R. (2004). A lógica da pesquisa científica. Editora Cultrix.

Dawid, A. P. (2010, February). Beware of the DAG!. In Causality: objectives and assessment (pp. 59-86). PMLR.


*PS*: Ao longo do texto, evitei tocar em pontos mais controversos da física contemporânea. A título de curiosidade, a existência de entrelaçamento quântico (Spooky action at a distance) e outras bizarrices lançou novos questionamentos sobre a possibilidade de um universo pautado na causalidade entre seus agentes constituintes.  
