## Introdução
As histórias de usuário são fundamentais no desenvolvimento ágil de software, especialmente em abordagens como o Scrum, pois auxiliam na captura de necessidades do usuário de forma simples e objetiva. Elas descrevem, sob a perspectiva do usuário final, o que é esperado do sistema, proporcionando um entendimento compartilhado entre as partes interessadas no projeto. Além disso, permitem um alinhamento claro dos objetivos do produto, ajudando a equipe de desenvolvimento a priorizar funcionalidades que gerem maior valor ao usuário. Este documento apresenta as histórias de usuário do aplicativo Bluesky, criadas a partir de uma análise criteriosa dos requisitos e baseadas nas necessidades identificadas durante o processo de elicitação.

## Objetivo
O principal objetivo deste artefato é documentar as histórias de usuário do aplicativo Bluesky, garantindo que:

1. As necessidades e expectativas dos usuários sejam compreendidas e traduzidas em funcionalidades claras e acionáveis.

2. O desenvolvimento seja orientado pela perspectiva do usuário, mantendo o foco na entrega de valor.

3. As funcionalidades sejam priorizadas de acordo com a relevância para os usuários finais e os objetivos do projeto.

4. A comunicação entre a equipe de desenvolvimento e os stakeholders seja clara e eficiente, reduzindo ambiguidades e alinhando expectativas.

Em última análise, este artefato busca assegurar que o Bluesky atenda de forma eficaz às demandas dos usuários, promovendo uma experiência satisfatória e funcional.

## Metodologia
Para a construção das histórias de usuário do aplicativo Bluesky, foi seguido um processo estruturado em três etapas principais:

1.	Elicitação de Requisitos: Aplicamos técnicas de brainstorming, observação, introspecção e questionários para identificar as necessidades dos usuários e requisitos funcionais e não funcionais do aplicativo. As informações coletadas foram organizadas e analisadas para garantir uma compreensão abrangente do contexto do sistema.

2.	Rastreabilidade e Priorização: Os requisitos identificados foram rastreados e associados a funcionalidades específicas, assegurando que nenhum aspecto importante fosse negligenciado. Para priorizar as funcionalidades, utilizamos técnicas como Three Level Scale, First Things Firts e $100.

3.	Elaboração das Histórias de Usuário: As histórias foram redigidas utilizando um formato padrão (como usuário, eu quero… para que…), acompanhadas de critérios de aceitação claros para cada funcionalidade; As histórias foram validadas com base no feedback de stakeholders e ajustadas conforme necessário para refletir com precisão as expectativas dos usuários.

## Participantes
Cada história de usuário foi validada com o PO. Com o objetivo de organização, a tabela 1 mostra a história de usuário, o integrante responsável por tal, Product Owner e usuário participantes. Todos os requisitos elicitados estão presentes no artefato [Requisitos Elicitados](../../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados). 


<center>
<font size="3"><b>Tabela 1:</b> Desenvolvedor e PO</font>

