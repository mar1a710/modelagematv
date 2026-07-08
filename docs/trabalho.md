# Documento Inicial do Projeto — D0  
## Documento de Visão e Documento de Requisitos

**Instituição:** Instituto Federal do Maranhão — Campus Itapecuru-Mirim  
**Disciplina:** Modelagem de Sistemas com IA Generativa  
**Professor:** Prof. Dr. Thales Levi Azevedo Valente  
**Turma:** Técnico Subsequente  
**Grupo:** Igor Cruz, Cauã Pereira, Gustavo Joaquim e Renato Augusto  
**Trilha:** Mapa Temporal Participativo de Memória Quilombola  
**Nome do projeto:** Estudos Quilombolas  
**Data:** 08/07/2026  
**Versão:** D0  

---

## Controle do Documento

| Versão | Data | Responsáveis | Descrição da alteração |
|---|---|---|---|
| D0 | 08/07/2026 | Igor Cruz, Cauã Pereira, Gustavo Joaquim e Renato Augusto | Primeira versão criada a partir das atividades das aulas 1 a 9. |

---

# Sumário

1. [Introdução](#1-introdução)  
2. [Documento de Visão](#2-documento-de-visão)  
3. [Documento de Requisitos](#3-documento-de-requisitos)  
4. [Registro de Uso da IA](#4-registro-de-uso-da-ia)  
5. [Espaço Reservado para Próximas Etapas](#5-espaço-reservado-para-próximas-etapas)  
6. [Pendências Gerais](#6-pendências-gerais)  

---

# 1. Introdução

## 1.1 Finalidade do documento

Este documento apresenta a versão inicial da visão e dos requisitos do projeto **Estudos Quilombolas**.  
Ele registra o problema real investigado, o objetivo do sistema, os stakeholders, o escopo inicial, os requisitos levantados até o momento e as pendências que ainda precisam de validação.

## 1.2 Fontes usadas para elaborar esta versão

| Fonte ou atividade | O que foi aproveitado no documento |
|---|---|
| Aula 1 — Problema real e trilha | Definição da trilha de Mapa Temporal Participativo de Memória Quilombola. |
| Aula 2 — Entrada, processamento e saída | Identificação das entradas, processamento e saídas do sistema de memórias. |
| Aula 4 — Uso de IA e log | Estruturação e boas práticas de registro da utilização da ferramenta. |
| Aula 5 — Stakeholders, objetivo, escopo e 5W1H | Levantamento dos públicos envolvidos, limites e objetivo do sistema. |
| Aula 6 — Plano de coleta e ética | Definição do cuidado ético com relatos, imagens e locais sensíveis. |
| Aula 8 — Primeira lista rastreável | Escrita dos primeiros RFs, RNFs e Regras de Negócio baseados nos achados. |
| Aula 9 — Documento de Visão e Documento de Requisitos | Organização e divisão do conteúdo em blocos complementares. |

---

# 2. Documento de Visão

## 2.1 Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Nome do projeto | Estudos Quilombolas |
| Trilha escolhida | Mapa Temporal Participativo de Memória Quilombola |
| Problema central | Dificuldade em registrar e preservar as memórias orais e os locais históricos das comunidades quilombolas de Itapecuru. |
| Público principal | Líderes comunitários, jovens quilombolas, pesquisadores e a Secretaria de Igualdade Racial. |
| Produto esperado | Plataforma participativa para mapear relatos, fotos e locais de memória com recorte temporal. |

## 2.2 Problema real

**Problema real identificado:**  
As memórias orais e os locais históricos das comunidades quilombolas de Itapecuru estão dispersos, o que dificulta o registro, a preservação e a consulta pelas novas gerações.

**Quem é afetado pelo problema:**  
Líderes comunitários, jovens quilombolas, pesquisadores e a Secretaria de Igualdade Racial.

**Por que o problema importa:**  
A dispersão dessas informações dificulta a salvaguarda e o acesso à memória histórica local, sendo necessário transformá-las em conhecimento organizado para que a comunidade possa compreender melhor o problema.

## 2.3 Justificativa

**Justificativa:**  
O projeto é importante porque transforma informações dispersas em conhecimento organizado, ajudando estudantes, professores e gestores a compreender melhor o problema e tomar decisões com mais responsabilidade.

## 2.4 Objetivo do sistema

**Objetivo geral:**  
Apoiar líderes comunitários, jovens quilombolas, pesquisadores e comunidades a registrar e consultar memórias territoriais para preservar histórias locais com fonte, autoria, mapeamento e validação.

## 2.5 Stakeholders

| Tipo | Stakeholder | Interesse ou necessidade | Relação com o sistema |
|---|---|---|---|
| Usuário direto | Estudante pesquisador / Jovem quilombola | Precisa cadastrar memórias e locais históricos | Usa o sistema para registrar os relatos e mapear os dados |
| Fornecedor de dados | Comunidade quilombola / Anciãos | Compartilhar suas memórias, fontes e relatos | Envia relatos, imagens e autorizações |
| Validador | Liderança comunitária ou responsável indicado | Confirmar informações sensíveis e gerenciar o status | Valida relatos e locais antes da publicação no mapa público |
| Gestor ou responsável | Secretaria de Igualdade Racial / Professor orientador | Acompanhar a preservação e o andamento do projeto | Consulta as memórias organizadas e gerencia as diretrizes |
| Impactado | Novas gerações e comunidade local | Ter acesso à história e registros preservados | Consome o mapa gerado e as páginas de memória |

## 2.6 Sistema como transformação

| Elemento | Descrição |
|---|---|
| Entradas | Relatos orais, locais, coordenadas, fotos, áudios e fontes. |
| Processamento | Organizar por território, associar tempo e lugar, validar informações. |
| Saídas | Mapa temporal, página de memória e relatório comunitário. |
| Usuários das saídas | Comunidade quilombola, estudantes, pesquisadores e visitantes. |

## 2.7 Escopo inicial

| ID | Dentro do escopo | Justificativa |
|---|---|---|
| E01 | Cadastrar memórias e relatos com título, descrição, local, período e fonte. | É a função central para organizar as memórias. |
| E02 | Registrar a localização e georreferenciamento no mapa. | Necessário para identificar espacialmente os pontos históricos. |
| E03 | Associar período e recorte temporal às memórias. | Permite ordenar cronologicamente os acontecimentos na linha do tempo. |
| E04 | Anexar fotos e arquivos de áudios de suporte aos relatos. | Garante o registro fiel das fontes de tradição oral. |

## 2.8 Fora do escopo

| ID | Fora do escopo | Motivo |
|---|---|---|
| FE01 | Realidade Virtual (VR) para visualização de memórias em 3D. | Complexidade fora dos limites do escopo definido para esta versão. |
| FE02 | Publicar relatos e locais reais sem autorização e validação. | Exige validação ética, proteção comunitária e conformidade com as regras. |

## 2.9 Fronteira do sistema

| Elemento externo | O que envia ao sistema | O que recebe do sistema |
|---|---|---|
| Comunidade quilombola | Envia relatos, fotos, áudios, validações e autorizações | Recebe mapa temporal, página de memória e possibilidade de revisão |

## 2.10 Limites e compromissos do projeto

| Compromisso | Como será respeitado |
|---|---|
| Respeitar autorização comunitária | Relatos, imagens e locais sensíveis só serão publicados após validação e autorização registrada. |
| Tratamento de dados sensíveis | Cuidado central na manipulação e sigilo de informações antes de estarem validadas pelas lideranças. |

---

# 3. Documento de Requisitos

## 3.1 Requisitos funcionais iniciais

| ID | Requisito funcional | Ator principal | Prioridade | Fonte ou evidência |
|---|---|---|---|---|
| RF001 | O sistema deve permitir cadastrar memória com título, descrição, local, período histórico e fonte. | Estudante pesquisador | Alta | Atividade de entrada/processamento/saída e escopo E01. |
| RF002 | O sistema deve permitir registrar a localização geográfica do relato no mapa. | Estudante pesquisador | Alta | Alinhado com o escopo de georreferenciamento E02. |
| RF003 | O sistema deve permitir associar um recorte ou período histórico a cada relato cadastrado. | Estudante pesquisador | Média | Alinhado com o escopo de associação temporal E03. |
| RF004 | O sistema deve permitir anexar arquivos de fotos ao registro da memória. | Estudante pesquisador | Média | Alinhado com o escopo de anexar mídias E04. |
| RF005 | O sistema deve permitir anexar arquivos de áudios contendo relatos orais. | Estudante pesquisador | Média | Alinhado com o escopo de anexar mídias E04. |
| RF006 | O sistema deve permitir registrar a fonte, autoria e os dados de autoria do depoimento. | Estudante pesquisador | Alta | Necessidade de controle de fontes do projeto. |
| RF007 | O sistema deve permitir alterar o status da memória para pendente, validada ou recusada. | Liderança comunitária | Alta | Fluxo operacional de validação exigido pela trilha. |
| RF008 | O sistema deve listar todas as memórias que necessitam de triagem ou moderação. | Liderança comunitária | Alta | Vinculado ao processo interno de controle de publicações. |
| RF009 | O sistema deve permitir a busca e filtragem de relatos no mapa por período temporal. | Visitante / Pesquisador | Média | Exigência funcional da visualização da linha do tempo. |
| RF010 | O sistema deve permitir o registro e vinculação da autorização formal de uso do relato. | Estudante pesquisador | Alta | Exigência do compromisso ético e autorização comunitária. |

## 3.2 Requisitos não funcionais iniciais

| ID | Categoria | Requisito não funcional | Como verificar | Prioridade |
|---|---|---|---|---|
| RNF001 | Privacidade / Ética | O sistema deve publicar relato ou imagem sensível apenas quando houver autorização registrada e status "validado". | Todo relato publicado deve obrigatoriamente apresentar o campo de autorização e status igual a validado. | Alta |
| RNF002 | Usabilidade | A interface deve permitir que um estudante cadastre uma memória em até 5 minutos após orientação inicial. | Medir o tempo gasto pelo usuário para finalizar um cadastro padrão em ambiente de testes. | Alta |
| RNF003 | Desempenho | As camadas principais do mapa devem carregar em até 5 segundos em conexões móveis de baixa velocidade (3G/4G). | Executar testes simulando banda de velocidade reduzida diretamente no navegador. | Média |
| RNF004 | Acessibilidade | As telas principais do sistema devem ser perfeitamente legíveis em aparelhos celulares. | Verificar a responsividade visual sem distorção das fontes e layouts em telas menores. | Alta |
| RNF005 | Usabilidade | As telas principais devem permitir a navegação por meio de comandos de toque na tela. | Validar a execução de toques e gestos móveis em dispositivos mobile. | Alta |
| RNF006 | Segurança | O sistema deve restringir o acesso ao painel de alteração de status exclusivamente a usuários autorizados. | Testar se usuários sem perfil validador são bloqueados ao tentar acessar as funções de triagem. | Alta |
| RNF007 | Rastreabilidade | O sistema deve manter o registro da autoria e fonte vinculados permanentemente ao relato correspondente. | Confirmar no banco de dados que nenhum relato pode ser órfão de fonte ou autor. | Média |

## 3.3 Regras de negócio iniciais

| ID | Regra de negócio | Justificativa | Fonte ou validação |
|---|---|---|---|
| RN001 | Apenas relatos validados pela liderança ou responsável indicado poderão ser publicados no mapa público. | Protege a memória coletiva e evita a exposição indevida de dados sem triagem prévia. | Regra de governança comunitária. |
| RN002 | Todo relato submetido deve conter obrigatoriamente a indicação clara da autoria ou fonte primária. | Mantém a fidelidade, a origem e a rastreabilidade da tradição oral coletada. | Requisito de fidelidade histórica. |
| RN003 | Um relato ou local sensível classificado como não autorizado deve ter sua publicação retida no sistema de modo oculto. | Cumpre o compromisso técnico e ético de não publicar dados sem autorização comunitária. | Cuidado ético do projeto. |
| RN004 | Alterações no status de uma memória ("Validada" ou "Recusada") exigem o registro do usuário validador responsável. | Permite auditar e rastrear quem foi o membro comunitário que liberou o conteúdo técnico. | Processo de triagem do sistema. |
| RN005 | Registros marcados com status "Recusada" não são apagados, permanecendo em modo rascunho interno para possíveis revisões. | Permite que o grupo ou pesquisador possa revisar correções em atividades futuras sem perder o trabalho. | Alinhamento de engenharia de requisitos. |

## 3.4 Critérios de aceitação

| Requisito relacionado | Dado que | Quando | Então |
|---|---|---|---|
| RF001 / RN001 | O estudante pesquisador está na tela de cadastro de memória; | Ele preenche o título, descrição, local, período e fonte; | O sistema deve salvar a memória com o status "pendente de validação". |
| RNF001 | O sistema possui um relato com status igual a "pendente" ou "recusado"; | Um visitante tenta acessar os dados desse relato na área pública; | O sistema impede a visualização da informação e mantém o relato oculto. |

## 3.5 Matriz de rastreabilidade inicial

| Evidência ou achado | Necessidade identificada | Requisito relacionado | Status |
|---|---|---|---|
| Achado: "há relatos que não podem ser publicados sem autorização". | Proteger memórias, imagens e locais sensíveis das comunidades. | RNF001 / RN003 | Pendente de validação com comunidade. |
| Achado: "necessidade de mapear relatos associando tempo e lugar". | Identificar os pontos e períodos históricos de forma ordenada. | RF002 / RF003 | Hipótese |

---

# 4. Registro de Uso da IA

| Data | Ferramenta | Prompt usado | O que foi aproveitado | O que foi corrigido ou descartado | Responsável pela revisão |
|---|---|---|---|---|---|
| 08/07/2026 | Gemini | "Formate o modelo de documento D0 adaptando estritamente para a trilha de Memória Quilombola, utilizando apenas dados explícitos fornecidos nos slides da Aula 9, sem inventar informações externas." | Organização visual das seções, estruturação das tabelas de requisitos funcionais e não funcionais. | Foram removidos dados fictícios de prazos e nomes de locais não citados no material de apoio. | Igor Cruz |

---

# 5. Espaço Reservado para Próximas Etapas

*As seções abaixo serão preenchidas nas próximas aulas. Por enquanto, deixem apenas os títulos.*

## 5.1 Atores do sistema
[preencher nas próximas aulas]

## 5.2 Casos de uso
[preencher nas próximas aulas]

## 5.3 Descrição detalhada dos casos de uso
[preencher nas próximas aulas]

## 5.4 Diagramas
[preencher nas próximas aulas]

| Diagrama | Status | Arquivo previsto |
|---|---|---|
| Diagrama de casos de uso | Pendente | `diagramas/casos_de_uso.puml` |
| Diagrama de atividades | Pendente | `diagramas/atividades.puml` |
| Diagrama de classes | Pendente | `diagramas/classes.puml` |
| Diagrama de sequência | Pendente | `diagramas/sequencia.puml` |

---

# 6. Pendências Gerais

| ID | Pendência ou dúvida | Quem deve validar | Prazo previsto |
|---|---|---|---|
| P001 | Definir quem pode validar relatos sensíveis — liderança comunitária/professor — próxima aula prática. | Professor / Grupo | Próxima aula prática. |

---

## Declaração do grupo

Declaramos que esta versão D0 foi elaborada com base nas atividades realizadas em sala, nas discussões do grupo e no uso responsável de IA generativa. O grupo revisou o conteúdo, corrigiu sugestões inadequadas e assume responsabilidade pelas informações registradas.

**Integrantes:**  
- Igor Cruz  
- Cauã Pereira  
- Gustavo Joaquim  
- Renato Augusto  

**Data:** 08/07/2026