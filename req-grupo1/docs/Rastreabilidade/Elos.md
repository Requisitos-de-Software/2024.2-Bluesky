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
    - Ambiental: Refere-se ao contexto externo no qual o sistema será inserido. Considera todos os fatores e restrições externas que podem influenciar o sistema, como fatores legais; cultura e sociedade; tecnologia disponível. 
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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,52 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** - A história de usuário [US01](../Modelagem/Agil/historia.md) satisfaz o requisito [RF01](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o usuário deve conseguir realizar o login no Bluesky <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 1.1 do [Backlog](../Modelagem/Agil/Backlog.md)  | 
| **Print** | [Imagem](../assets/images/elo1.jpeg) |

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,31 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** - A história de usuário [US02](../Modelagem/Agil/historia.md) satisfaz o requisito [RF02](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar a necessidade de recuperação de senha <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 1.2 do [Backlog](../Modelagem/Agil/Backlog.md)   | 
| **Print** | [Imagem](../assets/images/elo2.jpeg) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E03

<center>
<font size="3"><b>Tabela 4:</b> E03 - Cartão do Requisito Funcional 03 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve permitir que o usuário acesse novos conteúdos na plataforma em até 3 segundos após realizar uma ação de navegação |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RF03](../PerfilUsuario/Tecnicas/Requisitosel.md), [OB03](../PerfilUsuario/Tecnicas/Observacao.md),[US03](../Modelagem/Agil/historia.md) |
| **Elos Backward-from** |  [OB03](../PerfilUsuario/Tecnicas/Observacao.md) O requisito originou-se da Observação |
| **Elos Forward-from** | **Satisfação** - A história de usuário [US03](../Modelagem/Agil/historia.md) satisfaz o requisito [RF03](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização média na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.1 do [Backlog](../Modelagem/Agil/Backlog.md)  | 
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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,58 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** - A história de usuário [US04](../Modelagem/Agil/historia.md) satisfaz o requisito [RF04](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em realizar postagens  <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.2 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | [Imagem](../assets/images/elo4.jpeg) |

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,73 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** - A história de usuário [US05](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em editar suas publicações <br> **Satisfação** - O requisito recebeu $4 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização média na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.3 do [Backlog](../Modelagem/Agil/Backlog.md) <br> **Satisfação** - o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) deu origem ao caso de uso [UC05](../Modelagem/Caso_de_uso.md) <br> **Satisfação** - o requisito deu origem ao cenário [CEN05](../Modelagem/Cenario.md) | 
| **Print** | <iframe width="800" height="450" src="https://www.figma.com/embed?embed_host=markdown&url=https://www.figma.com/proto/gxIX8ULMSe6gf3Ii6dnyVu/Untitled?node-id=1-795&p=f&t=EUO7BdW0OlFonVSV-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A795" allowfullscreen></iframe>|

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 1,06 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** - A história de usuário [US06](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em fazer buscas por posts de seu interesse com palavras-chaves <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.4 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | [Imagem](../assets/images/elo5.jpeg) |

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,47 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br>  **Satisfação** - A história de usuário [US07](../Modelagem/Agil/historia.md) satisfaz o requisito [RF05](../PerfilUsuario/Tecnicas/Requisitosel.md) ao representar a necessidade do usuário em favoritar uma comunidade  <br> **Satisfação** - O requisito recebeu $8 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> **Agregação** - O requisito é classificado no Épico 2.5 do [Backlog](../Modelagem/Agil/Backlog.md)    | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E08

<center>
<font size="3"><b>Tabela 9:</b> E08 - Cartão do requisito funcional 08 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O usuário deve poder criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral. |
| **Categoria** | Ambiental |
| **Elementos** | [OB8](../PerfilUsuario/Tecnicas/Observacao.md) e [IS6](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Backward-from** | Agregação - [IS6](../PerfilUsuario/Tecnicas/Introspeccao.md) Originou E08 pela técnica de Introspecção |
| **Elos Forward-from** | Satisfação - A história de usuário [IS6](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF08 ao representar a necessidade do usuário em postar em um FEED <br> Satisfação - O requisito é tido como médio no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação -O requisito recebeu $3.5 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US08 é classificado no épico 2.6 no [Backlog](../Modelagem/Agil/Backlog.md) | 
| **Print** | [Imagem](../assets/images/elo8.jpeg) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E09

<center>
<font size="3"><b>Tabela 10: </b> E09 - Cartão do requisito funcional 09 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível ver as mensagens com outros usuários |
| **Categoria** | Ambiental |
| **Elementos** | [OB9](../PerfilUsuario/Tecnicas/Observacao.md) |
| **Elos Backward-from** | Agregação - [OB9](../PerfilUsuario/Tecnicas/Observacao.md) Originou E09 pela técnica de Observação |
| **Elos Forward-from** | Satisfação - A história de usuário [OB9](../PerfilUsuario/Tecnicas/Observacao.md) satisfaz o requisito RF09 ao representar a necessidade do usuário em visualizar e enviar mensagens a outros usuários, O requisito é tido como médio no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $19 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US09 é classificado no épico 2.7 no [Backlog](../Modelagem/Agil/Backlog.md) <br> Satisfação - O requisito tem a prioridade 0,07 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md)  | 
| **Print** | [Imagem](../assets/images/elo09.jpeg) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E10

<center>
<font size="3"><b>Tabela 11: </b> E10 - Cartão do requisito funcional 10 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | Deve ser possível editar o conteúdo do perfil |
| **Categoria** | Ambiental |
| **Elementos** | [OB10](../PerfilUsuario/Tecnicas/Observacao.md) e [IS12](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Backward-from** | Agregação - [OB10](../PerfilUsuario/Tecnicas/Observacao.md) Originou E10 pela técnica de Observação também pela técnica de introspecção com [IS12](../PerfilUsuario/Tecnicas/Introspeccao.md)|
| **Elos Forward-from** | Satisfação - A história de usuário [OB10](../PerfilUsuario/Tecnicas/Observacao.md) e [IS12](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF10 ao representar a necessidade do usuário em editar seu perfil. <br> O requisito é tido como alto no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $9 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US10 é classificado no épico 1.3 no [Backlog](../Modelagem/Agil/Backlog.md) <br> Satisfação - O requisito tem a prioridade 1,35 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md)  | 
| **Print** | [Imagem](../assets/images/E10.jpeg) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E11

<center>
<font size="3"><b>Tabela 12: </b> E11 - Cartão do requisito funcional 11 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. |
| **Categoria** | Organizacional |
| **Elementos** | [OB12](../PerfilUsuario/Tecnicas/Observacao.md),[IS7](../PerfilUsuario/Tecnicas/Introspeccao.md) e [BT03](../PerfilUsuario/Tecnicas/Brainstorm.md) |
| **Elos Backward-from** | Agregação - [BT03](../PerfilUsuario/Tecnicas/Brainstorm.md) Originou E11 pela técnica de Observação também pela técnica de introspecção com [IS07](../PerfilUsuario/Tecnicas/Introspeccao.md)|
| **Elos Forward-from** | Satisfação - A história de usuário [BT03](../PerfilUsuario/Tecnicas/Brainstorm.md) e [IS07](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF11 ao representar a necessidade do aplicativo de notificar devidamento o usuário com base em seus gostos. <br> O requisito é tido como baixo no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $4.5 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US11 é classificado no épico 2.8 no [Backlog](../Modelagem/Agil/Backlog.md) <br> Satisfação - O requisito tem a prioridade 0,07 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md) | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E12

<center>
<font size="3"><b>Tabela 13: </b> E12 - Cartão do requisito funcional 12 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. |
| **Categoria** | Ambiental |
| **Elementos** | [IS3](../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS22](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Backward-from** | Agregação - [IS3](../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS22](../PerfilUsuario/Tecnicas/Introspeccao.md) originaram E12 pela técnica de introspecção|
| **Elos Forward-from** | Satisfação - A história de usuário [IS3](../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS22](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF12 ao representar a necessidade do aplicativo de salvar posts desejados em itens salvos. <br> O requisito é tido como Médio no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $8.5 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US12 é classificado no épico 2.9 no [Backlog](../Modelagem/Agil/Backlog.md) <br> Satisfação - O requisito tem a prioridade 0,75 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md) | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E13

<center>
<font size="3"><b>Tabela 14: </b> E13 - Cartão do requisito funcional 13 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag|
| **Categoria** | Ambiental |
| **Elementos** | [IS4](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Backward-from** | Agregação - [IS4](../PerfilUsuario/Tecnicas/Introspeccao.md) origina E13 pela técnica de introspecção|
| **Elos Forward-from** | Satisfação - A história de usuário [IS4](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF13 ao representar a necessidade do aplicativo de visualizar os posts com os itens salvos. <br> O requisito é tido como Médio no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $14 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US13 é classificado no épico 2.10 no [Backlog](../Modelagem/Agil/Backlog.md) <br>  Satisfação - O requisito tem a prioridade 0,94 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md) | 
| **Print** | Imagem |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E14

<center>
<font size="3"><b>Tabela 15: </b> E14 - Cartão do requisito funcional 14 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas.|
| **Categoria** | Ambiental |
| **Elementos** | [IS5](../PerfilUsuario/Tecnicas/Introspeccao.md) |
| **Elos Backward-from** | Agregação - [IS5](../PerfilUsuario/Tecnicas/Introspeccao.md) origina E13 pela técnica de introspecção|
| **Elos Forward-from** | Satisfação - A história de usuário [IS5](../PerfilUsuario/Tecnicas/Introspeccao.md) satisfaz o requisito RF14 ao representar a necessidade do usuário de criar ou usar feeds de terceiros. <br> O requisito é tido como Médio no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) <br> Satisfação - requisito recebeu $11 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> Agregação - O requisito US14 é classificado no épico 2.11 no [Backlog](../Modelagem/Agil/Backlog.md) <br> Satisfação - O requisito tem a prioridade 0,34 em [First thing First](../PerfilUsuario/TecnicasPrior/FirstThingsFirst.md) | 
| **Print** | [Imagem](../assets/images/elo14.jpeg) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E15

As tabelas 16, 17, 18, 19, 29, 21, 22, 23 e 24 representam os cartões de elos de requisitos funcionais feitos pelo integrante [João Ribeiro](https://github.com/Joa0V).

<center>
<font size="3"><b>Tabela 16:</b> E15 - Cartão do Requisito Funcional 15 </font>

|            Item            |                                                                                         Descrição                                                                                         |
| :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                              Os usuários devem poder interagir com postagens por meio de comentários, curtidas e respostas.                                               |
|       **Categoria**        |                                                                                      Desenvolvimento                                                                                      |
|       **Elementos**        | [RF15](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS8](../PerfilUsuario/Tecnicas/Introspeccao.md), [IS16](../PerfilUsuario/Tecnicas/Introspeccao.md), [QT2](../PerfilUsuario/Tecnicas/Questionario.md), [US15](../Modelagem/Agil/historia.md)                 |
|   **Elos Backward-from**   |                                                 **Agregação** - O requisito originou-se da Introspecção(IS8, IS16) e do Questionário(QT2)                                                 |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US15 satisfaz as necessidades estabelecidas pelo requisito RF15<br>**Alocado** - a história de usuário US15 está alocada no Épico 2.20 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                              [Print do requisito implementado](../assets/images/printRF15.jpg)                                                            |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E16

<center>
<font size="3"><b>Tabela 17:</b> E16 - Cartão do Requisito Funcional 16 </font>

|            Item            |                                                                                        Descrição                                                                                         |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                 O sistema deve permitir a aplicação de filtros avançados, como autor do post, data de publicação ou popularidade, para melhorar a experiência de busca.                  |
|       **Categoria**        |                                                                                     Desenvolvimento                                                                                      |
|       **Elementos**        |              [RF16](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS9](../PerfilUsuario/Tecnicas/Introspeccao.md), [US16](../Modelagem/Agil/historia.md)                                  |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS9)                                                              |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US16 satisfaz as necessidades estabelecidas pelo requisito RF15<br>**Alocado** - a história de usuário US16 está alocada no Épico 2.4 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                                               Requisito não implementado                                                                                 |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E17

<center>
<font size="3"><b>Tabela 18:</b> E17 - Cartão do Requisito Funcional 17 </font>

|            Item            |                                                                                        Descrição                                                                                         |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                                      O usuário deve ser capaz de fazer log-in/log-in automático em sua conta criada                                                      |
|       **Categoria**        |                                                                                     Desenvolvimento                                                                                      |
|       **Elementos**        |            [RF17](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS11](../PerfilUsuario/Tecnicas/Introspeccao.md), [US17](../Modelagem/Agil/historia.md)                                   |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS11)                                                             |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US17 satisfaz as necessidades estabelecidas pelo requisito RF17<br>**Alocado** - a história de usuário US17 está alocada no Épico 2.1 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                              [Print do requisito implementado](../assets/images/printRF17.jpg)                                                           |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E18

<center>
<font size="3"><b>Tabela 19:</b> E18 - Cartão do Requisito Funcional 18 </font>

|            Item            |                                                                                         Descrição                                                                                         |
| :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                                  O usuário deve poder fixar uma publicação em seu perfil dando-a destaque em seu perfil                                                   |
|       **Categoria**        |                                                                                      Desenvolvimento                                                                                      |
|       **Elementos**        |                       [RF18](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS13](../PerfilUsuario/Tecnicas/Introspeccao.md), [US18](../Modelagem/Agil/historia.md)                         |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS13)                                                              |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US18 satisfaz as necessidades estabelecidas pelo requisito RF18<br>**Alocado** - a história de usuário US18 está alocada no Épico 2.21 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                              [Print do requisito implementado](../assets/images/printRF18.jpg)                                                            |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E19

<center>
<font size="3"><b>Tabela 20:</b> E19 - Cartão do Requisito Funcional 19 </font>

|            Item            |                                                                                         Descrição                                                                                         |
| :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |            O usuário deve poder tornar sua conta privada, restringindo a interação de outros usuários ao permitir que apenas seguidores consigam interagir diretamente com ele            |
|       **Categoria**        |                                                                                      Desenvolvimento                                                                                      |
|       **Elementos**        |               [RF19](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS14](../PerfilUsuario/Tecnicas/Introspeccao.md), [US19](../Modelagem/Agil/historia.md)                                 |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS14)                                                              |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US19 satisfaz as necessidades estabelecidas pelo requisito RF19<br>**Alocado** - a história de usuário US19 está alocada no Épico 2.22 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                                               Requisito não implementado                                                                                  |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E20

<center>
<font size="3"><b>Tabela 21:</b> E20 - Cartão do Requisito Funcional 20 </font>

|            Item            |                                                                                        Descrição                                                                                         |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                                     Deve ser possível ao usuário fazer publicações contendo texto, imagens e vídeos                                                      |
|       **Categoria**        |                                                                                     Desenvolvimento                                                                                      |
|       **Elementos**        |                        [RF20](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS15](../PerfilUsuario/Tecnicas/Introspeccao.md), [US20](../Modelagem/Agil/historia.md)                       |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS15)                                                             |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US20 satisfaz as necessidades estabelecidas pelo requisito RF20<br>**Alocado** - a história de usuário US20 está alocada no Épico 2.2 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                              [Print do requisito implementado](../assets/images/printRF20.jpg)                                                           |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E21

<center>
<font size="3"><b>Tabela 22:</b> E21 - Cartão do Requisito Funcional 21 </font>

|            Item            |                                                                                         Descrição                                                                                         |
| :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                 Deve ser possível ao usuário visualizar dentro do aplicativo publicações de diferentes idiomas traduzidas para o idioma principal definido no aplicativo                  |
|       **Categoria**        |                                                                                      Desenvolvimento                                                                                      |
|       **Elementos**        |                          [RF21](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS18](../PerfilUsuario/Tecnicas/Introspeccao.md), [US21](../Modelagem/Agil/historia.md)                      |
|   **Elos Backward-from**   |                                                             **Recurso** - O requisito RF16 originou-se da Introspecção(IS18)                                                              |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US21 satisfaz as necessidades estabelecidas pelo requisito RF21<br>**Alocado** - a história de usuário US21 está alocada no Épico 2.23 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                                               Requisito não implementado                                                                                  |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E22

<center>
<font size="3"><b>Tabela 23:</b> E22 - Cartão do Requisito Funcional 22 </font>

|            Item            |                                                                                        Descrição                                                                                         |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                                 O usuário deve poder mandar mensagens diretas a outro usuário, caso se sigam mutualmente                                                 |
|       **Categoria**        |                                                                                     Desenvolvimento                                                                                      |
|       **Elementos**        |                               [RF22](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS19](../PerfilUsuario/Tecnicas/Introspeccao.md), [US22](../Modelagem/Agil/historia.md)                |
|   **Elos Backward-from**   |                                                            **Recurso** - O requisito RF16 originou-se da Introspecção(IS19)                                                              |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US22 satisfaz as necessidades estabelecidas pelo requisito RF22<br>**Alocado** - a história de usuário US22 está alocada no Épico 2.7 do [Backlog](../Modelagem/Agil/Backlog.md) |
|         **Print**          |                                                              [Print do requisito implementado](../assets/images/printRF22.jpg)                                                           |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E23

<center>
<font size="3"><b>Tabela 24:</b> E23 - Cartão do Requisito Funcional 23 </font>

|            Item            |                                                                                        Descrição                                                                                         |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                       O usuário deve poder mandar mensagens diretas a outro usuário, caso se sigam mutualmente                                                           |
|       **Categoria**        |                                                                             Desenvolvimento                                                                                              |
|       **Elementos**        |   [RF23](../PerfilUsuario/Tecnicas/Requisitosel.md), [IS19](../PerfilUsuario/Tecnicas/Introspeccao.md), [US23](../Modelagem/Agil/historia.md), [CEN04](../Modelagem/Cenario.md), [UC04](../Modelagem/Caso_de_uso.md)  |
|   **Elos Backward-from**   |                                                   **Recurso** - O requisito RF16 originou-se da Introspecção(IS19)                                                                       |
|   **Elos Forward-from**    | **Satisfação**  - A história de usuário US23 satisfaz as necessidades estabelecidas pelo requisito RF23<br>**Alocado** - a história de usuário US23 está alocada no Épico 2.24 do [Backlog](../Modelagem/Agil/Backlog.md)<br>**Representação** - o cenário CEN04 representa o requisito RF23<br>**Representação** - o caso de uso UC04 representa o requisito RF23 |
|         **Print**          |                                                                               Requisito não implementado                                                                                  |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>


## E31

As tabelas 32, 33, 34, 35, 36, 37 e 38 representam os cartões de requisitos funcionais feitos pela integrante [Carla Clementino](https://github.com/ccarlaa).

### **Tabela 32: E31 - Cartão do Requisito Funcional 31**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O aplicativo deve permitir linkar para outras pessoas sem o sufixo ".bsky.social"                                                                                                                                                                                                                                                                                                                                                     |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF31](../PerfilUsuario/Tecnicas/Requisitosel.md), [QT3](../PerfilUsuario/Tecnicas/Questionario.md),                                                                     , [US36](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - 
, [QT3](../PerfilUsuario/Tecnicas/Questionario.md). O requisito originou-se do Questionário. |                                                                                                                                    
| **Elos Forward-from**     | **Satisfação** - O requisito recebeu uma priorização de 0,37 na técnica [First Things First](../PerfilUsuario/TecnicasPrior/firstthing.md).<br> **Satisfação** - A história de usuário [US36](../Modelagem/Agil/historia.md) satisfaz o requisito [RF31](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve permitir linkar para outras pessoas sem o sufixo ".bsky.social"	.<br> **Satisfação** - O requisito recebeu $11 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.31 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | [Imagem](../assets/images/elo31.png)                                                                                                                                                                                                                                         
**Autor:** [Carla Clementino](https://github.com/ccarlaa)


## E32

### **Tabela 33: E32 - Cartão do Requisito Funcional 32**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O aplicativo deve permitir Trending Topics                                                                                                                                                                                                                                                                                                                                             |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF32](../PerfilUsuario/Tecnicas/Requisitosel.md), [QT5](../PerfilUsuario/Tecnicas/Questionario.md),                                                                     , [US37](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [QT5](../PerfilUsuario/Tecnicas/Questionario.md). O requisito originou-se do Questionário. |                                                                                                                                    
| **Elos Forward-from**     | **Satisfação** - O requisito recebeu uma priorização de 0,23 na técnica [First Things First](../PerfilUsuario/TecnicasPrior/firstthing.md).<br> **Satisfação** - A história de usuário [US37](../Modelagem/Agil/historia.md) satisfaz o requisito [RF32](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve permitir Trending Topics.<br> **Satisfação** - O requisito recebeu $18 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização média na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.32 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/gxIX8ULMSe6gf3Ii6dnyVu/Untitled?node-id=35-6&embed-host=share" allowfullscreen></iframe>                                                                                                                                                                                                                                         
**Autor:** [Carla Clementino](https://github.com/ccarlaa)


## E33

### **Tabela 34: E33 - Cartão do Requisito Funcional 33**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O aplicativo deve permitir o sistema de tags fora do post                                                                                                                                                                                                                                                                                                                              |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF33](../PerfilUsuario/Tecnicas/Requisitosel.md), [QT4](../PerfilUsuario/Tecnicas/Questionario.md),                                                                     , [US38](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [QT4](../PerfilUsuario/Tecnicas/Questionario.md). O requisito originou-se do Questionário. |                                                                                                                   
| **Elos Forward-from**     | **Satisfação** - O requisito recebeu uma priorização de 0,59 na técnica [First Things First](../PerfilUsuario/TecnicasPrior/firstthing.md).<br> **Satisfação** - A história de usuário [US38](../Modelagem/Agil/historia.md) satisfaz o requisito [RF33](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve permitir o sistema de tags fora do post.<br> **Satisfação** - O requisito recebeu $2 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.33 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | Imagem                                                                                                                                                                                                                                        
**Autor:** [Carla Clementino](https://github.com/ccarlaa)


## E34

### **Tabela 35: E34 - Cartão do Requisito Funcional 34**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O usuário deve poder criar comunidades ou grupos privados.                                                                                                                                                                                                                                                                                                                     |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF34](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT1](../PerfilUsuario/Tecnicas/Brainstorm.md),                                                                     , [US39](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [BT1](../PerfilUsuario/Tecnicas/Brainstorm.md). O requisito originou-se do Brainstorm. |                                                                                                                   
| **Elos Forward-from**     | **Satisfação** - A história de usuário [US39](../Modelagem/Agil/historia.md) satisfaz o requisito [RF34](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve poder criar comunidades ou grupos privados.<br> **Satisfação** - O requisito recebeu $3 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.34 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | Imagem                                                                                                                                                                                                                                        
**Autor:** [Carla Clementino](https://github.com/ccarlaa)

## E35

### **Tabela 36: E35 - Cartão do Requisito Funcional 35**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O usuário deve poder configurar a privacidade das postagens                                                                                                                                                                                                                                                                                                                              |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF35](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT2](../PerfilUsuario/Tecnicas/Brainstorm.md),                                                                     , [US40](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [BT2](../PerfilUsuario/Tecnicas/Brainstorm.md). O requisito originou-se do Brainstorm. |                                                                                                                   
| **Elos Forward-from**     | **Satisfação** - A história de usuário [US40](../Modelagem/Agil/historia.md) satisfaz o requisito [RF35](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve poder configurar a privacidade das postagens.<br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.35 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | Imagem                                                                                                                                                                                                                                        
**Autor:** [Carla Clementino](https://github.com/ccarlaa)

## E36

### **Tabela 37: E36 - Cartão do Requisito Funcional 36**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O sistema deve enviar notificações sobre eventos em tempo real.                                                                                                                                                                                                                                                                                                                              |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF36](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT4](../PerfilUsuario/Tecnicas/Brainstorm.md),                                                                     , [US41](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [BT4](../PerfilUsuario/Tecnicas/Brainstorm.md). O requisito originou-se do Brainstorm. |                                                                                                                   
| **Elos Forward-from**     | **Satisfação** - A história de usuário [US41](../Modelagem/Agil/historia.md) satisfaz o requisito [RF36](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve enviar notificações sobre eventos em tempo real.<br> **Satisfação** - O requisito recebeu $10 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.36 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | Imagem                                                                                                                                                                                                                                        
**Autor:** [Carla Clementino](https://github.com/ccarlaa)

## E37

### **Tabela 38: E37 - Cartão do Requisito Funcional 37**

| **Item**                 | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição do requisito** | O sistema deve enviar notificações sobre eventos em tempo real.                                                                                                                                                                                                                                                                                                                              |
| **Categoria**             | Ambiental                                                                                                                                                                                                                                                                                                                                                                                    |
| **Elementos**             | [RF37](../PerfilUsuario/Tecnicas/Requisitosel.md), [BT5](../PerfilUsuario/Tecnicas/Brainstorm.md),                                                                     , [US42](../Modelagem/Agil/historia.md)                                                                             |
| **Elos Backward-from**    | **Agregação** - [BT5](../PerfilUsuario/Tecnicas/Brainstorm.md). O requisito originou-se do Brainstorm. |                                                                                                                   
| **Elos Forward-from**     | **Satisfação** - A história de usuário [US42](../Modelagem/Agil/historia.md) satisfaz o requisito [RF37](../PerfilUsuario/Tecnicas/Requisitosel.md) ao especificar que o aplicativo deve enviar notificações sobre eventos em tempo real.<br> **Satisfação** - O requisito recebeu $11 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md).<br> **Satisfação** - O requisito recebeu priorização média na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md).<br> **Agregação** - O requisito é classificado no Épico 2.37 do [Backlog](../Modelagem/Agil/Backlog.md). |
| **Print**                 | Imagem                                                                                                                                                                                                                                        
**Autor:** [Carla Clementino](https://github.com/ccarlaa)




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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 2,10 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** -  A especificação suplementar [RDE01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF01](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $10 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização baixa na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md)    | 

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,25 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** -  A especificação suplementar [RD01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF02](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $15 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

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
| **Elos Forward-from** | **Satisfação** - O requisito recebeu uma priorização 0,30 na técnica [First Things First ](../PerfilUsuario/TecnicasPrior/firstthing.md) <br> **Satisfação** -  A especificação suplementar [RC01](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF04](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $20 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta na [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## E42

<center>
<font size="3"><b>Tabela 43:</b> E42 - Cartão do Requisito Não Funcional 05 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** |A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. |
| **Categoria** | Ambiental |
| **Elementos** | [RNF05](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS04](../PerfilUsuario/Tecnicas/Introspeccao.md)  |
| **Elos Backward-from** | **Agregação** -  [NIS04](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Introspecção |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RU01](../Modelagem/Especificacao.md) e [RU04](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF05](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $8.5 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização média no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E43

<center>
<font size="3"><b>Tabela 44:</b> E43 - Cartão do Requisito Não Funcional 06 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** |O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. |
| **Categoria** | Desenvolvimento |
| **Elementos** | [RNF06](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS05](../PerfilUsuario/Tecnicas/Introspeccao.md)  |
| **Elos Backward-from** | **Agregação** -  [NIS05](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Introspecção |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RC02](../Modelagem/Especificacao.md) fornece critérios e detalhes que satisfazem o requisito [RNF06](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $5 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

## E44

<center>
<font size="3"><b>Tabela 45:</b> E44 - Cartão do Requisito Não Funcional 07 </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** |O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. |
| **Categoria** | Ambiental |
| **Elementos** | [RNF07](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS06](../PerfilUsuario/Tecnicas/Introspeccao.md) e [BT09](../PerfilUsuario/Tecnicas/Brainstorm.md) |
| **Elos Backward-from** | **Agregação** -  [NIS06](../PerfilUsuario/Tecnicas/Introspeccao.md) O requisito originou-se da Técnica de Introspecção |
| **Elos Forward-from** | **Satisfação** -  A especificação suplementar [RS01](../Modelagem/Especificacao.md) fornece parte significativa de critérios e detalhes que satisfazem o requisito [RNF06](../PerfilUsuario/Tecnicas/Requisitosel.md) <br> **Satisfação** - O requisito recebeu $8 na técnica [$100](../PerfilUsuario/TecnicasPrior/100.md) <br> **Satisfação** - O requisito recebeu priorização alta no [Three Level Scale](../PerfilUsuario/TecnicasPrior/Three.md) | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

As tabelas 46 e 47 representam os cartões de requisitos não funcionais feitos pelo integrante [João Ribeiro](https://github.com/Joa0V).

## E45

<center>
<font size="3"><b>Tabela 46:</b> E45 - Cartão do Requisito Não Funcional 8 </font>

|            Item            |                                                                      Descrição                                                                      |
| :------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** | O sistema deve permitir que o usuário personalize seus feeds e notificações facilmente, com opções para ajustar preferências de conteúdo e formato. |
|       **Categoria**        |                                                                   Desenvolvimento                                                                   |
|       **Elementos**        |                       [RNF8](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS7](../PerfilUsuario/Tecnicas/Introspeccao.md)                          |
|   **Elos Backward-from**   |                                   **Recurso** - O requisito não funcional RNF8 originou-se da Introspecção(NIS7)                                    |
|   **Elos Forward-from**    |                Não foram encontrados elos Forward-from, pois o requisito não está presente em artefatos posteriores a sua elicitação                |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
</center>

## E46

<center>
<font size="3"><b>Tabela 47:</b> E46 - Cartão do Requisito Não Funcional 9 </font>

|            Item            |                                                                                           Descrição                                                                                            |
| :------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Descrição do requisito** |                                                         O aplicativo deve ter um tempo de resposta para cada ação menor que 3 segundos                                                         |
|       **Categoria**        |                                                                                        Desenvolvimento                                                                                         |
|       **Elementos**        |        [RNF9](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS9](../PerfilUsuario/Tecnicas/Introspeccao.md), [RD03](../Modelagem/Especificacao.md), [NFR05](../Modelagem/Agil/NFRs.md)         |
|   **Elos Backward-from**   |                                                         **Recurso** - O requisito não funcional RNF9 originou-se da Introspecção(NIS9)                                                         |
|   **Elos Forward-from**    | **Alocação** - o requisito não funcional RNF9 foi alocado na categoria de desempenho na Especificação Suplementar(RD03)<br>**Satisfação** - o requisito é satisfeito pelo NFR framework(NFR05) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font>
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
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>17/01/2025</td>
            <td>1.1</td>
            <td>Criação do documento; elos 8 ao 14 e 42 a 44 </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre </a></td>
            <td>18/01/2025</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>19/01/2025</td>
            <td>1.2</td>
            <td>Adição dos elos 15 ao 23 e 45 a 46 </td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>19/01/2025</td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>