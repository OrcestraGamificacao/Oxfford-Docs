# Documento de Visão

## Introdução

### Propósito

Esse documento tem como objetivo descrever e esclarecer o funcionamento do sistema da A+ Espaços Didáticos, idealizado pela mesma, desenvolvido e implementado pela Orc'estra Gamificação, Empresa Junior de Engenharia de Software da Universidade de Brasília que tem como finalidade conectar professores e alunos no ambiente virtual, em prol de adaptar e ajudar espectros da educação brasileira.

### Escopo

Esse documento se refere ao website A+ Espaços Didáticos, à equipe desenvolvedora e também aos usuários do sistema. Além da usabilidade de cada usuário, e como isso afeta a sociedade, sendo assim um documento que descreve o comportamento geral, direta e indiretamente do sistema e do projeto desenvolvido.

### Definições, acrônimos e abreviações

* UnB - Universidade de Brasília
* Site - website / sistema web.
* Orc'estra - Orc'estra Gamificação
* EJ - Empresa Junior
* A+ -  A+ Espaços Didáticos
* Usuários - Pessoas que irão utilizar do software
* Back-end - Área do software no qual é implementado a regra de negócio do sistema.
* Front-end - Área do software no qual é implementado a interação do sistema com o usuário
* Stakeholders - Parte interessada do projeto
* API - Plataformas que utilizam do método *Software as a Service*


### Visão Geral

Esse documento descreve o posicionamento do site no mercado, descrição dos stakeholders, visão geral do produto, recursos, entre outros. De forma sistemática com o objetivo de informar ao leitor deste documento todas as formas de organização da aplicação e do projeto, e os motivos dele estar sendo desenvolvido.

## Posicionando

### Oportunidade de negócio

A aplicação se encontra em um contexto onde é necessário recursos adicionais para aprimoramento da educação, visto isso foi identificado uma oportunidade de conectar professores e alunos em diversos métodos de ajuda para a educação. Nesse contexto, professores cadastram-se com seus perfis em conjunto com horários de disponibilidade para que os alunos consigam agendar-se e terem uma aula de reforço, por exemplo. Além disso, é possível também que alunos submetam listas de exercícios para que recebam auxílio de professores na plataforma.

### Instrução do problema

O problema da pandemia de CoViD-19 afetou em diversos níveis o setor da educação. Sendo assim, a A+ é um website que visa conectar estudantes e professores para reforçar o ensino e auxiliar como uma plataforma que fomenta a educação durante esse período, assim como posteriormente poderá servir de auxílio para professores. O impacto do problema é a falta de aulas para que os alunos possam estudar para os principais exames nacionais, além de falta de remuneração para os professores durante esse período. Uma solucação bem sucedida incluiria o contato de professores com os alunos de forma remunerada, os alunos receberem auxílio através da plataforma para disciplinas e conteúdos que estejam estudando.

### Instrução de posição do produto

Para os alunos e professores os quais necessitam de algum método de conexão para auxílio educacional ou monetário. a A+ que disponibiliza de uma plataforma para que ambos possam realizar essa conexão. De outro modo do qual outras plataformas fazem, a A+ traz um diferencial que é a conexão mais pessoal entre os pares, não deixando o processo tão automatizado quanto se espera. Mostrando-se interessante o uso da plataforma justamente pela forma fácil e simples de se executar as funções da plataforma.

## Descrições da Parte Interessada e do Usuário

### Resumo da Parte Interessada

|Nome|Representa|Função|
|----|----------|------|
|A+ Espaços Didáticos|O cliente|Realiza a divulgação e representa legalmente a plataforma perante aos meios legais.|
|Orc'estra Gamificação | Os desenvolvedores | Realiza o desenvolvimento e implantação da aplicação.|
|Usuários|Os alunos e professores|Utilizam a plataforma para se conectar|

### Resumo do Usuário

|Nome|Descrição|Parte Interessada|
|----|----------|------|
|Professores| Se cadastram na plataforma onde podem resolver listas de exercícios, ministrar aulas online de reforço para alunos que agendem com eles, além de disponibilizar cursos produzidos. | Usuários|
|Alunos | Se cadastram na plataforma onde podem submeter listas de execícios para resolução dos professores, além de agendar e comprar aulas / cursos que são disponibilizados pelos professores. | Usuários|
|Administradores | Podem realizar a administração da plataforma, visualizando diversos setores e conseguindo remover/adicionar recursos na plaforma. | A+ Espaços Didáticos|


