
## Introdução

A rastreabilidade de requisitos é a habilidade de rastrear requisitos ao longo de todo o ciclo de desenvolvimento, associando-os aos seus artefatos de origem (pré-rastreabilidade) e aos artefatos de atividades posteriores (pós-rastreabilidade). Segundo Wiegers e Beatty(2013)¹, é fundamental na gerência de requisitos dando suporte necessário ao desenvolvimento de software e é muitas vezes necessário para utilizar de certas técnicas durante o processo de desenvolvimento como a análise de impactos e manutenção. Neste artefato se encontra uma matriz de rastreabilidade que apresenta as informações para rastrear os requisitos presentes neste projeto. 
## Objetivos

Com a matriz de rastreabilidade buscamos representar as informações de ligação entre requisitos, suas fontes e seus artefatos derivados de maneira clara e objetiva. Assim, podemos alcançar alguns os benefícios da rastreabilidade citados por Sayao e Leite(2005)² e Wiegers e Beatty(2013)¹, como verificação, correção de defeitos, validação, gerenciamento de riscos e previsão de prazos.

## Metodologia

A metodologia adotada será baseada no modelo de matriz de rastreabilidade apresentado por Sayao e Leite(2005)². De acordo com Wiegers e Beatty(2013)¹, as informações escolhidas para rastreabilidade devem ser aquelas que de fato irão servir aos objetivos pertinentes a rastreabilidade no projeto, portanto, a matriz de rastreabilidade sofrerá adaptações para melhor atender as necessidades deste projeto, na tabela 1 a seguir está o formato adotado:


<center>

**Tabela 1:** modelo da matriz de rastreabilidade

| Requisito  | Descrição | Implementado | Versão |     Elicitação      |       Modelagem        | Elos | Autor |
| :--------: | :-------: | :----------: | :----: | :-----: |:-----------------: | :--------------------: | :--: |
| RFxx/RNFxx |    --     |   SIM/NÃO    |  x.x   | OBxx/ISxx/QTxx/BTxx | CENxx/UCxx/SE/USxx/NFR | Cxx  | Integrante responsável |

<p align="center"><b>Autor: </b><a href="https://github.com/Joa0V">João Ribeiro</a></p>
</center>

### Legenda

- **Requisito:** código identificador do requisito. Requisitos funcionais tem o código no formato RFxx, já requisitos não funcionais apresentam código no formato RNFxx;
- **Descrição:** descrição do requisito elicitado;
- **Implementado:** indica o status de implementação do requisito. Requisitos implementados são preenchidos com 'SIM' e não implementados são preenchidos com 'NÃO';
- **Versão:** indica a versão do requisito;
- **Elicitação:** indica os artefatos nos quais o requisito foi elicitado.
	1. OBxx - Requisito elicitado pela observação.
	2. ISxx - Requisito elicitado pela introspecção.
	3.  QTxx - Requisito elicitado pelo questionário.
	4. BTxx - Requisito elicitado pelo Brainstorming.
- **Modelagem:** indica os artefatos de modelagem do requisito.
	1. CENxx - cenários
	2. UCxx - casos de uso
	3. SE - especificação suplementar
	4. USxx - histórias de usuário
	5. NFR - NFR framework
- **Elos:** indica cartão de elos referente ao requisito. 

## Matriz de rastreabilidade

A tabela 2 apresenta a matriz de rastreabilidade:

<center>

**Tabela 2:** matriz de rastreabilidade

