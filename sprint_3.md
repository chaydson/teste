# Sprint 3 - Documentação

## Informações Gerais
- **Início da Sprint:** 06/01/2025
- **Fim da Sprint:** 16/01/2025
- **Objetivo da Sprint:** retomar as contribuções do projeto 

# Lista de Membros

| Nome                              | Usuário   GitLab          |
|-----------------------------------|---------------------|
| Ana Beatriz Massuh                | @AnaBeatrizMassuh   |
| Artur Jackson                     | @artur-jack         |
| Artur Rodrigues                   | @ArturRSA19         |
| Beatriz Nascimento                | @Beatrizvn          |
| Delziron Braz                     | @DelzironBraz       |
| Gabriel Marcolino Rodrigues        | @GabrielMR360       |
| Guilherme de Sá Gonçalves         | @GuilhermeDSa1013   |
| João Barreto                      | @JoaoBarreto03      |
| Lucas Felipe Soares               | @lucasfs1007        |
| Lucas Spinosa                     | @LucasSpinosa       |
| Mateus de Almeida                 | @Mateuszinnn        |
| Pedro Henrique Rodrigues de Carvalho | @PedroHenrique2077 |
| Silas Souza                       | @Silas-souza        |
| Chaydson Ferreira                 | @chaydson           |
| Felipe Guimaraes                        | @felipegf1          |


# Issues por Membro

