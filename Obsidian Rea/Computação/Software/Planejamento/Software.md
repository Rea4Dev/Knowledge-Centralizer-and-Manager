---
Fonte SDLC: https://www-harness-io.translate.goog/blog/software-development-life-cycle-phases?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc
Fonte SDLC (2): https://youtu.be/mmVXL0LzLks?si=TMQqkNo7Gx6oTTma&t=122
Fonte "Engenharia de Software Roger S. Pressman 9th": https://www.amazon.com.br/Engenharia-software-Roger-S-Pressman/dp/6558040107
---
# O Software

`Fonte "Engenharia de Software Roger S. Pressman 9th"`
> -"Software consiste em: (1) instruções (programas de computador) que, quando executadas, fornecem características, funções e desempenho desejados; (2) estruturas de dados que possibilitam aos programas manipular informações adequadamente; e (3) informação descritiva, tanto na forma impressa quanto na virtual, descrevendo a operação e o uso dos programas."

# Vida Útil do Software - Desgaste x Deterioração
A vida útil do Software e sua deterioração é um tópico amplamente difundido e considerado. Em uma comparação ao Hardware, o autor *Roger S. Pressman* em seu livro "Engenharia de Software: Uma Abordagem Profissional 9th edição" diz:

> -"O software não é suscetível aos fatores maléficos do ambiente que causam o desgaste do hardware. Portanto, teoricamente, a curva da taxa de defeitos para software deveria assumir a forma da “curva idealizada”, mostrada na Figura 1.2.
> ![[Pasted image 20250919132738.png | center | 600]]
> Defeitos ainda não descobertos irão resultar em altas taxas logo no início da vida de um programa. Entretanto, esses defeitos serão corrigidos, e a curva se achata, como mostrado. A curva idealizada é uma simplificação grosseira de modelos de defeitos reais para software. Porém, a implicação é clara: software não se desgasta. Mas deteriora!
>
> Essa aparente contradição pode ser elucidada pela curva real apresentada na Figura 1.2. Durante sua vida, ==o software passará por alterações==. À medida que elas ocorrem, ==é provável que sejam introduzidos erros==, ocasionando o aumento da curva de taxa de defeitos, conforme mostrado na “curva real” (Figura 1.2). Antes que a curva possa retornar à taxa estável original, outra alteração é requisitada, aumentando a curva novamente. Lentamente, o nível mínimo da taxa começa a aumentar – o software está ==deteriorando devido à modificação==.
>
> Outro aspecto do desgaste ilustra a diferença entre hardware e software. Quando um componente de hardware se desgasta, ele é substituído por uma peça de reposição. ==Não existem peças de reposição de software==. Cada defeito de software indica um erro no projeto ou no processo pelo qual o projeto foi traduzido em código de máquina executável. Portanto, as tarefas de manutenção de software, que envolvem solicitações de mudanças, implicam complexidade consideravelmente maior do que as de manutenção de hardware."

# Software Development Life Cycle
Contextualização e generalização das fases do SDLC.

Observação: A depender do autor consultado, a nomenclatura das fases mudará.
## Fase de Planejamento
Primeira etapa do SDLC.

`Parafraseando Fonte SDLC (2)`
> Assim como um casamento sem antes definir o local, orçamento, convidados, menu, decoração e entretenimento se torna caótico, um Software sem passar pela Fase de Planejamento em seu ciclo de vida estará sujeito ao caos.

