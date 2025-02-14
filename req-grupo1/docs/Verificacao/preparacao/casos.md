## Introdução
A verificação de artefatos tem como finalidade garantir a conformidade, a qualidade e a eficiência de processos e atividades em diferentes áreas. Tais ferramentas são essenciais para organizar as etapas de execução e assegurar que todas as ações necessárias sejam realizadas de maneira adequada. 

## Objetivo
Este artefato tem como objetivo documentar a lista de verificação do artefato de [casos de uso](../../Modelagem/Caso_de_uso.md) com o intuito de facilitar a gestão.

## Metodologia
Como metodologia teremos uma tabela modelo para realização da inspeção do artefato, como mostra a tabela 1. 

<center>
<font size="3"><b>Tabela 1:</b> Tabela modelo </font>

| Descrição | Referência | Autor(a) |
|:---------:|:---------:|:-----------:|
| Pergunta para verificação | Referência | Integrante do grupo responsável pela pergunta |

<p align="center"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></p> 
</center>

## Checklist da Verificação
A tabela 2 mostra a lista de verificação dos casos de uso

<center>
<font size="3"><b>Tabela 2:</b> Verificação - Casos de uso </font>

|                                                                         Descrição                                                                                    | Referência                                                           | Autor(a)                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------: | :--------------------------------------------: |
|                                    O diagrama de caso de uso possuí o sistema, atores, casos de uso e relacionamentos?                                               | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 1:35   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                        O sistema é representado por um retangulo?                                                                    | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 1:47   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                          O nome do sistema é inserido no topo?                                                                       | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 1:50   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                  Tudo que acontece no sistema está dentro do retangulo?                                                              | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 2:00   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                        O ator é representado por um boneco palito?                                                                   | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 2:12   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                     O(s) ator(es) é representado fora do retangulo ?                                                                 | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 2:48   | [João Ribeiro](https://github.com/Joa0V)           |
|                                          O ator primário está do lado esquero e o secundário do lado direito ?                                                       | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 2:52   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                          Os casos de uso são representados por elipses? Eles representam ações?                                                      | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 4:10   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                                     Cada ator interage com ao menos um caso de uso?                                                                  | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 5:20   | [Eduarda](https://github.com/erteduarda)           |
|                                       As associações são representadas por uma linha que liga o ator ao caso de uso?                                                 | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 5:35   | [Renata Quadros](https://github.com/Renatinha28)   |
|                                Os relacionamentos de inclusão mostram dependencias entre o caso de uso base e o incluído?                                            | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 7:50   | [Renata Quadros](https://github.com/Renatinha28)   |
|                          Os relacionamentos de extensão são casos de uso estendidos que as vezes podem acontecer e as vezes não?                                     | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 8:43   | [Carla](https://github.com/ccarlaa)                |
|                          Nas generalizações os casos de uso secundários compartilham as características do caso de uso primário?                                     | Lucid Software Português (2019)<sup>[1](#ref1)</sup>, Minuto: 10:47  | [Davi Nobre](https://github.com/Jagaima)           |
|                          Nas especificações de caso de uso são indicados os atores que interagem com o caso de uso? Ex.: analista, secretário, etc.                  | [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao2.PNG) [²](#ref2)  | [João Ribeiro](https://github.com/Joa0V) |
|                                  Nas especificações de caso de uso existem as condições prévias necessárias para um caso de uso ser realizado?                       | [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao3.PNG) [²](#ref2)  | [João Ribeiro](https://github.com/Joa0V)           |
|           Nas especificações de caso de uso existem condições posteriores em que o sistema se encontra logo após o a conclusão do caso de uso?                       | [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao4.PNG) [²](#ref2)  | [João Ribeiro](https://github.com/Joa0V)           |
|  Nas especificações de caso de uso estão presentes os fluxos de eventos representando toda interação do ator com o caso de uso, incluindo os dados de entrada e saída? | [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao8.PNG) [²](#ref2)  | [João Ribeiro](https://github.com/Joa0V)           |
|                                Nas especificações de caso de uso existem um de cada tipo de fluxo de evento (básico, alternativo e de exceção)?                                 |  [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao8.PNG) [²](#ref2) | [João Ribeiro](https://github.com/Joa0V)           |
|                                       Os fluxos básicos representam o caminho comum (caminho feliz) percorrido pelo ator no caso de uso?                                        |  [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao5.PNG) [²](#ref2) | [João Ribeiro](https://github.com/Joa0V)           |
|          Os fluxos alternativos representam um comportamento alternativo devido a variações no fluxo básico causadas pelas escolhas do usuário?                      |  [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao6.PNG) [²](#ref2)  | [João Ribeiro](https://github.com/Joa0V) |
| Os fluxos de exceção representam um comportamento de exceção que aconteceu durante os fluxos básicos/alternativos? (Ex.: fluxo causado por input inválido em campo de cadastro) | [Exemplo de especificação de caso de uso MCTIC](../../assets/images/verificacao/especificacao7.PNG) [²](#ref2)   | [João Ribeiro](https://github.com/Joa0V) |




<p align="center"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></p> 
</center>

## Referências Bibliográficas
> 1. <a id="ref1"></a> Lucid Software Português. Tutorial de Caso de Uso UML, 25 de abril 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 08 dez. 2024.

> 2. <a id="ref2"></a> Brasil. Ministério da Ciência, Tecnologia e Inovação. Exemplo de especificação de caso de uso. Brasília, DF. Disponível em: https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Caso%20Uso_81686821.html?nodeId=afc37190. Acesso em: 01 fev. 2025.

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
            <td>01/01/2025</td>
            <td>1.0</td>
            <td>Criação do documento</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>01/01/2025</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
    </table>
</div>