### Ambiente do Usuário

Analisando as principais tarefas que podem ser executadas na plataforma, são necessário no mínimo duas pessoas para que elas sejam concluídas de forma satisfatória, sendo elas o aluno e o professor. Indiretamente é necessário a aprovação do professor pelos administradores, assim como também da plataforma que gerencia o pagamento e recebimento de recursos, aumentando o escopo de usuários necessários para cumprimento das tarefas como um todo.

Idealmente, o tempo necessário para execução das tarefas é bastante variável. Para agendamento de aulas, aceitação por parte dos professores, pagamento por parte dos alunos assim como o encontro de ambos para a aula, o tempo para a tarefa é a diferença entre o momento em que foi feito o agendamento e a finalização da aula.

Como restrições, é necessário que os usuários tenham acesso à internet para que possam fazer pleno uso da plataforma. Além de terem instalado algum dos principais navegadores web, como Google Chrome, Mozilla Firefox ou Safari.

Alguns sistemas adicionais estão integrados à plataforma. São eles:  *Zoom*, API para criação de chamadas virtuais, *SendGrid*, API para envio de emails para os usuários. *Stripe*, API para pagamentos. *Amazon AWS S3*, API para armazenamento de arquivos, fotos e vídeos.


### Perfis das Partes Interessadas e dos Usuários

**Representante:** A+ Espaços Didáticos
* Descrição: São os donos do produto, são eles que fazem a administração da plataforma adicionando e removendo recursos da plataforma, como adicionar matérias / disciplinas para que os professores possam se cadastrar. Além de fazer o gerenciamento de denuncias, depoimentos e perguntas enviadas para a plataforma como um todo.
* Tipo: Especialistas de negócio.
* Responsabilidades: Realizar o pagamento dos principais recursos necessários em termos de infraestrutura para a hospedagem do site. Além de realizar a administração citada em itens anteriores.
* Critérios de Sucesso: Ter a plataforma online com a utilização por diversos usuários. O ganho em cima disso será de uma pequena comissão paga sobre cada aula gerada pela plataforma.
* Envolvimento: Estão envolvidos justamente da detenção da ideia da regra de negócio, além de serem responsáveis legalmente sobre a plataforma. São eles os responsáveis também por procurar por ademais evoluções e funcionalidades.
* Entregas: Essa parte espera o produto como um todo entregue pela equipe desenvolvedora. Para que a mesma possa fazer a divulgação e propagação da plataforma.

**Representante:** Orc'estra Gamificação

* Descrição: Equipe responsável pelo desenvolvimento e implantação do software.
* Tipo: Técnicos e Desenvolvedores de Software e Gamificação.
* Responsabilidades: Realizar o desenvolvimento do software, incluindo Back-end e Front-end. Além da implantação no contexto virtual, para que a plataforma fique disponível para todos.
* Critérios de Sucesso: Ter o projeto entregue e sendo um projeto que impacte a sociedade no qual ele está incluído.
* Envolvimento: Envolve-se no contexto de tomadas de decisão sobre questões técnicas do software e da gamificação interna.
* Entregas: Se espera o pagamento da infraestrutura por parte dos donos do produto para que seja feita a parte da implantação. Além de também ser necessário que os mesmos criem contas de acesso em cada plataforma (API) que será utilizado e integrado na plataforma.

**Represetante:** Professores
* Descrição: Usuários que disponibilizam serviços na plataforma.
* Tipo: Especialista em área de ensino
* Responsabilidades: Disponibilizar horários específicos para ministrar suas aulas online e também conteúdos diversos.
* Critérios de Sucesso: Conseguir disponibilizar seus conteúdos e recursos em prol de auxiliar na educação de outros usuários.
* Envolvimento: Estão envolvidos como público-alvo.
* Entregas: Se espera a plataforma em pleno funcionamento.

