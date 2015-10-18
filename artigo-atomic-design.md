####Universidade do Oeste de Santa Catarina – Unoesc
####Pós-Graduação em Desenvolvimento Web, Cloud e Dispositivos Móveis - WebMob
####Disciplina: HTML5+CSS3
####Professor: Jean Carlo Nascimento
####Acadêmico: Maurício Alberto Grando
###Atomic Design
#####Resumo
O uso de softwares vêm crescendo assustadoramente ano após ano, e com isso cresce a demanda por desenvolvimento ágil e num curto espaço de tempo. Sendo essa uma necessidade a cada dia maior, uma das técnicas que vem ganhando espaço é chamada de Atomic Design, que apresenta a proposta de átomos, moléculas, organismos, templates e páginas. Essa técnica propõe um reuso dos componentes, a fim de ganhar tempo quando é necessário efetuar alguma mudança na interface, pois propõe que a alteração seja feita apenas num único local. Este artigo aborda um resumo da técnica do design atômico, bem como etapas, vantagens, conceitos e exemplos de seu uso.
#####1. O que é?
A técnica do design atômico é baseada na criação de componentes reaproveitáveis no desenvolvimento de um sistema (web, desktop, mobile, etc), a fim de centralizar cada funcionalidade num único local e diminuir o tempo de manutenção dessa funcionalidade.</br>
Esta metodologia para a criação de interfaces foi criada pelo webdesigner Brad Frost e explicada em detalhes na conferência Beyond Tellerrand, na Alemanha. Ela consiste em tomar emprestados da química os conceitos de átomos, moléculas e organismos, que juntos formam a matéria final (que é o sistema final entregue ao cliente).
#####2. Como funciona
Consiste em dividir o sistema em cinco partes, conforme descritas abaixo:</br></br>
**2.1 Átomos (atoms)**: são as partes mínimas de cada página, mas que sozinhas não são úteis. Exemplos: inputs, buttons, labels de formulários, etc.</br></br>
**2.2 Moléculas (molecules)**: são agrupamentos de átomos. Nesse ponto, o conteúdo começa a fazer sentido para quem está usando. Exemplo: um label de formulário, um input e um botão, quando agrupados, criam um formulário que pode efetuar alguma operação.</br></br>
**2.3 Organismos (organisms)**: são grupos de moléculas, que formam partes maiores (ou sessões) de uma página. Norteiam a navegação de leitura do conteúdo da interface. A criação de organismos torna possível o reuso de componentes, pois um organismo pode ter moléculas de vários tipos diferentes.</br></br>
**2.4 Modelos (templates)**: são grupos de organismos “costurados” (ou seja, organizados) para formar as páginas. A partir dessa etapa, o cliente já pode visualizar as páginas com funcionalidades dispostas em ação, com o desenho em fase final.</br></br>
**2.5 Páginas (pages)**: são instâncias específicas dos templates. Nessa etapa o conteúdo final é formado para dar uma visão exata do que o usuário acabará por ver. É tipicamente o local aonde a maioria das pessoas envolvidas no projeto do sistema passará o tempo, buscando problemas e/ou melhorias. Se for necessário algum ajuste, deve-se voltar às moléculas, organismos e templates para resolver.</br></br>
Existe uma ferramenta criada juntamente com a técnica do design atômico, chamada Pattern Lab. Esta ferramenta é utilizada para construir a interface, agrupando os átomos, moléculas e organismos. Também serve como biblioteca central para criação/alteração de novos componentes.</br></br>
O Pattern Lab também é utilizado para validar os componentes em vários browsers e também é possível fazer refresh (atualizar) automático a cada mudança em de componente (imagem, css, etc).
#####3. Por que usar
*	Esse é o jeito o qual nós já estamos pensando no design e implementação desses elementos, mas talvez não de forma consciente e não de forma tão específica.
*	Os membros do time de desenvolvimento e do cliente conseguem visualizar melhor o sistema de design, sem precisar ver os layouts salvos em frente a eles.
*	O sistema passa a ter maior escalabilidade e coerência enquanto mostra simultaneamente as coisas em seu contexto final. Não existem breakpoints ou devices específicos para montar a interface, e sim elementos que se comportam adequadamente a todos eles.
*	Agilidade na alteração de componentes: como é baseado em componentes, qualquer alteração pode ser feita uma única vez e todos os templates que usam esse componente já estarão alterados.
*	Centralização de informações: ao utilizar o Pattern Lab, o time de desenvolvimento tem em mãos uma biblioteca centralizada com informações de cada componente. Isso torna fácil o acesso às funcionalidades.

#####4. Onde usar
#####5. Exemplos
Seguem abaixo exemplos de cada etapa do atomic design aplicado num site real das [Ferramentas Gerais] (http://www.fg.com.br).
#####5.1 Átomos
Tags htmls que por si só não úteis, pois não existe vínculo entre elas.</br>
<img src="https://cloud.githubusercontent.com/assets/15130723/10555517/bab47aec-7446-11e5-8a0c-b9a3ba5877db.png" alt="atoms" title="Atoms"/></br>
#####5.2 Moléculas
Os átomos do item anterior foram agrupados, criando uma estrutura com possível utilidade para quem está usando.</br>
<img src="https://cloud.githubusercontent.com/assets/15130723/10555518/babaab74-7446-11e5-824f-aed4ffbb3e6e.png" alt="molecules" title="Molecules"/></br>
#####5.3 Organismos
Foi criado um novo componente a partir da junção da molécula do item anterior, somada a outras moléculas já criadas.</br>
<img src="https://cloud.githubusercontent.com/assets/15130723/10566802/7e736888-75cf-11e5-8e46-4116e9501175.png" alt="organisms" title="Organisms"/></br>
#####5.4 Templates
Foi aplicado o organismo do item anterior num wireframe, dando forma à página inicial do site.</br>
<img src="https://cloud.githubusercontent.com/assets/15130723/10555515/baa9c5ac-7446-11e5-9eac-aadf05215071.png" alt="templates" title="Templates"/></br>
#####5.5 Pages
Por fim, foi criada a página real, utilizando os átomos, moléculas, organismos e o template dos itens anteriores.</br>
Esta é a página que será entregue ao cliente para posterior avaliação/testes.</br>
<img src="https://cloud.githubusercontent.com/assets/15130723/10555516/baafe8f6-7446-11e5-9731-10cb8bd39f16.png" alt="pages" title="Pages"/></br>
#####6. Referências
[http://bradfrost.com/blog/post/atomic-web-design/] (http://bradfrost.com/blog/post/atomic-web-design/)</br>
[http://tableless.com.br/o-que-e-design-atomic/] (http://tableless.com.br/o-que-e-design-atomic/)</br>
[http://patternlab.io/] (http://patternlab.io/)</br>
[http://www.frontendbrasil.com.br/tutoriais/atomic-design-como-funciona/] (http://www.frontendbrasil.com.br/tutoriais/atomic-design-como-funciona/)</br>