| Requisito  | Descrição | Implementado | Versão |     Elicitação      |       Modelagem        | Elos | Autor |
| :--------: | :-------: | :----------: | :----: | :-----------------: | :--------------------: | :-------------: | :----: | 
| RF01 | Deve ser possível realizar o login no Bluesky | SIM | 1.0 | [OB01](../PerfilUsuario/Tecnicas/Observacao.md), [IS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [IS010](../PerfilUsuario/Tecnicas/Introspeccao.md) | [US01](../Modelagem/Agil/historia.md) | [E01](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF02 | Deve ser possível recuperar a senha | SIM | 1.0 | [OB02](../PerfilUsuario/Tecnicas/Observacao.md) | [US02](../Modelagem/Agil/historia.md) | [E02](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF03 | O sistema deve permitir que o usuário acesse novos conteúdos na plataforma em até 3 segundos após realizar uma ação de navegação | SIM | 1.0 | [OB03](../PerfilUsuario/Tecnicas/Observacao.md) | [US03](../Modelagem/Agil/historia.md) | [E03](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF04 | Deve ser possível realizar postagens na plataforma | SIM |1.0 | [OB04](../PerfilUsuario/Tecnicas/Observacao.md) | [US04](../Modelagem/Agil/historia.md) | [E04](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF05 | Deve ser possível editar uma postagem na plataforma | NÃO |1.0 | [OB05](../PerfilUsuario/Tecnicas/Observacao.md), [IS17](../PerfilUsuario/Tecnicas/Introspeccao.md) | [US05](../Modelagem/Agil/historia.md), [UC05](../Modelagem/Caso_de_uso.md), [CEN05](../Modelagem/Cenario.md) | [E05](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF06 | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. | SIM |1.0 | [OB06](../PerfilUsuario/Tecnicas/Observacao.md), [IS02](../PerfilUsuario/Tecnicas/Introspeccao.md) | [US06](../Modelagem/Agil/historia.md) | [E06](../Rastreabilidade/Elos.md) |[Renata Quadros](https://github.com/Renatinha28) |
| RF07 | Deve ser possível favoritar uma comunidade | NÃO |1.0 | [OB07](../PerfilUsuario/Tecnicas/Observacao.md)| [US07](../Modelagem/Agil/historia.md) | [E07](../Rastreabilidade/Elos.md) | [Renata Quadros](https://github.com/Renatinha28) |
| RF08 | O usuário deve poder criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral. | SIM |1.0 | [OB8](../PerfilUsuario/Tecnicas/Observacao.md) e [IS6](../PerfilUsuario/Tecnicas/Introspeccao.md)| [US08](../Modelagem/Agil/historia.md) | [E08](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF09 | Deve ser possível ver as mensagens com outros usuários. | SIM |1.0 | [OB9](../PerfilUsuario/Tecnicas/Observacao.md)| [US09](../Modelagem/Agil/historia.md) | [E09](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF10 | Deve ser possível editar o conteúdo do perfil | SIM |1.0 | [OB10](../PerfilUsuario/Tecnicas/Observacao.md) e [IS12](../PerfilUsuario/Tecnicas/Introspeccao.md)| [US10](../Modelagem/Agil/historia.md) | [E10](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF11 | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. | NÃO |1.0 | [OB12](../PerfilUsuario/Tecnicas/Observacao.md),[IS7](../PerfilUsuario/Tecnicas/Introspeccao.md) e [BT03](../PerfilUsuario/Tecnicas/Brainstorm.md)| [US11](../Modelagem/Agil/historia.md) | [E11](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF12 | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. | NÃO |1.0 | [IS3](../PerfilUsuario/Tecnicas/Introspeccao.md) e [IS22](../PerfilUsuario/Tecnicas/Introspeccao.md)| [US12](../Modelagem/Agil/historia.md), [CEN03](../Modelagem/Cenario.md), [UC03](../Modelagem/Caso_de_uso.md) | [E12](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF13 | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag | NÃO |1.0 | [IS4](../PerfilUsuario/Tecnicas/Introspeccao.md)| [US13](../Modelagem/Agil/historia.md), [CEN03](../Modelagem/Cenario.md)| [E13](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| RF14 | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. | SIM |1.0 | [IS5](../PerfilUsuario/Tecnicas/Introspeccao.md)| [US14](../Modelagem/Agil/historia.md)| [E14](../Rastreabilidade/Elos.md) | [Davi Nobre](https://github.com/Jagaima) |
| - |
| COLOQUEM EM ORDEM | 
| - | 
| - |
| RNF01 | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) | SIM | 1.0 | [OB11](../PerfilUsuario/Tecnicas/Observacao.md) | [SE - RDE01](../Modelagem/Especificacao.md) | [E38](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF02 | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantin do uma experiência fluida para o usuário. | SIM | 1.0 | [BT07](../PerfilUsuario/Tecnicas/Brainstorm.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md) | [SE - RD01](../Modelagem/Especificacao.md) | [E39](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF03 | O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. | SIM | 1.0 | [BT07](../PerfilUsuario/Tecnicas/Brainstorm.md), [NIS01](../PerfilUsuario/Tecnicas/Introspeccao.md), [NIS13](../PerfilUsuario/Tecnicas/Introspeccao.md) | [SE - RD02](../Modelagem/Especificacao.md) | [E40](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF04 | Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. | SIM | 1.0 | [NIS03](../PerfilUsuario/Tecnicas/Introspeccao.md) | [SE - RC01](../Modelagem/Especificacao.md) | [E41](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF05 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | SIM | 1.0 | [RNF05](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS04](../PerfilUsuario/Tecnicas/Introspeccao.md) | [SE - RU01](../Modelagem/Especificacao.md) e [SE - RU04](../Modelagem/Especificacao.md) | [E42](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF06 | O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. | Parcialmente | 1.0 | [RNF06](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS05](../PerfilUsuario/Tecnicas/Introspeccao.md)  | [SE - RC02](../Modelagem/Especificacao.md)| [E43](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |
| RNF07 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | SIM | 1.0 |[RNF07](../PerfilUsuario/Tecnicas/Requisitosel.md), [NIS06](../PerfilUsuario/Tecnicas/Introspeccao.md) e [BT09](../PerfilUsuario/Tecnicas/Brainstorm.md)  | [SE - RS01](../Modelagem/Especificacao.md)| [E44](../Rastreabilidade/Elos.md) |  [Renata Quadros](https://github.com/Renatinha28) |

<font size="3"><b>Autores: </b><a href="https://github.com/Joa0V">João Ribeiro</a>; <a href="https://github.com/Renatinha28">Renata Quadros</a>; <a href="https://github.com/Jagaima">Davi Nobre</a>; <a href="https://github.com/ccarlaa">Carla Clementino</a>; <a href="https://github.com/erteduarda">Eduarda Tavares</a></font> 
</center>

## Referências Bibliográficas

> 1. WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.
> 2. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 18 jan. 2025.

## Bibliografia

> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 18 jan. 2025.

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf. Acesso em: 18 jan. 2025

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
            <td>18/01/2025</td>
            <td>1.0</td>
            <td>Criação do documento</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>18/01/2025</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>18/01/2025</td>
            <td>1.1</td>
            <td>Add elos 1 ao 7 e 38 ao 41</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td></td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>17/01/2025</td>
            <td>1.0</td>
            <td>Adição dos elos 8 ao 14 e 42 a 44 na matriz</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre </a></td>
            <td>18/01/2025</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
    </table>
</div>