# Mapa consolidado e ranking

## Painel por macroárea

Base: 100 questões de conhecimentos específicos — Petrobras/CESGRANRIO 2018 (50) e Transpetro/CESGRANRIO 2023 (50). Cada questão recebeu uma macroárea primária, sem dupla contagem.

| Ordem | Área macro | Questões | Frequência relativa | Faixa | Leitura |
|---:|---|---:|---:|---|---|
| 1 | Arquitetura de Dados | 19 | **19%** | Alta | Tema mais estável; apareceu fortemente nas duas provas |
| 2 | Engenharia de Software | 12 | **12%** | Alta | Requisitos, ciclo de vida, UML e testes são recorrentes |
| 2 | Segurança da Informação | 12 | **12%** | Alta | Bloco tradicional em 2018 e muito modernizado em 2023 |
| 4 | Gerenciamento de Projetos e Produtos | 10 | **10%** | Alta | PMBOK clássico em 2018; híbrido/ágil em 2023 |
| 5 | Lógica Matemática | 8 | **8%** | Média | Bloco regular de quatro questões em cada prova |
| 6 | Análise de Dados e Informações | 6 | **6%** | Média | BI, OLAP, Big Data, mineração e sistemas gerenciais |
| 6 | Processos, grupos de processos e áreas de conhecimento | 6 | **6%** | Média | KPIs, cadeia de valor, eficácia e grupos do PMBOK |
| 6 | Gestão e Governança de TI | 6 | **6%** | Média | Cresceu com LGPD, governança, inovação e serviços de TI |
| 9 | UX | 5 | **5%** | Média | Ausente em 2018 e bloco explícito de cinco questões em 2023 |
| — | Fora das nove macroáreas atuais | 16 | 16% | — | Leis 13.303/12.846, produção, negociação, finanças, algoritmos e redes do edital antigo |

Considerando apenas as 84 questões enquadradas nas nove macroáreas, as participações são: Arquitetura de Dados 22,6%; Engenharia de Software 14,3%; Segurança 14,3%; Projetos/Produtos 11,9%; Lógica 9,5%; e 7,1% para cada uma de Análise de Dados, Processos e Governança; UX 6,0%.

## Tabela consolidada por tópico

“% obs.” é a proporção aproximada sobre as 100 questões específicas CESGRANRIO. Tópicos próximos foram agregados para não sugerir precisão inexistente.

