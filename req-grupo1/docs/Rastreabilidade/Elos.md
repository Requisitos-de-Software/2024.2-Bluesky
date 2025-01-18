## Introdução 
O presente documento exploramos os conceitos e metodologias fundamentados no Meta-modelo de Toranzo. Este modelo fornece diretrizes para organizar e representar os elementos e relacionamentos essenciais na análise de requisitos, garantindo um entendimento estruturado e rastreável. A análise é realizada com base nos elos de conexão entre categorias, enfatizando a importância dos vínculos entre os elementos do sistema, como requisitos, objetivos organizacionais e recursos. Além disso, um modelo de cartão é utilizado como instrumento para documentar e visualizar as interações entre os elos e categorias de forma clara e prática.

Utilizamos os elos Backward-from e Forward-from, que desempenham papéis fundamentais na análise e rastreabilidade dos requisitos.

### Elos Backward-from: 
-	Indicam a origem de um requisito ou elemento, ou seja, mostram de onde ele foi derivado. <sup>[2](#ref2)

-	São usados para rastrear o raciocínio ou a justificativa para a existência de um determinado elemento.


###	Elos Forward-from:
-	Mostram como um requisito ou elemento está relacionado a outros, destacando como ele contribui para a satisfação ou implementação de outro elemento. <sup>[2](#ref2)

-	Facilitam o acompanhamento do impacto de um requisito em diferentes partes do sistema.


A inclusão dos elos Backward-from e Forward-from permite não apenas rastrear os requisitos de forma eficiente, mas também identificar lacunas ou inconsistências no sistema.

## Objetivo
O objetivo deste documento é detalhar a estruturação dos requisitos do aplicativo Bluesky, utilizando o Meta-modelo de Toranzo como base.

## Metodologia 
 A tabela 1 representa um cartão feito pelos integrantes do grupo, adaptado como referência ao slide dos professores Milene Serrano e Maurício Serrano (páginas 22 à 27)<sup>[1](#ref1). O cartão aborda os tipos de elos e as categorias derivadas do Meta-modelo de Toranzo.

<center>
<font size="3"><b>Tabela 1:</b> Modelo de cartão </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | qual requisito está tratando |
| **Categoria** | Ambiental, Organizacional, Gerencial ou Desenvolvimento |
| **Elementos** | Elementos rastreavéis |
| **Elos Backward-from** | Tipo de elo - Origem |
| **Elos Forward-from** | Tipo de elo - Relação | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Legenda do modelo de cartão 

- Categoria: Classificadas em quatro níveis. 
    - Ambiental: Refere-se ao contexto externo no qual o sistema será inserido. Considera todos os fatores e restições externos que podem influenciar o sistema, como fatores legais; cultura e sociedade; tecnologia disponível. 
    - Organizacional: Foca na organização que está desenvolvento. Analisa elementos internos, como objetivos; estratégias.
    - Gerencial: Refere-se a informações que auxiliam a gerência do projeto, como planejamento; comunicação.
    - Desenvolvimento: Abrange os aspectos técnicos diretamente relacionados à construção e implementação do sistema, como artefatos de requisitos; códigos.

- Elementos: Identificadores para:
    - requisito (RFx - para requisitos funcionais e RNFx - para requisitos não funcionais)
    -  Caso de uso(UCx)
    -  Cenário(CENx)
    -  História de usuário (USx)
    -  Técnica de elicitação(OBx - Observação, ISx - Introspecção funcional, NIS - Introspecção para os não funcionais, BTx - Brainstorm, QTx - Questionário)
    - NFR Framework (NFRx)
    - Especificação suplementar (RUx, RCx, RDx, RSx, RDEx, RINx, RFIx)

- Elos Backward-from: Mostra-se o tipo de elo e a origem do requisito.

- Elos Forward-from: Mostra-se o tipo de elo e como o requisito é satisfeito ou relacionado a outros elementos.

- Tipos de Elos: 
    - Satisfação: Relacionado ao cumprimento de expectativas ou demandas.
    - Recurso: Conecta elementos que fornecem ou utilizam recursos necessários, podendo ser uma pessoa, equipe, tempo, orçamento, etc.
    - Responsabilidade: Relaciona quem ou o que é responsável por determinados elementos ou atividades. 
    - Representação: Conecta elementos de representação ou abstração de algo. 
    - Alocado: Representa a alocação de recursos, funcionalidades ou responsabilidades.
    - Agregação: Indica a composição de elementos para formar um todo.

- Print: Imagem/protótipo da implementação


## E01
As tabelas 2, 3, 4, 5, 6, 7 e 8 representam os cartões de requisitos funcionais feitos pela integrante [Renata Quadros](https://github.com/Renatinha28).

<center>
<font size="3"><b>Tabela 2:</b> E01 - Cartão do Requisito Funcional 01 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível realizar o login no Bluesky |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RF01](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB01](../PerfilUsuario/Tecnicas/Observacao.md), [IS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [IS10](../PerfilUsuario/Tecnicas/Introspeccao.md), [US01](../Modelagem/Cenario.md)  |
| **Elos Backward-from** | **Agregação** - [OB01](../PerfilUsuario/Tecnicas/Observacao.md), [IS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [IS10](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Observação e da Introspecção |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US01](../Modelagem/Agil/historia.md) satisfaz o requisito [RF01](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o usuário deve conseguir realizar o login no Bluesky <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 1.1 do [Backlog](../Modelagem/Agil/Backlog.md)  | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E02

<center>
<font size="3"><b>Tabela 3:</b> E02 - Cartão do Requisito Funcional 02 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível recuperar a senha |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RF02](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB02](../PerfilUsuario/Tecnicas/Observacao.md),[US02](../Modelagem/Agil/historia.md)  |
| **Elos Backward-from** | **Agregação** - [OB02](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Observação  |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US03](../Modelagem/Agil/historia.md) satisfaz o requisito [RF02](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar a necessidade de recuperação de senha <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 1.2 do [Backlog](../Modelagem/Agil/Backlog.md)   | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E03

<center>
<font size="3"><b>Tabela 4:</b> E03 - Cartão do Requisito Funcional 03 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | - |
| **Categoria** | -|
| **Elementos** | - |
| **Elos Backward-from** | - |
| **Elos Forward-from** | - | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E04

<center>
<font size="3"><b>Tabela 5:</b> E04 - Cartão do Requisito Funcional 04 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível realizar postagens na plataforma |
| **Categoria** | Desenvolvimento |
| **Elementos** |  [RF04](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB04](../PerfilUsuario/Tecnicas/Observacao.md),[US04](../Modelagem/Agil/historia.md) |
| **Elos Backward-from** | **Agregação** - [OB04](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Técnica de Observação |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US04](../Modelagem/Agil/historia.md) satisfaz o requisito [RF04](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em realizar postagens  <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.2 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E05

A tabela 6 representa a funcionalidade não implementada escolhida pela integrante Renata Quadros. 

<center>
<font size="3"><b>Tabela 6:</b> E05 - Cartão do Requisito Funcional 05 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível editar uma postagem na plataforma |
| **Categoria** | Desenvolvimento |
| **Elementos** |  [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB05](../PerfilUsuario/Tecnicas/Observacao.md), [IS17](../PerfilUsuario/Tecnicas/Introspeccao.md), [US05](../Modelagem/Agil/historia.md) |
| **Elos Backward-from** | **Agregação** - [OB05](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Técnica de Observação e da técnica de Introspecção  [IS17](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US05](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em editar suas publicações <br> **Satisfação** - O requisito recebeu $4 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização média na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.3 do [Backlog](../Modelagem/Agil/Backlog.md) <br> **Satisfação** - o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) deu origem ao caso de uso [UC05](../Modelagem/Caso_de_uso.md) <br> **Satisfação** - o requisito deu origem ao cenário [CEN05](../Modelagem/Cenario.md) | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E06

<center>
<font size="3"><b>Tabela 7:</b> E06 - Cartão do Requisito Funcional 06 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. |
| **Categoria** | Desenvolvimento |
| **Elementos** |  [RF06](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB06](../PerfilUsuario/Tecnicas/Observacao.md), [IS02](../PerfilUsuario/Tecnicas/Introspeccao.md), [US06](../Modelagem/Agil/historia.md) |
| **Elos Backward-from** | **Agregação** - [OB06](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Técnica de Observação e da técnica de Introspecção  [IS02](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US06](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em fazer buscas por posts de seu interesse com palavras-chaves <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.4 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E07

<center>
<font size="3"><b>Tabela 8:</b> E07 - Cartão do Requisito Funcional 07 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível favoritar uma comunidade |
| **Categoria** | Desenvolvimento |
| **Elementos** | [OB07](../PerfilUsuario/Tecnicas/Observacao.md), [US07](../Modelagem/Agil/historia.md) |
| **Elos Backward-from** | **Agregação** - [OB07](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Técnica de Observação  |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US07](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em favoritar uma comunidade  <br> **Satisfação** - O requisito recebeu $8 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.5 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E08
## E09
## E10
## E11
.
.
.
## E35
## E36
## E37
>>>>>>>>>>>>>
>>>>>>>> começa os não funcionais (obs: n tem a linha de print)
>>>>>>>>>>>>>>>
## E38

As tabelas 39, 40, 41 e 42 representam os cartões de requisitos não funcionais feitos pela integrante [Renata Quadros](https://github.com/Renatinha28).

<center>
<font size="3"><b>Tabela 39:</b> E38 - Cartão do Requisito Não Funcional 01 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RNF01](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB11](../PerfilUsuario/Tecnicas/Observacao.md), [NFR04](../Modelagem/Agil/NFRs.md), [RDE01](../Modelagem/Especificacao.md)  |
| **Elos Backward-from** | **Agregação** - [OB11](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Técnica de Observação  |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RDE01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF01](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $10 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md)    | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E39


<center>
<font size="3"><b>Tabela 40:</b> E39 - Cartão do Requisito Não Funcional 02 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantin do uma experiência fluida para o usuário. |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RNF02](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT07](../PerfilUsuario/Tecnicas/Brainstorm.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [NFR05](../Modelagem/Agil/NFRs.md), [RD01](../Modelagem/Especificacao.md)  |
| **Elos Backward-from** | **Agregação** - [BT07](../PerfilUsuario/Tecnicas/Observacao.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Brainstorm e da Introspecção  |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RD01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF02](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E40

<center>
<font size="3"><b>Tabela 41:</b> E40 - Cartão do Requisito Não Funcional 03 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** |O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. |
| **Categoria** | Ambiental |
| **Elementos** | [RNF03](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT07](../PerfilUsuario/Tecnicas/Brainstorm.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [NIS13](../PerfilUsuario/Tecnicas/Introspeccao.md) [NFR06](../Modelagem/Agil/NFRs.md), [RD02](../Modelagem/Especificacao.md)  |
| **Elos Backward-from** | **Agregação** - [BT07](../PerfilUsuario/Tecnicas/Observacao.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [NIS13](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Brainstorm e da Introspecção |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RD02](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF03](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E41

<center>
<font size="3"><b>Tabela 42:</b> E41 - Cartão do Requisito Não Funcional 04 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** |Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. |
| **Categoria** | Ambiental |
| **Elementos** | [RNF04](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS03](../PerfilUsuario/Tecnicas/Introspeccao.md), [NFR10](../Modelagem/Agil/NFRs.md), [RC01](../Modelagem/Especificacao.md)  |
| **Elos Backward-from** | **Agregação** -  [NIS03](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Introspecção |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RC01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF04](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Referências Bibliográficas 
> 1. <a id="ref1"></a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 17 jan. 2025.

> 2. <a id="ref2"></a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 17 jan. 2025.

## Bibliografia

> 1. WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf. Acesso em: 17 jan. 2025.

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
            <td>17/01/2025</td>
            <td>1.0</td>
            <td>Criação do documento; elos 1 ao 7 e 38 ao 41 </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>18/01/2025</td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>