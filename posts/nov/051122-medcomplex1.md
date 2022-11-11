@def title = "Complexidades em medicina"
@def tags = ["syntax", "code"]

~~~
<a name="medcomplex1"></a>
~~~
# Medicina - Arte e Técnica

## Prefácio 

Este texto é destinado a aspectos relacionados à prática médica. Assume que o leitor possui uma leitura prévia em conhecimentos prévios em Fisiologia Médica (ver Guyton & Hall - Tratado de Fisiologia Médica).  

Anteriormente, fiz a empreitada de escrever um livro sobre análise de dados em ciências emíricas (https://leanpub.com/cienciadados), o que foi gratificante. Diante da ausência de uma fonte que abrangesse alguns temas que considero axiais para a prática médica, decidi iniciar um segundo livro. 

Versão 1 06/11/2022

## Volume 1 - Complexidades da fisiologia humana

### Capítulo 1: Lei de Goodhart e Probabilidade em medicina

A chamada "lei de Goodhart" parte da observação de Charles Goodhart sobre como medidas podem ser enganosas quando passamos a interferir sobre elas.

O princípio é sintetizado pela frase:
"When a measure becomes a targe, it ceases to be a good measure"

E provavelmente apareceu na literatura  no trecho:

"Any observed statistical regularity 
will tend to collapse 
once pressure is placed upon it 
for control purposes."

Goodhart, Charles (1975). 
"Problems of Monetary Management: The U.K. Experience". 
Papers in Monetary Economics. 1. Sydney: Reserve Bank of Australia.

Em medicina, é comum usarmos certas medidas como parâmetro para verificar o estado de um paciente ou o funcionamento de alguns sistema. Por exemplo, no atendimento ao trauma, a pressão arterial é usada para estimar os efeitos sistêmicos de uma perda sanguínea.

Também é comum o processo intuitivo de agir para restaurar valores tidos como normais. No contexto citado, parece natural repor o volume perdido para restaurar valores fisiológicos de pressão arterial, garantindo assim uma boa perfusão.

Refletindo sobre o princípio de Goodhart, podemos perguntar: "será que restaurar pressão arterial normal é realmente benéfico para o organismo?". Há aqui um salto lógico sutil quando interferimos diretamente sobre a medida. Isto ocorre porque esta é apenas um pequeno recorte de um sistema mais complexo. A restauração da medida através de intervenções externas ocorre num cenário artificial. Assim, a medida (e.g. pressão arterial) pode não mais estar indexada à variável de interesse (perfusão tecidual). É o que ocorre nas anemias. Não por condições hidrodinâmicas, mas por causas outras, como uma baixa quantidade de hemoglobina funcional circulando.  
Em última instância, a existência de fenômenos compensatórios não considerados pode causar um efeito inverso ao desejado. Isto é, manter artificalmente algumas condições pode prelcuir a ativação de mecanismos benéficos para contenção ou mesmo ativar outros secundários. 

A resposta fisiológica ainda é, em boa parte, imprevisível aos modelos mecanicistas que temos do organismo humano. Daí vem o uso de ensaios clínicos com amostras e métodos probabilísticos. 

## Conceitos relacionados (Wiki)

Teoria dos jogos (‘Gaming the system’)
Lei de Campbell – Aplicação na sociologia
Efeito Cobra - Incentivos em torno de uma métrica pioram o problema (Oswaldo Cruz e os “ratos de ouro”, Sec XX)
Crítica de Lucas – Em economia, a decisão dos agentes depende das políticas vigentes.	
 	Teoria de Controle
Sistemas caóticos
“Sistemas de 1a ordem” - Pêndulo duplo
“Sistemas de 2a ordem” - Mercado de ações: sensível a previsões feitas

XXX IMAGEM Artigo XXX
Reposição volêmica no trauma

Qual o ponto?
Volume fixo?
Volume correspondente à perda? 
Volume de acordo à resposta?

[...] penetrating injuries [..] have better outcomes with restrictive clear fluid resuscitation policies,permitting a systolic blood pressure (BP) between 60 and 70 mmHg until the patient can be taken to the operating theater [10]. 
[...] [In the context of blunt trauma] A slightly higher systolic blood pressure of 80–90 mmHg is permitted, again, until control in theater is achieved and blood products are available. ## Conceitos relacionados (Wiki)

Teoria dos jogos (‘Gaming the system’)
Lei de Campbell – Aplicação na sociologia
Efeito Cobra - Incentivos em torno de uma métrica pioram o problema (Oswaldo Cruz e os “ratos de ouro”, Sec XX)
Crítica de Lucas – Em economia, a decisão dos agentes depende das políticas vigentes.
        Teoria de Controle
Sistemas caóticos
“Sistemas de 1a ordem” - Pêndulo duplo
“Sistemas de 2a ordem” - Mercado de ações: sensível a previsões feitas

XXX IMAGEM Artigo XXX
Reposição volêmica no trauma

Qual o ponto?
Volume fixo?
Volume correspondente à perda?
Volume de acordo à resposta?

[...] penetrating injuries [..] have better outcomes with restrictive clear fluid resuscitation policies,permitting a systolic blood pressure (BP) between 60 and 70 mmHg until the patient can be taken to the operating theater [10].
[...] [In the context of blunt trauma] A slightly higher systolic blood pressure of 80–90 mmHg is permitted, again, until control in theater is achieved and blood products are available.