**Representante:** Alunos
* Descrição: Usuários que contratam / compram serviços na plataforma.
* Responsabilidades: Manter o funcionamento da plataforma com as interações geradas com os conteúdos e recursos disponibilizados.
* Critérios de Sucesso: Conseguir ter acesso às aulas / cursos presentes na plataforma.
* Envolvimento: Estão envolvidos como público-alvo.
* Entregas: Se espera a plataforma em pleno funcionamento.

### Principais necessidades da Parte Interessada ou do Usuário

O principal motivo para o problema resolvido pela plataforma da A+ é a falta de auxílio educacional durante a pandemia de CoViD-19, acompanhado da necessidade dos estudantes em reforçarem seus estudos extra-classe.

O problema é resolvido, com o método de conexão entre professores e alunos de forma fácil, acessível e intuitiva. Sendo assim, suprimindo grande parte do problema apresentado.

A solução proposta é uma plataforma que faça essa conexão mantendo o diálogo entre os pares de forma que eles possam utilizar da plataforma de forma satisfatória e engajada.

## Visão Geral do Produto

### Perspectiva do Produto

A plataforma A+ é um produto parcialmente autocontido, dependente de plataformas de terceiros para administração de algumas funcionalidades como pagamentos, envio de emails, criação de reuniões virtuais, armazenamento de arquivos, etc. Com isso a manutenção do software deve ser feito por empresas à escolha da empresa A+ Espaços Didáticos que são os responsáveis pela plataforma. 