| Área macro                           | Tópico/conceito específico                                                           | % obs. | Frequência estimada      | Estilo de cobrança CESGRANRIO                                                              |
| ------------------------------------ | ------------------------------------------------------------------------------------ | -----: | ------------------------ | ------------------------------------------------------------------------------------------ |
| Arquitetura de Dados                 | Modelo E-R, cardinalidade, generalização/especialização e passagem conceitual→lógico |     5% | Alta                     | Cenário ou diagrama; identificar o modelo que preserva regras e cardinalidades             |
| Arquitetura de Dados                 | SQL, joins, agregação, DDL, chaves e autorrelacionamento                             |     4% | Alta                     | Trecho de esquema/consulta; escolher a instrução que produz o resultado pedido             |
| Arquitetura de Dados                 | Normalização, dependências e formas normais                                          |     2% | Alta                     | Diagnóstico de tabela e identificação da anomalia/dependência remanescente                 |
| Arquitetura de Dados                 | Modelagem dimensional, estrela, fatos e dimensões                                    |     2% | Média/Alta               | Transformação de modelo relacional em dimensional; distinção fato/dimensão                 |
| Arquitetura de Dados                 | Performance e otimizador de consultas                                                |     2% | Média/Alta               | Ação prática do DBA, índice/plano/estatísticas e função do otimizador                      |
| Arquitetura de Dados                 | Relacional × documentos × grafos; Cypher                                             |     2% | Média/Alta               | Escolha do paradigma adequado ou leitura de consulta curta em grafo                        |
| Arquitetura de Dados                 | Álgebra relacional                                                                   |     1% | Média                    | Reconhecimento de aridade/propriedade de operadores                                        |
| Arquitetura de Dados                 | Metadados                                                                            |     1% | Média                    | Finalidade do catálogo/dicionário do SGBD                                                  |
| Arquitetura de Dados                 | Data Lake e dados brutos                                                             |     1% | Média/Alta               | Conceito aplicado, schema-on-read e variedade de dados                                     |
| Arquitetura de Dados                 | Transações e ACID                                                                    |     1% | Média/Alta               | Associação correta entre letra, propriedade e efeito transacional                          |
| Gerenciamento de Projetos e Produtos | EAP/WBS                                                                              |     2% | Alta                     | Conceito PMBOK aplicado; entregáveis, decomposição e pacote de trabalho                    |
| Gerenciamento de Projetos e Produtos | Cronograma, precedência e caminho crítico                                            |     1% | Média/Alta               | Pequeno problema numérico com rede de atividades                                           |
| Gerenciamento de Projetos e Produtos | Valor agregado (VP, VA, CR, VC)                                                      |     1% | Média                    | Cálculo direto e interpretação de custo/prazo                                              |
| Gerenciamento de Projetos e Produtos | Iniciação, contexto e ciclo de vida                                                  |     2% | Média/Alta               | Situação empresarial e seleção do modelo/processo adequado                                 |
| Gerenciamento de Projetos e Produtos | Scrum × Kanban                                                                       |     1% | Alta para o edital atual | Comparação de papéis, cadência, fluxo e limites de WIP                                     |
| Gerenciamento de Projetos e Produtos | SAFe e Program Increment                                                             |     1% | Alta para o edital atual | Definição precisa de artefato/evento e propósito em escala                                 |
| Gerenciamento de Projetos e Produtos | Estrutura organizacional/matriz e autoridade do GP                                   |     1% | Média                    | Relação entre tipo de matriz e poder do gerente                                            |
| Gerenciamento de Projetos e Produtos | Monitoramento/medição do progresso                                                   |     1% | Média                    | Identificar a atividade gerencial descrita no caso                                         |
| Processos                            | KPIs: características, direcionadores e resultados                                   |     2% | Alta                     | Diferenciar indicador de causa/efeito; escolher conjunto de boas características           |
| Processos                            | Cadeia de valor de Porter                                                            |     1% | Média/Alta               | Classificar aplicações em processos primários ou de apoio                                  |
| Processos                            | Eficácia, eficiência e desempenho de processo                                        |     1% | Média                    | Caso curto, às vezes com cálculo percentual                                                |
| Processos                            | Grupos de processos e sequência                                                      |     2% | Alta para o edital atual | Ordenar iniciação→planejamento→execução→monitoramento/controle→encerramento                |
| Gestão e Governança de TI            | Arquitetura empresarial e alinhamento negócio–TI                                     |     2% | Média/Alta               | Sequência negócio→dados→aplicações→tecnologia ou definição de governança                   |
| Gestão e Governança de TI            | Gerenciamento de serviços e KPIs                                                     |     1% | Média/Alta               | Finalidade/qualidade de indicador em contexto de serviço                                   |
| Gestão e Governança de TI            | LGPD                                                                                 |     1% | Alta para o edital atual | Conceito legal aplicado a tratamento/proteção de dados; exige literalidade moderada        |
| Gestão e Governança de TI            | Economia da inovação                                                                 |     1% | Média                    | Definição econômica contextualizada em inovação                                            |
| Gestão e Governança de TI            | Conceitos e perspectivas tecnológicas/IoT                                            |     1% | Média                    | Reconhecimento conceitual por descrição de uso                                             |
| Engenharia de Software               | Requisitos: funcional/não funcional, elicitação, análise e validação                 |     5% | Alta                     | Caso realista; classificar requisito ou técnica/fase; alternativas semanticamente próximas |
| Engenharia de Software               | Ciclo de vida: cascata, V, incremental, iterativo e prototipação                     |     3% | Alta                     | Comparar modelos ou reconhecer o modelo descrito por um diálogo/cenário                    |
| Engenharia de Software               | Verificação, validação e testes estáticos/beta                                       |     2% | Alta                     | Diferenciar V&V e técnica/tipo de teste pelo objetivo                                      |
| Engenharia de Software               | UML, atividade, casos de uso e orientação a objetos                                  |     2% | Média/Alta               | Selecionar diagrama para fluxo/colaboração ou conceito de OO                               |
| UX                                   | Prototipação de alta fidelidade                                                      |     1% | Alta para o edital atual | Identificar atributos/uso correto; contrastar com paper prototype/wireframe                |
| UX                                   | Design thinking e ideação                                                            |     1% | Alta para o edital atual | Técnica adequada à geração de ideias em equipe                                             |
| UX                                   | Acessibilidade e usabilidade                                                         |     1% | Alta para o edital atual | Definições e distinções conceituais aplicadas                                              |
| UX                                   | Personas/mapa de empatia                                                             |     1% | Alta para o edital atual | Componentes do mapa: pensa/sente, vê, ouve, fala/faz etc.                                  |
| UX                                   | MVP                                                                                  |     1% | Alta para o edital atual | Versão mínima para testar hipótese e obter aprendizado/feedback                            |
| Análise de Dados                     | Big Data e os “Vs”                                                                   |     1% | Média/Alta               | Associação entre V e seu significado operacional                                           |
| Análise de Dados                     | BI, sistemas gerenciais e apoio à decisão                                            |     1% | Média                    | Classificação de sistemas e propósito gerencial                                            |
| Análise de Dados                     | OLAP e análise multidimensional                                                      |     1% | Alta para o edital atual | Conceito e operações analíticas em cenário decisório                                       |
| Análise de Dados                     | Dado→informação→conhecimento→inteligência                                            |     1% | Média                    | Ordenação/definição conceitual                                                             |
| Análise de Dados                     | Mineração: classificação e regras de associação                                      |     2% | Média                    | Escolha de algoritmo e cálculo/interpretação de suporte e confiança                        |
| Lógica Matemática                    | Equivalências, conectivos e valores-verdade                                          |     3% | Alta                     | Avaliar implicação/equivalência, frequentemente com negações                               |
| Lógica Matemática                    | Validade de argumentos e regras de inferência                                        |     3% | Alta                     | Completar conclusão ou identificar Modus Tollens/De Morgan etc.                            |
| Lógica Matemática                    | Lógica de predicados/quantificadores                                                 |     1% | Média/Alta               | Consequência lógica de frase com “todo/algum”                                              |
| Lógica Matemática                    | Problemas de ordenação e dedução                                                     |     1% | Média                    | Restrições textuais curtas para determinar posição/atributo                                |
| Segurança da Informação              | ISO 27002, controles e classificação da informação                                   |     2% | Alta                     | Objetivo/diretriz da norma em situação organizacional                                      |
| Segurança da Informação              | Criptografia, hash, assinatura/certificação e envelope digital                       |     2% | Alta                     | Função de chave/hash e sequência correta de criptografia híbrida                           |
| Segurança da Informação              | IAM: SSO, RBAC e ABAC                                                                |     2% | Alta                     | Caso de autenticação/autorização; distinguir papel de atributo/contexto                    |
| Segurança da Informação              | SDL e SAST/DAST/IAST                                                                 |     1% | Alta para o edital atual | Identificar técnica pelo acesso ao código e momento do teste                               |
| Segurança da Informação              | MITRE ATT&CK                                                                         |     1% | Alta para o edital atual | Conceito e finalidade de táticas/técnicas, sem cálculo                                     |
| Segurança da Informação              | Resposta a incidentes — NIST SP 800-61                                               |     1% | Alta para o edital atual | Fases e ciclo de melhoria pós-incidente                                                    |
| Segurança da Informação              | SIEM/operações de segurança                                                          |     1% | Alta para o edital atual | Reconhecer correlação centralizada de logs/eventos                                         |
| Segurança da Informação              | Ataques passivos e propriedades de segurança                                         |     1% | Média                    | Relacionar ameaça a confidencialidade/integridade/disponibilidade                          |
| Segurança da Informação              | Privacidade/proteção de dados                                                        |     1% | Média/Alta               | Consequência ou risco em situação cotidiana/organizacional                                 |