| Nome                              | Issues                   |
|-----------------------------------|--------------------------|
| Ana Beatriz Massuh                | [#360](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/merge_requests/342), [#220](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/220) e [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151)                         |
| Artur Jackson                     | [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                         |
| Artur Rodrigues                   | [#400](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/400#note_2292665400) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260#note_2292665506)                        |
| Beatriz Nascimento                | [#451](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/451)                         |
| Delziron Braz                     | [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194)                         |
| Felipe Guimaraes                  | [#294](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/294)                         |
| Gabriel Marcolino Rodrigues       | [#294](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/294) e [#432](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/432)                        |
| Guilherme de Sá Gonçalves         | [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                         |
| João Barreto                      |  [#400](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/400#note_2292665400) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260#note_2292665506)                       |
| Lucas Felipe Soares               | [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#195](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/195)                         |
| Lucas Spinosa                     | [#251](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/251) e [#180](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/180)       |
| Mateus de Almeida                 | [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                         |
| Pedro Henrique Rodrigues de Carvalho | [#221](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/221) e [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                      |
| Silas Souza                       |                          |
| Chaydson Ferreira                 | [#221](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/221) e [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)                         |

## Participação dos Membros da Equipe durante a Sprint 3

### Ana Beatriz Massuh
- **Tarefas concluídas:** [#360](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/merge_requests/342)
- **Dificuldades encontradas:** Tive dificuldades em visualizar o erro de distribuidora duplicada que foi relatado na issue [#151](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/151).
- **Relatos:** Pela terceira vez acredito que finalizei a issue [#360](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/merge_requests/342), nessa sprint adicionei a demanda de geração agora no formulário de edição de unidade consumidora. Comecei a solucionar a issue [#220](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/220) para a refatoração da configuração de e-mail para usar o backend de e-mail nativo do Django, nela atualizei o `settings.py` para utilizar o sistema de e-mail nativo do Django, criei configurações específicas para e-mails no ambiente de desenvolvimento (`settings/development.py`), mas ainda falta adicionar o Mailpit ao `docker-compose.yml` para facilitar o debug em ambiente de desenvolvimento, refatorar a função `send_email` para usar `django.core.mail`e criar os testes para certificar se tudo está correto.

### Artur Jackson
- **Tarefas concluídas:** [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)
- **Dificuldades encontradas:** 
- **Relatos:** Contribuí para o aumento na cobertura de testes no frontend com a realização de testes nos componenetes Header e FormFieldError na issue [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222). Além disso, também estava trabalhando na issue [#444](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/444), remanescente da última sprint. Após terminar, antes de subir as alterações, percebi que com as novas atualizações vindas do upstream, fizeram com que não fosse mais possível selecionar outra data na fatura. Tornando a issue obsoleta.

### Artur Rodrigues
- **Tarefas concluídas:** [#400](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/400#note_2292665400) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260#note_2292665506) (Parcialmente)
- **Dificuldades encontradas:** Achar os locais específicos para mudanças dos cards.
- **Relatos:** Peguei duas issues para resolver neste sprint. A primeira está relacionada com flashes que apareciam na barra de rolagem do navegador, que foi tranquilamente resolvida. A segunda issue consiste na alteração dos tamanhos para preencher os espaços vazios na tela quando a resolução da tela é maior, infelizmente ainda não foi finalizada, mas está encaminhada. 

### Beatriz Nascimento
- **Tarefas concluídas:** [#451](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/451) 
- **Dificuldades encontradas:** Nenhuma
- **Relatos:** A issue consistia em resolver esse bug: No formulário de Adicionar Unidade Consumidora, no campo de "Início de Vigência", ao tentar inserir uma data manualmente, o input de data não permite a inserção do ano. Em geral foi uma issue tranquila de ser feita. 

### Chaydson Ferreira
- **Tarefas concluídas:** [#221](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/221) e [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222) Configuração e implementação do jest para informar a taxa de cobertura de testes em relação a todo o projeto e um relatório, bem como o aumento da cobertura de testes do frontend, com foco nos arquivos app.ts, person.ts, recommendation.ts (pasta types) e validation-cnpj.ts
- **Dificuldades encontradas:** Identificação de dependências não bem mapeadas em alguns arquivos, como validation-cnpj.ts, o que exigiu ajustes no código para torná-lo testável.
- **Relatos:** O aumento da cobertura de testes trouxe uma maior confiança no código e ajudou a identificar melhorias necessárias nas implementações existentes

### Delziron Braz
- **Tarefas concluídas:** [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194)
- **Dificuldades encontradas:** Na issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) a maior dificuldade foi resolver problemas que o pipeline encontrou, entretando, foi consultado um monitor para tal problema, e será marcado um encontro para melhor avaliação do pipeline, tendo em vista que o teste passa e aumenta a cobertura
- **Relatos:** Na issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) trabalhei em conjunto com o Lucas Felipe, onde desenvolvemos mais testes para aumentar a cobertura do mepa-api. Tivemos sucesso com êxito no aumento da cobertura dos testes, como também, na diminuição de erros encontrados nos testes.

### Felipe Guimaraes 
- **Tarefas concluídas:** [#294](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/294)
- **Dificuldades encontradas:** Apenas o tempo de estudo para resolver o problema
- **Relatos:** Nessa Sprint por falta de tempo formei um par com o gabriel marcolino que foi quem me ajudou com o que precisei para o desenvolvimento da Issue e conseguimos concluir os ajustes

### Gabriel Marcolino Rodrigues
- **Tarefas concluídas:** [#294](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/294) e [#432](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues 432)
- **Dificuldades encontradas:** Usar o mesmo layout(código) que a tabela de faturas na tela de UC usava e a unificação das duas para deixa em um componente parametrizado.
- **Relatos:** Nessa sprint fiz o ajuste solicitado no merge que fiz na primeira spring na issue 432 e dei continuidade na issue 294, a qual estava atuando na sprint passada. Dentre os itens solicitados na issue 294 não consegui fazer o de usar o mesmo layout(código) que a tabela de faturas na tela de UC, pois ao tentar fazer isso acabava quebrando toda a formatação já feita na tabela, então acabou que ficou de fora esse ajuste assim como a unificação das duas tabelas que dependia da outra tarefa mencionada. Além disso, fiz pareamento com o Felipegf1 na issue 294.

### Guilherme de Sá Gonçalves
- **Tarefas concluídas:** [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222)
- **Dificuldades encontradas:** Não tive difuculdades em fazer os testes
- **Relatos:** Nessa sprint, me dediquei a aumentar a cobertura de testes no frontend, juntamente com outros colegas. Finalizei os testes dos 4 últimos arquivos em "utils", alcançando 100% de cobertura nessa classe.

### João Barreto
- **Tarefas concluídas:** [#400](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/400#note_2292665400) e [#260](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/260#note_2292665506) (Parcialmente)
- **Dificuldades encontradas:** Achar os locais específicos para mudanças dos cards.
- **Relatos:** Peguei duas issues para resolver neste sprint. A primeira está relacionada com flashes que apareciam na barra de rolagem do navegador, que foi tranquilamente resolvida. A segunda issue consiste na alteração dos tamanhos para preencher os espaços vazios na tela quando a resolução da tela é maior, infelizmente ainda não foi finalizada, mas está encaminhada. 

### Lucas Felipe Soares
- **Tarefas concluídas:** [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/194) e [#195](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/195).  
- **Dificuldades encontradas:** Na issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-endosergia-api/-/issues/194) encontramos problemas envolvendo o pipeline desde a sprint passada. Com isso, optamos por seguir tentando aumentar a cobertura de testes enquanto não o problema do piplenine não fosse corrigido. Quanto a issue [#195](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/195) não obtive grandes dificuldades e a issue já está em code review.  
- **Relatos:** A issue [#194](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-endosergia-api/-/issues/194) segui fazendo pareamento com o [Delziron Braz](https://gitlab.com/DelzironBraz).

### Lucas Spinosa
- **Tarefas concluídas:** [#251](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/251)
- **Dificuldades encontradas:** Necessidade de alterações no Backend 
- **Relatos:** Consegui realizar a issue [#251](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/251) sem muitas dificuldades. Entretanto a issue [#180](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-web/-/issues/180) vai envolver a criação de novos endpoints para o frontend validar os campos. Não sei como fazer isso no backend do projeto, e portanto, precisarei fazer em dupla com alguém que tenha conhecimento nisso.

### Mateus de Almeida
- **Tarefas concluídas:** [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222) ampliação da cobertura de teste em `contract.ts` e `graph.ts`.
- **Dificuldades encontradas:** 
- **Relatos:** Trabalhei para aumentar a cobertura de testes do frontend, fazendo testes para os componentes graph e contract, foi verificado o comportamento das interfaces em situações com dados válidos e inválidos, para que seja assegurado o correto funcionamento.

### Pedro Henrique Rodrigues de Carvalho
- **Tarefas concluídas:** [#221](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/221) e [#222](https://gitlab.com/lappis-unb/projetos-energia/mec-energia/mec-energia-api/-/issues/222). Implementação e configuração do Jest para gerar relatórios de cobertura de testes em todo o projeto e aumento da cobertura de testes no frontend, com foco nos arquivos `app.ts`, `person.ts`, `recommendation.ts` e `validation-cnpj.ts`.
- **Dificuldades encontradas:** Algumas dependências em arquivos, como `validation-cnpj.ts`, não estavam bem definidas, o que tornou necessário realizar ajustes no código para facilitar sua testabilidade.
- **Relatos:** A ampliação da cobertura dos testes proporcionou maior confiança na base de código e evidenciou pontos que poderiam ser aprimorados nas implementações já existentes.

### Silas Souza
- **Tarefas concluídas:** 
- **Dificuldades encontradas:** 
- **Relatos:** 