![](https://i.imgur.com/XRMkdVC.png)
![](https://i.imgur.com/oFOGHJg.png)
![](https://i.imgur.com/bWtDqUF.png)

### Resumo das Capacidades

|Benefício para o Cliente|Recursos de Suporte|
|------------------------|-------------------|
|Professores podem se disponibilizar para aulas online. | O cadastro é feito com horários de disponibilidade que podem ser alterados conforme o professor quiser.|
|Professores podem disponibilizar cursos sobre conteúdos de suas especialidades. | Cada professor têm sua própria página de perfil, podendo manipulá-la conforme quiser.|
|Alunos podem submeter listas de exercícios para resolução por parte dos professores. | É possível especificar um um valor à ser pago pela resolução da lista, além de conseguir aceitar qualquer professor que se interesse.|
|Usuários podem entrar em contato em qualquer hora que desejar. | A plataforma conta com diversos recursos para entrar em contato com os administradores.|
|Os usuários podem se conectar em uma chamada assim que a aula se torna disponível. | Os links para as video-chamadas são gerados automaticamente com a criação da aula. Com horários agendados.|
|Os usuários podem pesquisar por professores e matérias. | A plataforma conta com um sistema de busca para objetos dentro de seu escopo.|
|Os professores podem ser categorizados por disciplinas escolares. | A plataforma separa os professores em disciplinas para melhor visualização dos mesmos.|
|Os alunos e professores nunca terão choques de horários. | A plataforma organiza automaticamente os horários do professores, de forma que dois alunos nunca poderão marcar horário com o mesmo professor no mesmo horário.|
|Professores serão bem remunerados a partir do que eles querem receber por aula. | O pagamento feito pelos alunos na plataforma é dividido com um pequena comissão para os administradores.|
|Os usuários podem se comunicar de forma instantânea dentro da plataforma. | Existe na plataforma chats que possibilitam essa comunicação entre professor e aluno.|
|Os administradores podem se comunicar com os usuários através do email. | O dashboard de administração conta com essa funcionalidade.|
|Os administradores podem fazer o controle de quais professores. | É possível para os administradores, aprovarem ou reprovarem professores na plataforma, deixando-os disponíveis ou indisponíveis para visualização na plataforma.|
|É possível fazer o gerenciamento de disciplinas presentes na plataforma. | Os administradores podem fazer o gerenciamento de matérias através da criação delas, e da ativação / desativação das mesmas.|
|É possível para os administradores responderem os contatos recebidos. | É possível no dashboard do administrador, responder os contatos recebidos, através da publicação de depoimentos, além de respostas por email.|

### Suposições e Dependências

* Alteração de escopo com a adição de novas funcionalidades.
* Modificação no fluxo de atividades da plataforma.
* Alteração nos sistemas de navegadores que impossibilitem alguma funcionalidade.
* Modificação em alguma API integrada com a plataforma.

### Custos e Precificação

**Servidor:** É necessário dispor de recursos para hospedagem do sistema no ambiente web. Sendo assim gastos certos custos com o servidor.

**Desenvolvimento:** A precificação realizada foi o produto de dias trabalhados pelo número de desenvolvedores disponíveis para o projeto pela Orc'estra Gamificação.

**Armazenamento:** É necessário que seja pago mensalmente pelo custo de armazenamento online, de arquivos para disponibilização da plataforma.

**Pagamentos:** É cobrado uma taxa de 2.3% sobre a conta principal atrelada à API de Pagamento utilizada, sobre cada cobrança feita.

### Licenciamento e Instalação

O software foi desenvolvido à partir de tecnologias disponíveis no mercado de desenvolvimento não sendo necessário quaisquer licenciamento para uso das mesmas. A instalação não é necessária visto que se trata de uma aplicação disponível no meio web. Utilizando de protocolos de segurança da internet.

## Recursos do Produto

1. **Realizar cadastro:** O usuário se cadastra como professor ou como aluno. Visando as especificações de cada tipo de usuário.
2. **Realizar confirmação de conta:** Quando cadastrados, os usuários confirmam suas contas através do email.
3. **Realizar login:** O usuário efetua o login na plataforma, para ter acesso à todas as funcionalidades.
4. **Visualizar matérias:** O usuário pode ver a listagem de matérias disponíveis na plataforma.
5. **Visualizar perguntas frequentes:** O usuário pode visualizar perguntas frequentes disponibilizado pelo administrador.
6. **Buscar:** O usuário pode buscar por professores e matérias na plataforma.
7. **Visualizar solicitações / requisições:** Professores e alunos podem visualizar suas respectivas solicitações e requisições.
8. **Aceitar aulas:** Professores devem aceitar as aulas para que os alunos paguem por elas.
9. **Pagar aulas:** Alunos pagam pelas aulas que foram aceitas pelos professores
10. **Cancelar aulas:** Durante as solicitações, ou mesmo depois de paga a aula pode ser cancelada pelo professor.
11. **Visualizar aulas:** Professores e alunos podem acessar as aulas para visualizar suas informações e também ter acesso ao link da video-chamada.
12. **Enviar denúncia:** Os usuários podem enviar denúncias para o administrador a partir de uma aula.
13. **Reagendar aulas:** Alunos podem reagendar aulas que foram pagas porém canceladas pelo professor.
14. **Criar listas de exercícios:** Alunos podem submeter listas de exercícios para a plataforma.
15. **Visualizar listas de exercícios:** Professores podem visualizar todas as listas de exercícios submetidas, e alunos podem visualizar todas as suas listas criadas.
16. **Candidatar para lista de exercícios:** Professor podem se candidatar para resolver listas de exercícios.
17. **Selecionar professor:** Alunos escolhe um dos professores dos quais se candidataram para resolver a lista.
18. **Submeter solução:** Professor pode submeter uma solução para lista de exercícios.
19. **Pagar professor para solução:** Quando submetido solução, o aluno pode pagar para recebe-la em seu email.
20. **Acessar perfil:** O usuário pode acessar seu próprio perfil para visualizar informações cadastradas.
21. **Editar perfil:** O usuário pode editar as suas informações pessoais.
22. **Editar informações da aula:** O professor pode editar informações da sua aula, como matérias, preço, horários.
23. **Enviar perguntas:** O usuário pode enviar perguntas para os administradores.
24. **Enviar depoimentos:** O usuário pode enviar depoimentos para os administradores.
25. **Alterar senha:** O usuário pode alterar a sua senha.
26. **Visualizar professores por matéria:** Os usuários podem visualizar a listagem de professores disponíveis em cada matéria.
27. **Filtrar professores:** Dentro de cada matéria é possível filtrar professores por preço e nível de escolaridade.
28. **Visualizar informações do professor:** O usuário pode visualizar informações sobre a aula de todo o professor.
29. **Agendar aula:** O aluno pode agendar aulas de acordo com dia / horário / matéria disponível no professor.
30. **Comprar curso:** O aluno pode comprar cursos dos professores.
31. **Acessar curso:** O aluno que comprou um curso, pode acessar os vídeos daquele curso.
32. **Enviar contato:** O usuário pode enviar contato para os administradores.
33. **Realizar cadastro do ADMIN:** O administrador pode se cadastrar.
34. **Realizar login do ADMIN:** O administrador pode efetuar o login.
35. **Gerenciar matérias:** O administrador pode adicionar e desativar matérias da plataforma.
36. **Gerenciar usuários:** O administrador pode adicionar e remover usuários da plataforma.
37. **Gerenciar denúncias:** O administrador pode visualizar denúncias feitas por usuários.
38. **Gerenciar perguntas:** O administrador pode visualizar as perguntas feitas por usuários.
39. **Gerenciar depoimentos:** O administrador pode publicar depoimentos na plataforma assim como removê-los.

## Restrições

O design desenvolvido para a plataforma está de acordo com os padrões web para desktop, sendo assim o uso em aparelhos móveis pouco efetivo e não adaptado.

Existem restrições sobre plataformas de terceiros. Para que o professor possa receber pelas aulas que foram dadas, além de seus cursos. É necessário ter a devida verificação e cadastro na plataforma de pagamento responsável por administrar esse recurso. Toda a verificação é feita pela própria plataforma de pagamento (Stripe), sendo passível de reprovação em alguns casos.

É necessário para o professor dispor de dados pessoais para cadastro na plataforma de pagamentos. Sendo esses dados não armazenados nos bancos de dados da plataforma A+.

## Faixas de Qualidade

Para que o produto mantenha uma nível de qualidade, é necessário seguir as especificações técnicas do software. Sobre grande demanda, o software deve funcionar de forma satisfatória. Sendo que grande parte do desempenho é dado pela infraestrutura contratada.

Em questões de usabilidade foram seguidos e validados os princípios de usabilidade mantendo a navegabilidade satisfatória, simples, acessível e de fácil entendimento.

O uso pleno da plataforma deve ser entendido em pares, não é possível o completo uso da plataforma sem respostas dos pares específicos, como por exemplo um aluno ter acesso à aula sem a aprovação devida do professor. Mantendo assim questões de segurança importantes para a plataforma.

## Precedência e Prioridade

1. Realizar cadastro do ADMIN
2. Realizar login do ADMIN
3. Gerenciar matérias
4. Realizar cadastro
5. Realizar confirmação de conta
6. Realizar login
7. Acessar perfil
8. Editar perfil
9. Editar informações da aula
10. Visualizar matérias
11. Gerenciar usuários
12. Visualizar professores por matérias
13. Visualizar informações do professor
14. Agendar aula
15. Comprar curso
16. Acessar curso
17. Visualizar solicitações / requisições
18. Aceitar aulas
19. Pagar aulas
20. Cancelar aulas
21. Visualizar aulas
22. Reagendar aulas
23. Enviar denúncias
24. Criar lista de exercícios
25. Visualizar listas de exercícios
26. Candidatar para lista de exercícios
27. Selecionar professor
28. Submeter solução
29. Pagar professor para solução
30. Enviar perguntas
31. Enviar depoimentos
32. Filtrar professores
33. Alterar senha
34. Enviar contato
35. Gerenciar denúncias
36. Gerenciar perguntas
37. Gerenciar depoimentos
38. Buscar
39. Visualizar perguntas frequentes

## Outros requisitos do produto

### Padrões Aplicáveis

* Padrões de comunicação: TCP/IP
* Padrões de conformidade da plataforma: Windows, Unix, MacOS
* Padrões de qualidade e segurança: ISO 9001

### Requisitos do Sistema

A plataforma está disponível para todos os sistemas operacionais com interface gráfica que contem com suporte à navegadores de internet. Não existem requisitos mínimos para executação do software desenvolvido.

Para que a plataforma funcione de forma plena, é necessário também o pleno funcionamento das API integradas que funcionam de forma independente.

## Apêndice 1 - Atributos do Recurso

### Status

O produto está com status de APROVADO, que significa que as capacidades que são consideradas úteis e factíveis e que foram aprovadas para implementação pelo canal oficial.

### Benefício

Nesse tópico são descritos os benefícios de cada recursos para o público alvo, sendo avaliados em 3 níveis. Crítico, Importante e Útil.

1. Realizar cadastro do ADMIN: Crítico
2. Realizar login do ADMIN: Crítico
3. Gerenciar matérias: Crítico
4. Realizar cadastro: Crítico
5. Realizar confirmação de conta: Importante
6. Realizar login: Crítico
7. Acessar perfil: Crítico
8. Editar perfil: Importante
9. Editar informações da aula: Importante
10. Visualizar matérias: Útil
11. Gerenciar usuários: Importante
12. Visualizar professores por matérias: Importante
13. Visualizar informações do professor: Crítico
14. Agendar aula: Crítico
15. Comprar curso: Crítico
16. Acessar curso: Importante
17. Visualizar solicitações / requisições: Crítico
18. Aceitar aulas: Crítico
19. Pagar aulas: Crítico
20. Cancelar aulas: Importante
21. Visualizar aulas: Crítico
22. Reagendar aulas: Útil
23. Enviar denúncias: Útil
24. Criar lista de exercícios: Crítico
25. Visualizar listas de exercícios: Importante
26. Candidatar para lista de exercícios: Importante
27. Selecionar professor: Crítico
28. Submeter solução: Crítico
29. Pagar professor para solução: Crítico
30. Enviar perguntas: Útil
31. Enviar depoimentos: Útil
32. Filtrar professores: Útil
33. Alterar senha: Útil
34. Enviar contato: Útil
35. Gerenciar denúncias: Útil
36. Gerenciar perguntas: Útil
37. Gerenciar depoimentos: Útil
38. Buscar: Útil
39. Visualizar perguntas frequentes: Útil

### Esforço

Abaixo são numerados os recursos que determinam mais esforço com base na complexidade técnica do desenvolvimento dos mesmos, em termos de funções e quantidade de código.

1. Realizar cadastro do ADMIN
2. Realizar login do ADMIN
3. Realizar cadastro
4. Realizar confirmação de conta
5. Realizar login
6. Editar perfil
7. Editar informações da aula
8. Agendar aula
9. Comprar curso
10. Visualizar solicitações / requisições
11. Pagar aulas
12. Pagar professor para solução

Esses recursos foram definidos como mais complexos justamente pela dificuldade em reproduzir uma lógica coerente em determinar questões de segurança e usabilidade para os mesmos. Além de algum deles depender de esforços de terceiros para o seu pleno funcionamento, como por exemplo a etapa de pagamentos, enquanto outros foram definidos a complexidade pela quantidade de funções e códigos gerados.

### Riscos

#### Gerenciamento de Riscos

A Gestão de Riscos é voltada para o futuro, uma vez que um gerenciamento eficaz requer a identificação antecipada de ameaças e oportunidades. O principal benefício do plano é o de garantir que o grau, o tipo e a visibilidade do gerenciamento de riscos sejam proporcionais tanto aos riscos como à importância para a organização e para as demais partes interessadas.

Gerenciar os riscos do projeto requer um Plano de gerenciamento dos riscos descrevendo como os processos de riscos serão estruturados e executados iniciando pela identificação dos riscos, suas análises qualitativa e quantitativa, seu plano de respostas e concluindo com a forma que os riscos serão controlados e monitorados. O Plano de gerenciamento dos riscos é desenvolvido e aprovado durante a fase de planejamento do projeto e é um plano auxiliar do Plano de gerenciamento do projeto. Tem como objetivo aumentar a probabilidade e o impacto dos eventos positivos, reduzir a probabilidade e o impacto dos eventos negativos no projeto e orientar a equipe do projeto sobre como os processos de riscos serão executados.

#### Processo de Gerenciamento de Riscos

* Identificar os riscos: Determinar quais riscos podem afetar o projeto e documentar suas características.
* Realizar a análise qualitativa dos riscos: Avaliar a exposição ao risco para priorizar os riscos que serão objetos de análise ou ação adicional.
* Realizar a análise quantitativa dos riscos: Efetuar a análise numérica do efeito dos riscos identificados nos objetivos gerais do projeto.
* Planejar as respostas aos riscos: Desenvolver opções e ações para aumentar as oportunidades e reduzir as ameaças aos objetivos do projeto.
* Controlar os riscos: Monitorar e controlar os riscos durante o ciclo de vida do projeto.

#### Categorias dos Riscos

* Técnico: Requisitos, Tecnologia, Confiabilidade, Usabilidade, Desempenho, Qualidade.
* Externo: Políticas, Infraestrutura, Condições climáticas.
* Organizacional: Dependências do projeto.
* Gerencial: Planejamento, Controle.

#### Definições de probabilidade e impacto

**Probabilidade**

Um risco é um evento que “pode” ocorrer. A probabilidade de ocorrer pode variar de um pouco mais de 0% a um pouco menos de 100%. Observe que risco trata de incerteza, por isso não podemos identificá-lo como 100% de probabilidade de ocorrência, porque então seria uma certeza, não um risco. Assim como não pode ser exatamente 0%, ou não seria um risco.

|Probabilidade - P|Intervalo|Peso|
|-----------------|---------|----|
|Muito baixo|0 <= P <= 20%|1|
|Baixo|20% <= P <= 40%|2|
|Moderado|40% <= P <= 60%|3|
|Alto|60% <= P <= 80%|4|
|Muito alto|80% <= P <= 100%|5|

**Impacto**

O tamanho do impacto varia de acordo com a questão sendo avaliada.

| Impacto - I | Descrição | Peso|
| -------- | -------- | -------- |
| Muito Baixo | Quase que imperceptível ao projeto | 1 |
| Baixo | Pouca influência no desenvolvimento do projeto | 2 |
| Moderado | Notável ao projeto, mas sem grandes consequências | 3 |
| Alto | Dificulta o desenvolvimento do projeto | 4 |
| Muito Alto | Impossibilita o prosseguimento do projeto | 5 |

**Matriz de Probabilidade e Impacto**

| P\I | Muito Baixo | Baixo | Moderado | Alto | Muito Alto |
| -------- | -------- | -------- | -------- | -------- |  -------- |
| Muito Baixo | 1 | 2 | 3 | 4 | 5 |
| Baixo | 2 | 4 | 6 | 8 | 10 |
| Moderado | 3 | 6 | 9 | 12 | 15 |
| Alto | 4 | 8 | 12 | 16 | 20 |
| Muito Alto | 5 | 10 | 15 | 20 | 25 |

**Prioridade** 

Com a matriz Probabilidade X Impacto é possível determinar o nível de prioridade de cada risco.

| Prioridade | Intervalo | 
| -------- | -------- |
| Baixa | 1-5 |
| Média | 6-15 |
| Alta | 16-25 |

#### Riscos do Trabalho

| Risco	| Causa	| Descrição	| Impacto |
| -------- | -------- | -------- | -------- |
| R01 | Inexperiência da equipe	| Dificuldades com a tecnologia de desenvolvimento | Produtividade baixa e atraso nas entregas |
| R02 |  Falta de Acessibilidade| Acessibilidade à internet em meio a pandemia | Atraso nas entregas ou sobrecarga de outro membro da equipe |
| R03 | Escopo mal definido | Mudança no escopo | Replanejamento das atividades |
| R04 | Impossibilidade física ou emocional de realizar atividade | Contágio do SARS-CoV-2 de membro da equipe ou de familiar de membro da equipe  | Mudança no Planejamento |
| R05 | Saída de membros da Equipe | Membros saírem da empresa antes de terminarem o projeto | Replanejamento de atividades e atraso de entregas |

#### Análise e Respostas aos Riscos

|Risco|Probabilidade|Impacto|Prioridade|Ação|
|-----|-------------|-------|----------|----|
|R01|Moderada|Alto|Média|Capacitar os membros nas tecnologias utilizadas.|
|R02|Moderada|Alto|Média|Remanejar atividades remanescentes entre os membros.|
|R03|Baixo|Alto|Baixa|Replanejar atividades e tempo que será necessário para execução.|
|R04|Moderada|Alto|Média|Remanejar atividades remanescentes entre os membros.|
|R05|Alta|Alta|Alta|Alocar novos membros para o projeto.|