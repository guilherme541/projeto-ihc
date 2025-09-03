# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel) e Prof. Dr. Plino Thomaz Aquino Junior.

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Uma Metodologia Baseada em Redes Neurais Profundas e videos de VANTs para Análise de Segurança em Ambientes de Canteiros de Obra na Construção Civil.** sob orientação do Professor **Gabriela Biondi** e desenvolvido pelos seguintes alunos:

- Caio de Souza Conceicão RA: 22.122.033-8
- Guilherme Couto Goms RA: 22.122.035-3
- Lucas Dias Batista RA: 22.122.065-0
- Pedro Henrique Algodoal Pinto RA: 22.122.072-6
- Samir Oliveira Costa RA: 22.122.030-4

## Resumo
Segurança em canteiros de obras é comprometida pela complexa interação entre operários e equipamentos, exigindo monitoramento constante. O desafio está em identificar riscos em tempo real, o que requer análise tridimensional de múltiplas perspectivas aéreas. Para isso, o trabalho propõe uma metodologia inovadora baseada em visão computacional e aprendizado profundo, utilizando drones (VANTs) para analisar vídeos e detectar situações perigosas, emitindo alertas preventivos para evitar acidentes.

## Introdução

- Apresente uma breve descrição.
- Apresente o objetivo.
  
O projeto consiste no desenvolvimento de um sistema de monitoramento de segurança para canteiros de obras, focando na detecção de situações de risco em tempo real através de análise visual automatizada. O sistema utiliza algoritmos de visão computacional e aprendizado de máquina para identificar objetos e pessoas em cenas de construção, analisando vídeos capturados por drones (VANTs) para detectar condições potencialmente perigosas. O objetivo principal é fornecer às empresas de construção civil uma ferramenta capaz de monitorar continuamente as atividades do canteiro, identificar riscos de segurança de forma automatizada, e auxiliar na prevenção de acidentes de trabalho. Além disso, focado na disciplina de Interface Humano-Computador, aumentamos o escopo do projeto para trabalhar também com a análise dos dados capturados e a geração de relatórios a partir destes.

- Apresente o usuário final.
  
Usuário final: Empresas de construção civil, equipes de segurança do trabalho e gestores de obras.

- Apresente os principais benefícios para o usuários.
  
 Redução de acidentes de trabalho através de monitoramento automatizado  
 Otimização da alocação de recursos de segurança baseada em dados reais  
 Identificação proativa de situações de risco antes que se tornem acidentes  
 Melhoria do cumprimento de normas de segurança no canteiro  

- Apresente as funcionalidades.
  
 Detecção e reconhecimento de objetos na cena
 Armazenamento e sincronização de dados
 Geração de relatórios de segurança (não está no escopo do TCC)
 ```diff
! TO-DO
```

- Apresente as tecnologias e ferramentas computacionais utilizadas.
 ```diff
! TO-DO
```

- Apresente o contexto de uso.
  
Canteiros de obras de construção civil onde há necessidade de monitoramento contínuo de segurança, com foco na prevenção de acidentes através de análise de vídeos aéreos.

- O produto ou serviço prevê o desenvolvimento de interface? (Sim/Não)
  
O sistema foi inicialmente concebido para funcionar de forma automatizada, gerando apenas dados para análise posterior, **sem necessidade de interface para o usuário final**.


## Público Alvo

Grupo Específico de Pessoas ou Organizações para as quais este produto ou serviço é direcionado

- Gerentes de Segurança do Trabalho em empresas de construção civil de médio e grande porte
- Engenheiros de Segurança responsáveis pelo cumprimento de normas regulamentadoras
- Gestores de Obras e Projetos que buscam otimizar operações e reduzir custos com acidentes

Público Secundário

- Seguradoras que oferecem cobertura para acidentes de trabalho na construção civil
- Consultorias em Segurança do Trabalho especializadas no setor da construção

Descreva as caracteristicas demográficas, comportamentais, psicográficas ou geográficas deste público alvo que o torna mais propenso a se interessar pelo que está sendo oferecido neste projeto ou serviço.
 ```diff
! TO-DO
```

## Análise de concorrência

1. Identifique os principais concorrentes ou softwares mais utilizados pelo seu público-alvo.
2. Colete informações sobre os concorrentes selecionados.
3. Analise as características e funcionalidades dos concorrentes.
4. Avalie a experiência do usuário (UX).
5. Examine os preços e modelos de negócio.
6. Pesquisa de satisfação do cliente e opiniões.
7. Identifique padrões e tendências no mercado.
8. Elabore relatórios e sumarize os resultados.
9. Extraia pontos positivos e faça recomendações.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

  - Persona primaira ...
  - Persona secundária ...
  - Outras personas ...

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?


<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->
 
## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->


```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