## Top assuntos mais quentes — ordem de estudo

### Prioridade 1 — dominar primeiro

1. **Modelagem E-R + modelo relacional + SQL + normalização.** É o núcleo mais recorrente e mais “resolvível” por treino.
2. **Engenharia de requisitos.** Tipos, elicitação, análise, especificação, validação, casos de uso e critérios de aceitação.
3. **Segurança moderna e clássica.** ISO 27002, IAM/SSO/RBAC/ABAC, criptografia/assinatura, SIEM, NIST 800-61, MITRE ATT&CK e SAST/DAST/IAST.
4. **PMBOK e gerenciamento híbrido.** EAP, grupos de processos, ciclo de vida, matriz organizacional, caminho crítico e valor agregado.
5. **Ciclo de vida, V&V e testes.** Cascata/V/incremental/iterativo, testes estáticos, beta e distinção verificação×validação.

### Prioridade 2 — forte potencial na próxima CESGRANRIO

6. **Scrum, Kanban e SAFe**, especialmente diferenças operacionais e Program Increment.
7. **Modelagem dimensional, OLAP, Data Lake e Big Data.** Estudar junto para capturar questões que transitam entre arquitetura e BI.
8. **UX:** protótipos, MVP, acessibilidade/usabilidade, design thinking, personas e mapa de empatia.
9. **Lógica sentencial e argumentos:** equivalências, implicação, negação, quantificadores, Modus Ponens/Tollens e De Morgan.
10. **LGPD e governança/alinhamento negócio–TI.** O edital atual transforma itens que eram periféricos em alvos diretos.