| História de Usuario | Desenvolvedor                          | Product Owner | Usuário | Link levando a gravação |
|:--------------------:|:-------------------------------------:|:-------------:|:-------:|:-------:|
| US01 até US07        | [Renata](https://github.com/Renatinha28) | -             | Amanda      | [Link](#1_a_7)
| US08 até US14        | [Davi Nobre](https://github.com/Jagaima) | -             | -       | - |


<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Histórias de Usuário

A tabela 2 mostra o modelo seguido para cada história de usuário realizada.


<center>
<font size="3"><b>Tabela 2:</b>Modelo para História de Usuário</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | USx |
| Tema | Título |
| Descrição | Eu, como [tipo de usuário], desejo [ação desejada] para [objetivo] |
| Critérios de Aceitação | - [Critério 1] <br> - [Critério 2] <br> ... |
| Prioridade PO | Alta, Média, Baixa |
| Prioridade Usuário | Alta, Média, Baixa |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | Código do requisito |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Histórias de Usuário : requisitos elicitados 1 até 7

As tabelas 3 até 9 descrevem as histórias de usuário realizadas pela integrante [Renata Quadros](https://github.com/Renatinha28)

<a id="US01"></a>

<center>
<font size="3"><b>Tabela 3:</b>História de Usuário: Login</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US01 |
| Tema | Fazer login |
| Descrição | Eu, como usuário, desejo realizar o login no aplicativo Bluesky para acessar minha conta. |
| Critérios de Aceitação | - O sistema deve permitir o login automatico caso o usuário tenha salvo <br> - O sistema deve redirecionar para tela inicial do app após a confirmação do login <br> - O sistema deve permitir o acesso apenas se o usuário e a senha estiverem corretos |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB1](../../PerfilUsuario/Tecnicas/Observacao.md), [IS1](../../PerfilUsuario/Tecnicas/Introspeccao.md), [IS10](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US02"></a>

<center>
<font size="3"><b>Tabela 4:</b>História de Usuário: Recuperar senha</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US02 |
| Tema | Recuperar senha |
| Descrição | Eu, como usuário, desejo recuperar minha senha para acessar o aplicativo Bluesky em caso de esquecimento. |
| Critérios de Aceitação |  - O sistema deve exibir um botão "Esqueci minha senha" na tela de login <br> - O usuário deve receber um e-mail com um link de redefinição de senha no e-mail cadastrado na conta <br> - O link enviado deve expirar após 10 minutos|
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB2](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US03"></a>

<center>
<font size="3"><b>Tabela 5:</b>História de Usuário: Acessar novos conteúdos</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US03 |
| Tema | Acessar novos conteúdos rapidamente |
| Descrição | Eu, como usuário, desejo acessar novos conteúdos rapidamente para estar atualizado com as últimas informações da plataforma. |
| Critérios de Aceitação | - O sistema deve atualizar o feed automaticamente ao abrir o aplicativo <br> - O usuário deve ter a opção de atualizar o feed manualmente  |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB3](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US04"></a>

<center>
<font size="3"><b>Tabela 6:</b>História de Usuário: realizar postagens</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US04 |
| Tema | Realizar postagens |
| Descrição | Eu, como usuário, desejo realizar postagens na plataforma para compartilhar informações e ideias com outros usuários. |
| Critérios de Aceitação | - O sistema deve permitir a criação de postagens com texto e imagens <br> - O botão "publicar" só deve ser habilitado após o preenchimento do campo de texto ou adição de imagem |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB4](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US05"></a>

<center>
<font size="3"><b>Tabela 7:</b>História de Usuário: Editar publicações </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US05 |
| Tema | Editar postagens |
| Descrição | Eu, como usuário, desejo editar minhas publicações já postadas para corrigir erros ou atualizar o conteúdo. |
| Critérios de Aceitação | - O sistema deve permitir edições de postagens já publicadas <br> - O sistema deve exibir uma mensagem de confirmação após a confirmação da edição <br> - O sistema de exibir na publicação editada uma mensagem de "editada" deixando claro quais postagens foram editadas |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada|
| Rastreabilidade | [OB5](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS17](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US06"></a>

<center>
<font size="3"><b>Tabela 8:</b>História de Usuário: Buscar por posts com palavras-chaves </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US06 |
| Tema |  Busca com palavras-chaves |
| Descrição | Eu, como usuário, desejo buscar posts relacionados ao meu interesse utilizando palavras-chave, hashtags ou filtros específicos, para encontrar conteúdos relevantes. |
| Critérios de Aceitação | - O sistema deve permitir ao usuário interir palavras chaves na barra de busca <br> - Os resultados da busca devem ser exibidos ordenados por relevância |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB6](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS2](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="US07"></a>

<center>
<font size="3"><b>Tabela 9:</b>História de Usuário: Favoritar posts ou comunidades </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US07 |
| Tema | Favoritar posts |
| Descrição | Eu, como usuário, desejo favoritar comunidades para acessar rapidamente os conteúdos de maior interesse. |
| Critérios de Aceitação |  - O sistema deve permitir ao usuário favoritar posts por meio de um ícone <br> - Os itens favoritados devem ser salvos na aba de "Favoritos" |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB7](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Validação com Usuário


<a id="1_a_7"></a>

O vídeo 1 contém a verificação das histórias de usuário e backlog do 1 ao 7. Foi realizado pela [Renata Quadros]() com a participação voluntária da Amanda atuando como usuário. Esta gravação foi realizada no dia 15/12/2024 às 16:00.

<div align="center">
    <font size="3">
        <p style="text-align: center">
            <b>Vídeo 1:</b> Validação histórias de usuário e backlog (1 ao 7)
        </p>
    </font>
    <iframe width="560" height="315" 
        src="https://www.youtube.com/embed/AVD3JyGSZm8" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
    <font size="3">
        <p style="text-align: center">
            <b>Autor:</b> Renata Quadros
        </p>
    </font>
</div>

## Histórias de Usuário requisitos elicitados 08 a 14.

As próximas 7 tabelas a seguir contem as histórias de usuário criados pelo usuário [Davi Nobre](https://github.com/Jagaima)

<a id="US08"></a>

<center>
<font size="3"><b>Tabela 10:</b>História de Usuário: criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral.</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US08 |
| Tema | Criar post e compartilha-los num feed. |
| Descrição | Eu, como usuário comum do app, desejo criar uma publicação para que seja vista em um feed específico |
| Critérios de Aceitação | - O sistema deve permitir escolher o feed para postar de acordo com a vontade de seu criador original ("#" ou palavras passe) <br> - O usuário pode ter um post em multiplos feeds <br> ... |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [OB8](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS6](../../PerfilUsuario/Tecnicas/Introspeccao.md) |


<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>


<a id="US09"></a>

<center>
<font size="3"><b>Tabela 11:</b>História de Usuário: Ver mensagens com outros usuários</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US09 |
| Tema | Deve ser possível ver as mensagens com outros usuários |
| Descrição | Eu, como usuário, desejo ver minhas mensagens com outro usuário para recordar um fato que foi conversado |
| Critérios de Aceitação | - As mensagens devem ter data <br> - As mensagens devem ter confirmação de vizualização <br> ... |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [OB9](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

<a id="US10"></a>


<center>
<font size="3"><b>Tabela 12:</b>História de Usuário: Editar o conteúdo do perfil</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US10 |
| Tema | Deve ser possível editar o conteúdo do perfil |
| Descrição | Eu, como usuário, desejo editar meu perfil para mudar a aparência da minha página principal |
| Critérios de Aceitação | - O numéro de vezes editado deve ser ilimitado <br> - O link conector (ex: .bsky.social) só pode ser mudado uma vez a cada 3 meses <br> ... |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [OB10](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS12](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>



<a id="US11"></a>

<center>
<font size="3"><b>Tabela 13:</b>História de Usuário: Notificar o usuário de posts com base em seus interesses</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US11 |
| Tema | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. |
| Descrição | Eu, como usuário, desejo receber notificações de posts relacionados ao que gosto para conhecer novas contas a seguir e ficar atualizado. |
| Critérios de Aceitação | - O numéro de vezes que a notificação é enviada no dia não deve exceder 3 <br> - se o usuário não abre as notificações normalmente, sua frequência deve ser de duas por semana <br> ... |
| Prioridade PO | Baixa |
| Prioridade Usuário | Baixa |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [OB12](../../PerfilUsuario/Tecnicas/Observacao.md), [IS7](../../PerfilUsuario/Tecnicas/Introspeccao.md) e [BT3](../../PerfilUsuario/Tecnicas/Brainstorm.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

<a id="US12"></a>

<center>
<font size="3"><b>Tabela 14:</b>História de Usuário: Salvar posts de interesse</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US12 |
| Tema | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. |
| Descrição | Eu, como usuário, desejo salvar posts relacionados ao que gosto para os rever quando quiser facilmente e manter nota de postagens importantes |
| Critérios de Aceitação | - O usuário deve ter uma confirmação imediata que teve o post salvo <br> - se o usuário tem a conta privada, seus post não podem ir para nenhum itens salvos <br> ... |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [IS3](../../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS22](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

<a id="US13"></a>

<center>
<font size="3"><b>Tabela 15:</b>História de Usuário: Gerẽnciar seus posts salvos por data e/ou hashtag </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US13 |
| Tema | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag. |
| Descrição | Eu, como usuário, desejo gerênciar meus posts salvos relacionados ao que gosto para me organizar com o que ainda preciso ou não. |
| Critérios de Aceitação | - O usuário pode remover posts <br> - se o usuário original apagar o post, ele irá sumir do itens salvos e o usuário será notificado <br> ... |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [IS4](../../PerfilUsuario/Tecnicas/Introspeccao.md)|

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

<a id="US14"></a>

<center>
<font size="3"><b>Tabela 16:</b>História de Usuário: Criar ou participar de feeds de com base em critérios como tipo de post, hashtag e usuários. </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US14 |
| Tema | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. |
| Descrição | Eu, como usuário, desejo participar ou criar um feed para ter um espaço sobre um tipo de conteúdo que me relaciono. |
| Critérios de Aceitação | - O usuário chefe pode definir quem vai ou não pro feed <br> - O feed pode ter alguma função específica EX: o feed programado para mostrar os post mais populares de uma conta <br> ... |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | [IS5](../../PerfilUsuario/Tecnicas/Introspeccao.md)|

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## Histórias de Usuário requisitos elicitados 15 a 23.

As próximas 9 tabelas a seguir contém as histórias de usuário criados pelo integrante [João Ribeiro](https://github.com/Joa0V)

<a id="US15"></a>

<center>
<font size="3"><b>Tabela 17:</b>História de Usuário: Interagir com postagens por comentários, curtidas e respostas.</font>

|             Item             |                                                                                                 Descrição                                                                                                  |
| :--------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                                                    US15                                                                                                    |
|             Tema             |                                                                                          Publicações e Interações                                                                                          |
|          Descrição           |                                   Eu, como usuário, desejo interagir com postagens por meio de comentários, curtidas e respostas para me expressar sobre uma publicação.                                   |
|    Critérios de Aceitação    | - O aplicativo deve permitir fazer comentários e curtir uma publicação tanto em sua exibição em um feed quanto em sua página própria<br> - As respostas devem ser feitas à comentários ou outras respostas |
|        Prioridade PO         |                                                                                                    Alta                                                                                                    |
|      Prioridade Usuário      |                                                                                                    Alta                                                                                                    |
|            Status            |                                                                               Se a história foi Validada ou não pelo usuário                                                                               |
|       Rastreabilidade        |                                                                                                    [RF15](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS8](../../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS16](../../PerfilUsuario/Tecnicas/Introspeccao.md) e [QT2](../../PerfilUsuario/Tecnicas/Questionario.md)                                                                                                    |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US16"></a>

<center>
<font size="3"><b>Tabela 18:</b>História de Usuário: Pesquisar publicações com filtros avançados.</font>

|             Item             |                                                                                                                       Descrição                                                                                                                        |
| :--------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                                                                          US16                                                                                                                          |
|             Tema             |                                                                                                                Publicações e Interações                                                                                                                |
|          Descrição           |                                              Eu, como usuário, desejo pesquisar publicações com filtros como autor do post, data de publicação ou popularidade, para melhorar minha experiência de busca.                                              |
|    Critérios de Aceitação    | - Os filtros podem ser adicionados ou excluídos durante uma pesquisa<br>- Todos os filtros de uma pesquisa devem poder ser excluídos de uma só vez<br>- As mudanças de filtro devem ser refletidas nos resultados das pesquisas em menos de 3 segundos |
|        Prioridade PO         |                                                                                                                          Alta                                                                                                                          |
|      Prioridade Usuário      |                                                                                                                          Alta                                                                                                                          |
|            Status            |                                                                                                     Se a história foi Validada ou não pelo usuário                                                                                                     |
|       Rastreabilidade        |                                                                                                                       [RF16](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS9](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                                                                        |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US17"></a>

<center>
<font size="3"><b>Tabela 19:</b>História de Usuário: Fazer log-in automático.</font>

|             Item             |                                                                  Descrição                                                                  |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                    US17                                                                     |
|             Tema             |                                                   Autenticação e Configurações de Usuário                                                   |
|          Descrição           |      Eu, como usuário, desejo fazer log-in automático em minha conta criada agilizar o início do uso do sistema em cada sessão de uso.      |
|    Critérios de Aceitação    | - O log-in automático deve ser explicitamente autorizado pelo usuário por uma checkbox<br>- O log-in automático deve poder ser desabilitado |
|        Prioridade PO         |                                                             Alta, Média, Baixa                                                              |
|      Prioridade Usuário      |                                                             Alta, Média, Baixa                                                              |
|            Status            |                                               Se a história foi Validada ou não pelo usuário                                                |
|       Rastreabilidade        |                                                                 [RF17](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS11](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                  |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US18"></a>

<center>
<font size="3"><b>Tabela 20:</b>História de Usuário: Fixar publicação no perfil.</font>

|             Item             |                                                               Descrição                                                               |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                 US18                                                                  |
|             Tema             |                                                       Publicações e Interações                                                        |
|          Descrição           |         Eu, como usuário, desejo fixar uma publicação em seu perfil para dar destaque a publicação importante em meu perfil.          |
|    Critérios de Aceitação    | - A publicação destacada deve ser a primeira a ser exibida no perfil do usuário<br>- A publicação destacada deve poder ser desafixada |
|        Prioridade PO         |                                                         Média                                                         |
|      Prioridade Usuário      |                                                          Média                                                       |
|            Status            |                                            Se a história foi Validada ou não pelo usuário                                             |
|       Rastreabilidade        |                                                              [RF18](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS13](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                               |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US19"></a>

<center>
<font size="3"><b>Tabela 21:</b>História de Usuário: Tornar a conta privada.</font>

|             Item             |                                                               Descrição                                                               |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                 US19                                                                  |
|             Tema             |                                                       Publicações e Interações                                                        |
|          Descrição           |         Eu, como usuário, desejo tornar minha conta privada para permitir que apenas seguidores consigam interagir diretamente comigo |
|    Critérios de Aceitação    | - A publicação destacada deve ser a primeira a ser exibida no perfil do usuário<br>- A publicação destacada deve poder ser desafixada |
|        Prioridade PO         |                                                          Alta                                                          |
|      Prioridade Usuário      |                                                          Alta                                                          |
|            Status            |                                            Se a história foi Validada ou não pelo usuário                                             |
|       Rastreabilidade        |     [RF19](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS14](../../PerfilUsuario/Tecnicas/Introspeccao.md)                        |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US20"></a>

<center>
<font size="3"><b>Tabela 22:</b>História de Usuário: Fazer publicações com texto, imagens e vídeos.</font>

|             Item             |                                                                                                                      Descrição                                                                                                                       |
| :--------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                                                                         US20                                                                                                                         |
|             Tema             |                                                                                                               Publicações e Interações                                                                                                               |
|          Descrição           |                                                               Eu, como usuário, desejo fazer publicações contendo texto, imagens e vídeos para melhor me comunicar por meio dos posts.                                                               |
|    Critérios de Aceitação    | - O conteúdo da publicação deve poder ser adicionado, modificado ou excluído durante a criação da publicação de acordo com a vontade de seu criador.<br>- Uma pré-visualização de imagens e vídeos deve ser exibida antes da postagem da publicação. |
|        Prioridade PO         |                                                                                                                         Alta                                                                                                                         |
|      Prioridade Usuário      |                                                                                                                         Alta                                                                                                                         |
|            Status            |                                                                                                    Se a história foi Validada ou não pelo usuário                                                                                                    |
|       Rastreabilidade        |                                                                                                                      [RF20](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS15](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                                                                      |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US21"></a>

<center>
<font size="3"><b>Tabela 23:</b>História de Usuário: Vizualizar tradução de publicação.</font>

|             Item             |                                                                                        Descrição                                                                                        |
| :--------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                                          US21                                                                                           |
|             Tema             |                                                                                Publicações e Interações                                                                                 |
|          Descrição           | Eu, como usuário, desejo visualizar publicações de diferentes idiomas traduzidas para meu idioma principal dentro do aplicativo para compreender usuários que falam diferentes línguas. |
|    Critérios de Aceitação    |                      - A tradução deve ser disponibilizada na mesma página da publicação<br>- Caso haja impossibilidade de tradução, o usuário deve ser sinalizado                      |
|        Prioridade PO         |                                                                                          Alta                                                                                           |
|      Prioridade Usuário      |                                                                                          Alta                                                                                           |
|            Status            |                                                                     Se a história foi Validada ou não pelo usuário                                                                      |
|       Rastreabilidade        |                                                                                       [RF21](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS18](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                                        |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US22"></a>

<center>
<font size="3"><b>Tabela 24:</b>História de Usuário: Enviar mensagens diretas a outro usuário.</font>

|             Item             |                                                                             Descrição                                                                             |
| :--------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                               US22                                                                                |
|             Tema             |                                                                        Comunicação direta                                                                         |
|          Descrição           |             Eu, como usuário, desejo mandar mensagens diretas a outro usuário, caso nos sigamos mutualmente para poder me comunicar de forma privada.             |
|    Critérios de Aceitação    | - As mensagens diretas podem ser acessadas somente por usuários que façam parte do canal de comunicação privado <br>- Deve ser possível sair de conversas diretas |
|        Prioridade PO         |                                                                               Média                                                                               |
|      Prioridade Usuário      |                                                                               Média                                                                               |
|            Status            |                                                          Se a história foi Validada ou não pelo usuário                                                           |
|       Rastreabilidade        |                                                                            [RF22](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS19](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                             |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US23"></a>

<center>
<font size="3"><b>Tabela 25:</b>História de Usuário: Participar de grupos de mensagens privadas.</font>

|             Item             |                                                                                                                                     Descrição                                                                                                                                      |
| :--------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| USx(número de identificação) |                                                                                                                                        US23                                                                                                                                        |
|             Tema             |                                                                                                                                 Comunicação direta                                                                                                                                 |
|          Descrição           |                                                               Eu, como usuário, desejo participar de grupos de mensagens privadas para poder me comunicar de forma privada com um grupo restrito de outros usuários.                                                               |
|    Critérios de Aceitação    | - As mensagens de de grupos de mensagens privadas podem ser acessadas somente por usuários que façam parte do canal de comunicação privado<br>- Deve ser possível convidar usuários para o grupo de mensagens privadas<br>- Deve ser possível sair de grupos de mensagens privadas |
|        Prioridade PO         |                                                                                                                                       Média                                                                                                                                        |
|      Prioridade Usuário      |                                                                                                                                       Média                                                                                                                                        |
|            Status            |                                                                                                                   Se a história foi Validada ou não pelo usuário                                                                                                                   |
|       Rastreabilidade        |                                                                                                                                     [RF23](../../PerfilUsuario/Tecnicas/Requisitosel.md), [IS20](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                                                                                     |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="US24"></a>

<center>
<font size="3"><b>Tabela 26:</b>O usuário deve poder mandar mídias como vídeos e áudios nas mensagens privadas.</font>


| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US24                                                                         |
| **Tema**                     | Enviar mídias em mensagens privadas                                           |
| **Descrição**                | Eu, como usuário, desejo enviar vídeos e áudios em mensagens privadas para compartilhar conteúdos de forma mais completa e interativa. |
| **Critérios de Aceitação**   | - O sistema deve permitir o envio de arquivos de vídeo e áudio em mensagens privadas. <br> - O sistema deve exibir uma mensagem de sucesso após o envio da mídia. <br> - O sistema deve notificar o destinatário sobre a nova mensagem contendo mídia. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS21](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                   |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US25"></a>


<center>
<font size="3"><b>Tabela 27:</b>O usuário deve poder criar, modificar e excluir suas listas de perfis de interesse.</font>


| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US25                                                                         |
| **Tema**                     | Listas de perfis de interesse                                                 |
| **Descrição**                | Eu, como usuário, desejo criar, modificar e excluir minhas listas de perfis de interesse para organizar melhor minhas conexões e interações. |
| **Critérios de Aceitação**   | - O sistema deve permitir a criação de novas listas de perfis de interesse. <br> - O sistema deve permitir a modificação de listas existentes. <br> - O sistema deve permitir a exclusão de listas de perfis de interesse. <br> - O sistema deve exibir uma mensagem de confirmação após a criação, modificação ou exclusão de uma lista. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS23](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                   |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US26"></a>

<center>
<font size="3"><b>Tabela 28:</b>Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de perfis de interesse para ter/deixar de ter acesso às publicações desses perfis por uma aba.</font>

| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US26                                                                         |
| **Tema**                     | Inscrição em listas de perfis de interesse                                    |
| **Descrição**                | Eu, como usuário, desejo inscrever-me ou deixar de ser inscrito em listas de perfis de interesse para ter ou deixar de ter acesso às publicações desses perfis por meio de uma aba. |
| **Critérios de Aceitação**   | - O sistema deve permitir que o usuário se inscreva em listas de perfis de interesse. <br> - O sistema deve permitir que o usuário se desinscreva de listas de perfis de interesse. <br> - O sistema deve exibir uma aba com as publicações dos perfis aos quais o usuário está inscrito. <br> - O sistema deve atualizar a aba e as publicações conforme o status de inscrição ou desinscrição. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS24](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                    |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US27"></a>


<center>
<font size="3"><b>Tabela 29:</b>O usuário deve poder criar, modificar e excluir suas listas de moderação.</font>

| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US27                                                                         |
| **Tema**                     | Listas de moderação                                                           |
| **Descrição**                | Eu, como usuário, desejo criar, modificar e excluir minhas listas de moderação para gerenciar melhor os perfis e conteúdos que preciso monitorar. |
| **Critérios de Aceitação**   | - O sistema deve permitir a criação de novas listas de moderação. <br> - O sistema deve permitir a modificação de listas de moderação existentes. <br> - O sistema deve permitir a exclusão de listas de moderação. <br> - O sistema deve exibir uma mensagem de confirmação após a criação, modificação ou exclusão de uma lista de moderação. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS25](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                   |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US28"></a>


<center>
<font size="3"><b>Tabela 30:</b>Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de moderação para não permitir/permitir a interação com os perfis contidos na lista.</font>

| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US28                                                                         |
| **Tema**                     | Inscrição em listas de moderação                                              |
| **Descrição**                | Eu, como usuário, desejo inscrever-me ou deixar de ser inscrito em listas de moderação para permitir ou não a interação com os perfis contidos na lista. |
| **Critérios de Aceitação**   | - O sistema deve permitir que o usuário se inscreva em listas de moderação. <br> - O sistema deve permitir que o usuário se desinscreva de listas de moderação. <br> - O sistema deve permitir ou restringir a interação com os perfis contidos na lista de moderação, dependendo do status de inscrição ou desinscrição do usuário. <br> - O sistema deve exibir uma mensagem de confirmação após a inscrição ou desinscrição de uma lista de moderação. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS26](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                  |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US29"></a>


<center>
<font size="3"><b>Tabela 31:</b>O usuário deve poder visualizar a quantidade de vezes em que sua publicação foi visualizada.</font>

| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US29                                                                         |
| **Tema**                     | Visualização de contagem de visualizações de publicações                       |
| **Descrição**                | Eu, como usuário, desejo visualizar a quantidade de vezes em que minha publicação foi visualizada para entender o engajamento com o meu conteúdo. |
| **Critérios de Aceitação**   | - O sistema deve exibir a contagem de visualizações de cada publicação do usuário. <br> - O sistema deve atualizar a contagem de visualizações em tempo real, sempre que a publicação for acessada. <br> - O sistema deve exibir a contagem de visualizações de forma clara e acessível. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Média                                                                        |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [IS27](../../PerfilUsuario/Tecnicas/Introspeccao.md)                                                                  |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="US30"></a>


<center>
<font size="3"><b>Tabela 32:</b>O aplicativo deve permitir ao usuário a comunicação, entreterimento e informações atualizadas.</font>

| **Item**                     | **Descrição**                                                                 |
|------------------------------|------------------------------------------------------------------------------|
| **USx(número de identificação)** | US30                                                                         |
| **Tema**                     | Comunicação, entretenimento e informações atualizadas                         |
| **Descrição**                | Eu, como usuário, desejo que o aplicativo me permita comunicação, entretenimento e informações atualizadas, para que eu possa me manter informado e engajado com o conteúdo. |
| **Critérios de Aceitação**   | - O sistema deve permitir a comunicação em tempo real entre os usuários. <br> - O sistema deve oferecer opções de entretenimento, como vídeos, jogos ou conteúdo multimídia. <br> - O sistema deve fornecer informações atualizadas, como notícias, eventos e alertas relevantes. <br> - O sistema deve garantir que o conteúdo seja atualizado de forma contínua e eficiente. |
| **Prioridade PO**            | Alta                                                                         |
| **Prioridade Usuário**       | Alta                                                                         |
| **Status**                   | Validada                                                                     |
| **Rastreabilidade**          | [QT1](../../PerfilUsuario/Tecnicas/Questionario.md)                                                                  |


<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>


#### Gravação com o PO

#### Gravação com o Usuário

## Bibliografia

> 1. DIOGO. Guia definitivo para Histórias de Usuário - Product Management. YouTube, 11 jul. 2022. Disponível em: https://www.youtube.com/watch?v=pLJ3LxR292w.

> 2. 2023.2 Economia DF. Econimia DF, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 15, nov. 2024.

> 3. Meu INSS, 2024.1. Disponível em: https://vitorfleonardo.github.io/2024.1-Meu-INSS/. Acesso em 16, nov. 2024.

## :round_pushpin: Histórico de Versão 

<div align="center">
    <table>
        <tr>
            <th>Data</th>
            <th>Versão</th>
            <th>Descrição</th>
            <th>Autor</th>
            <th>Data da Revisão</th>
            <th>Revisor</th>
        </tr>
        <tr>
        <td>14/12</td>
            <td>1.0</td>
            <td>Criação do documento e histórias de usuário de 1 até 7 </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
        <td>14/12</td>
            <td>1.1</td>
            <td>Criação do documento e histórias de usuário de 8 até 14 </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>15/12</td>
            <td>1.2</td>
            <td>Criação das histórias de usuário de 15 até 23 </td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>16/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>16/12</td>
            <td>1.3</td>
            <td>Criação das histórias de usuário de 24 até 30 </td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td></td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>