`Extraído Fonte SDLC`
>-"A etapa inicial do desenvolvimento de software, o Planejamento, envolve a definição do propósito e do escopo do software, assim como a identificação do nosso destino e o planejamento da melhor rota. Descobrimos as tarefas em questão durante essa fase e elaboramos estratégias para uma execução eficiente.
>
>A equipe colabora para entender as necessidades dos usuários finais e os objetivos que o software deve atingir. Basicamente, perguntamos: "Que problema este software resolverá?" e "Que valor ele oferecerá ao usuário?"
>
>Um estudo de viabilidade também ocorre durante a fase de planejamento. Desenvolvedores e equipes de produto avaliam os desafios técnicos e financeiros que podem afetar o desenvolvimento ou o sucesso do software.
>
>Então, o que acontece nesta fase? Documentos importantes, como o Plano do Projeto e a Especificação de Requisitos de Software (ERS), são criados. Esses guias detalham as funções do software, os recursos necessários, [os possíveis riscos](https://www-harness-io.translate.goog/blog/how-to-mitigate-risk-in-ai-software-development?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) e o cronograma do projeto.
>
>A fase de Planejamento promove a comunicação e a colaboração eficazes dentro da equipe. Ao definir funções, responsabilidades e expectativas claras, ela estabelece uma base sólida para um processo de desenvolvimento de software eficiente."

## Fase de Requisitos
Segunda etapa do SDLC.

`Extraído Fonte SDLC (2)`
> -"Esta fase é toda baseada em reunir informações **`detalhadas`** sobre o que o software deve fazer. (...)"

`Extraído Fonte SDLC`
>-"A Fase 2 do SDLC, Análise de Requisitos, busca identificar e registrar os requisitos precisos dos usuários finais. Nesta fase, a equipe busca responder: "Quais são as expectativas dos nossos usuários em relação ao nosso software?". Isso é chamado de coleta de requisitos.
>
>A equipe do projeto coleta informações das partes interessadas, incluindo analistas, usuários e clientes. Eles conduzem entrevistas, pesquisas e grupos focais para entender as expectativas e necessidades do usuário. O processo envolve não apenas fazer as perguntas certas, mas também interpretar as respostas com precisão.
>  
>Após coletar os dados, a equipe os analisa, distinguindo os recursos essenciais dos desejáveis. Essa análise ajuda a equipe a entender as necessidades de funcionalidade, desempenho, segurança e interface do software.
>
>Esses esforços resultam em um Documento de Especificação de Requisitos. Ele descreve a finalidade, os recursos e as funcionalidades do software, servindo como um guia para a equipe de desenvolvimento e fornecendo estimativas de custo, se necessário. Para garantir sua confiabilidade, o documento é validado quanto à precisão, abrangência e viabilidade.
>
>O sucesso da fase de Análise de Requisitos é fundamental para todo o projeto. Se realizada corretamente, resulta em uma solução de software que atende às necessidades dos usuários e supera suas expectativas."

## Fase de Design
Terceira etapa do SDLC.

`Extraído Fonte SDLC`
> -"A fase de Design envolve a construção da estrutura. A equipe de desenvolvimento é responsável pela engenharia de software e define a funcionalidade e a estética do software. Isso, por fim, resulta no produto de software. A ênfase está em definir a estrutura, a navegação, as interfaces de usuário e o design do banco de dados do software. Esta fase garante que o software seja amigável ao usuário e execute suas tarefas com eficiência.
>
> Então, quais tarefas a equipe realiza? As principais atividades incluem a elaboração de diagramas de fluxo de dados, a construção de diagramas de entidade relacionamento e o design de mock-ups de interface do usuário. A equipe também identifica dependências do sistema e pontos de integração. Ela também define as limitações do software, como restrições de hardware, requisitos de desempenho e outros fatores relacionados ao sistema.
>
> O ponto culminante dessas tarefas é um Documento de Design de Software (SDD) exaustivo. Este documento serve como roteiro para a equipe durante a fase de codificação. Ele detalha meticulosamente o design do software, desde a arquitetura do sistema até o design dos dados, e até mesmo as especificações da interface do usuário.
>
> A fase de Design é o elo entre o propósito do software (estabelecido nas fases de Planejamento e Análise de Requisitos) e sua execução (definida na fase de codificação). É uma etapa essencial na criação de um software que funcione de forma eficiente e proporcione uma excelente experiência ao usuário."

## Fase de Codificação
Quarta etapa do SDLC.

`Extraído Fonte SDLC`
> -"A fase de codificação no ciclo de vida de desenvolvimento de software (SDLC) é quando engenheiros e desenvolvedores começam a trabalhar e converter o design do software em código tangível.
>
> Esta fase de desenvolvimento visa desenvolver um software funcional, eficiente e fácil de usar. Os desenvolvedores utilizam uma linguagem de programação apropriada, Java ou outra, para escrever o código, guiados pelo SDD e pelas diretrizes de codificação. Este documento, atuando como um roteiro, garante que o software esteja alinhado com a visão definida nas fases anteriores.
>
> Outro aspecto fundamental desta fase são as revisões regulares de código. Os membros da equipe examinam cuidadosamente o trabalho uns dos outros para identificar quaisquer bugs ou inconsistências. Essas avaliações meticulosas mantêm altos padrões de código, garantindo a confiabilidade e a robustez do software. Esta fase também inclui testes internos preliminares para confirmar a funcionalidade básica do software.
>
> Ao final desta fase, um software funcional ganha vida. Ele incorpora os esforços de planejamento, análise e design das etapas anteriores. Embora possa não ser perfeito, representa um passo significativo em direção a uma solução de software valiosa."

## Fase de Teste
Quinta etapa do SDLC.

`Extraído Fonte SDLC`
> -"Considere a fase de Teste do SDLC como uma rigorosa inspeção de qualidade em uma linha de produção. É quando vulnerabilidades são descobertas. O teste de software envolve uma análise completa do software em busca de bugs ou falhas que possam ter ocorrido durante a codificação. O objetivo é garantir a operação impecável do software antes que ele chegue aos usuários finais. E até mesmo identificar oportunidades de melhoria.
>
> O processo de teste começa com a definição de parâmetros claros, alinhados aos requisitos do software. Isso inclui a identificação das condições necessárias para o software e a definição de diversos cenários para examiná-las. Esta etapa auxilia na criação de uma estratégia de teste eficiente.
>
> Após estabelecer os casos de teste, desenvolvedores e [engenheiros devem testar o software rigorosamente](https://www-harness-io.translate.goog/blog/how-to-implement-testing-in-production?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) . Eles devem conduzir vários tipos de testes, incluindo testes unitários, testes de segurança, testes de integração, testes de sistema e testes de aceitação. Esses testes abrangem desde a análise de componentes individuais até a garantia da operação perfeita de todo o sistema.
>
> Quando um teste revela um bug, ele é documentado em detalhes, observando seus sintomas, método de reprodução e sua influência no software. Esses bugs são então enviados de volta aos desenvolvedores para correção. Uma vez implementadas as correções necessárias, o software retorna à fase de testes para validação. Esse processo é um ciclo de refinamento persistente até que o software esteja em conformidade com todos os parâmetros pré-determinados.
>
> A fase de testes é fundamental para garantir a robustez e a confiabilidade do software."

## Fase de Implantação
Sexta etapa do SDLC.

`Extraído Fonte SDLC`
> -"Após criar um produto com precisão, é hora de apresentá-lo aos usuários, enviando-o para o ambiente de produção. A fase de Implantação envolve a disponibilização do software meticulosamente testado e ajustado aos usuários finais.
>
> Uma estratégia específica é executada para a implantação do software, a fim de garantir o mínimo de interrupção na experiência do usuário. Dependendo do software e do seu público, podemos usar diferentes métodos, como [implantações Big Bang, Blue-Green ou Canary](https://www-harness-io.translate.goog/harness-devops-academy/what-is-a-canary-deployment?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) .
>
> No entanto, a implantação não se resume apenas ao lançamento do software. Trata-se de garantir que os usuários possam operá-lo com facilidade. Essa responsabilidade pode envolver a criação de manuais do usuário, a realização de sessões de treinamento ou a oferta de suporte no local. 
>
> A fase de Implantação não sinaliza o fim, mas sim um marco significativo. Ela marca a transição da fase de projeto para a fase de produto, onde o software começa a cumprir seu propósito."

## Fase de Manutenção
Sétima etapa do SDLC.

`Extraído Fonte SDLC`
> -"No Ciclo de Vida de Desenvolvimento de Software, a fase de manutenção é caracterizada por assistência e melhoria constantes, o que garante o melhor funcionamento e longevidade possíveis do software e assegura que ele atenda às expectativas do cliente.
>
> O foco principal é a adaptação às necessidades em constante mudança do software. Essa adaptação envolve responder ao feedback do usuário, resolver problemas inesperados e atualizar o software com base na evolução das necessidades dos usuários. É um processo contínuo de refinamento e adaptação, semelhante ao de um jardineiro cuidando do seu jardim.
>
> As tarefas de manutenção envolvem atualizações frequentes de software, implementação de patches e correção de bugs. O suporte ao usuário também é um componente crucial, oferecendo ajuda e orientação aos usuários que enfrentam dificuldades com o software.
>
> A fase de manutenção também considera estratégias de longo prazo, como, por exemplo, atualizar ou substituir o software. Essa decisão depende do ciclo de vida do software e do progresso tecnológico. Assim como um proprietário que pensa em reformar ou vender sua casa, o software pode precisar de uma reformulação completa ou ser descontinuado para permanecer relevante e valioso."