### Prioridade 3 — cobertura e desempate

11. Metadados, ACID, otimizador, índices, NoSQL documentos/grafos e Cypher.
12. KPIs, cadeia de valor, eficácia/eficiência e processos organizacionais.
13. Dado–informação–conhecimento–inteligência, BI, dashboards e storytelling com dados.
14. Economia da inovação, perspectivas tecnológicas e IoT.
15. Tópicos de segurança ainda não observados no corpus recente: nuvem, IoT, DLP/CASB/EDR/WAF, threat hunting, STRIDE e continuidade.

## Padrão de cobrança da CESGRANRIO

- Predomina a **múltipla escolha contextualizada**: um parágrafo de negócio/TI seguido de uma distinção conceitual precisa.
- Banco de dados e lógica trazem execução: consulta, cardinalidade, cálculo ou dedução; não basta memorizar definições.
- A banca gosta de pares confundíveis: verificação×validação, eficácia×eficiência, RBAC×ABAC, Scrum×Kanban, fato×dimensão.
- Normas e frameworks aparecem pela **finalidade prática** de controles/fases/artefatos, com literalidade suficiente para punir nomenclatura imprecisa.
- Em tecnologia recente, a profundidade tende a ser introdutória, mas a alternativa correta exige conhecer o vocabulário oficial.

## Contraste com a CEBRASPE 2022

A prova CEBRASPE tem 120 itens de certo/errado e tende a decompor uma mesma tecnologia em várias afirmações, cobrando exceções e precisão terminológica. Ela reforça a relevância de processos de negócio, bancos/BI, engenharia de software e governança, mas seu peso não foi misturado aos percentuais acima, pois formato e número de itens produziriam viés contra o foco CESGRANRIO.

