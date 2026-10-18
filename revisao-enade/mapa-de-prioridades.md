# Mapa de prioridades — Enade 2026, Ciência da Computação

Montado em 18/10/2026 a partir da Portaria Inep nº 157/2026 e das provas de CC de 2011, 2014, 2017 e 2021 (componente específico: 30 questões por prova, 120 no total, objetivas e discursivas). As provas de 2005 e 2008 ficaram fora da contagem por serem mais antigas e de outro currículo de referência; continuam boas para treino.

A classificação de cada questão em um único assunto é minha; algumas questões tocam dois temas (ex.: um problema NP sobre grafos), então trate os números como ordem de grandeza.

## Mudança importante no formato de 2026

| | Até 2021 | Enade 2026 |
|---|---|---|
| Formação Geral | 8 objetivas + 2 discursivas | **15 objetivas, nenhuma discursiva** |
| Componente específico | 27 objetivas + 3 discursivas | **30 objetivas + 1 discursiva** |
| Tempo | 4 h | 4 h |

Consequência: o peso das objetivas aumentou. Treinar o formato de múltipla escolha do Enade (asserção-razão, "é correto apenas o que se afirma em") vale mais do que antes. A única discursiva específica, historicamente, costuma cair em algoritmos e estruturas de dados (heap, lista/pilha, backtracking, divisão e conquista, Fibonacci, árvore de busca), mas já houve lógica, circuito somador, UML, DFS em grafo, modelo ER e cache.

## Quantas questões cada assunto teve (2011–2021)

| Assunto (portaria) | 2011 | 2014 | 2017 | 2021 | Total | Média/prova |
|---|---|---|---|---|---|---|
| Algoritmos e estruturas de dados (inclui complexidade e programação) | 7 | 6 | 6 | 5 | 24 | 6 |
| Sistemas operacionais | 1 | 4 | 3 | 2 | 10 | 2,5 |
| Lógica e matemática discreta | 3 | 4 | 2 | 1 | 10 | 2,5 |
| Engenharia de software | 2 | 2 | 3 | 2 | 9 | 2,25 |
| Teoria da computação (autômatos, linguagens, computabilidade, P vs NP) | 4 | 3 | 1 | 1 | 9 | 2,25 |
| Sistemas digitais | 2 | 1 | 1 | 2 | 6 | 1,5 |
| Organização e arquitetura de computadores | 2 | 1 | 1 | 2 | 6 | 1,5 |
| Inteligência artificial | 1 | 1 | 2 | 2 | 6 | 1,5 |
| Bancos de dados | 0 | 2 | 2 | 1 | 5 | 1,25 |
| Teoria dos grafos | 1 | 1 | 2 | 1 | 5 | 1,25 |
| Paradigmas de linguagens | 2 | 1 | 1 | 1 | 5 | 1,25 |
| Redes de computadores | 2 | 0 | 1 | 1 | 4 | 1 |
| Computação gráfica e processamento de imagem | 0 | 1 | 2 | 1 | 4 | 1 |
| Compiladores | 1 | 1 | 1 | 1 | 4 | 1 |
| Probabilidade e estatística | 1 | 1 | 0 | 1 | 3 | 0,75 |
| Sistemas distribuídos | 1 | 0 | 0 | 2 | 3 | 0,75 |
| Interação humano-computador | 0 | 1 | 0 | 2 | 3 | 0,75 |
| Segurança da informação | 0 | 0 | 2 | 1 | 3 | 0,75 |
| Ética, computação e sociedade | 0 | 0 | 0 | 1 | 1 | 0,25 |

Tendência recente (2017–2021): mais IA, IHC, nuvem/sistemas distribuídos, segurança e LGPD; menos teoria da computação pura. Ética aparece explicitamente na lista da portaria de 2026 e nas competências ("avaliar o impacto da computação na sociedade e no ambiente"), então vale uma revisão curta mesmo com pouca incidência histórica.

## Faixas de prioridade

**Faixa 1 — cai sempre e em quantidade (≈ metade da prova)**
1. Algoritmos e estruturas de dados: listas, pilhas, filas, árvores de busca e AVL, heaps, ordenação (insertion, quick, merge), busca binária, recursão, complexidade (notação O, recorrências), técnicas de projeto (guloso, divisão e conquista, programação dinâmica, backtracking).
2. Sistemas operacionais: escalonamento, threads, exclusão mútua e sincronização (produtor-consumidor, locks, semáforos), deadlock, paginação e substituição de páginas.
3. Lógica e matemática discreta: lógica proposicional e de predicados, regras de inferência, relações de equivalência, combinatória.
4. Engenharia de software: Scrum e métodos ágeis, processos iterativos, testes (níveis), padrões de projeto (Observer, Singleton etc.), UML, qualidade.
5. Teoria da computação: autômatos e expressões regulares, gramáticas, máquina de Turing, problema da parada, P, NP e NP-completo.

**Faixa 2 — uma a duas questões por prova**
Sistemas digitais (circuitos, álgebra booleana, mux, somador), arquitetura (pipeline e conflitos, memória, cache, Von Neumann), IA (aprendizado supervisionado e não supervisionado, redes neurais, agentes, busca A*), bancos de dados (SQL com joins e subconsultas, ER para relacional, normalização), grafos (Dijkstra, Kruskal, DFS/BFS), paradigmas (Prolog, OO: encapsulamento, herança, TDA).

**Faixa 3 — cerca de uma questão ou menos**
Redes (camadas, TCP/UDP, dispositivos, protocolos), computação gráfica e imagem (filtros, morfologia, iluminação, ray tracing), compiladores (fases, gramáticas LL/LR), probabilidade (condicional, distribuição normal), sistemas distribuídos e nuvem, IHC (usabilidade, personas), segurança (criptografia simétrica e assimétrica, hash, ataques), ética e LGPD.

## Onde cada assunto está na grade da Unisinos

| Assunto | Disciplinas |
|---|---|
| Algoritmos e estruturas de dados | Algoritmos e Programação (Fundamentos; Estruturas Lineares; Árvores e Ordenação; Grafos, Hashing e Heaps); Análise e Projeto de Algoritmos |
| Sistemas operacionais | Fundamentos de SO; Análise e Aplicação de SO |
| Lógica e matemática discreta | Raciocínio Lógico; Matemática para Computação |
| Engenharia de software | ES: Requisitos, Análise, Projeto, Implementação e Teste |
| Teoria da computação | Linguagens Formais e Autômatos; Teoria da Computação |
| Sistemas digitais e arquitetura | Projeto de Sistemas Digitais; Arquitetura de Sistemas Digitais |
| IA | Inteligência Artificial e Aprendizado de Máquina |
| Bancos de dados | Fundamentos de Banco de Dados; Sistemas de Gerência de BD |
| Grafos | Algoritmos e Programação: Grafos, Hashing e Heaps |
| Paradigmas | Paradigmas de Programação |
| Redes | Redes: Aplicação e Transporte; Redes: Internetworking, Roteamento e Transmissão |
| Compiladores | Tradutores |
| Computação gráfica e imagem | Processamento Gráfico; Computação Gráfica |
| Probabilidade e estatística | Probabilidade e Inferência Estatística; Análise de Dados para Tomada de Decisão |
| Sistemas distribuídos | Sistemas Distribuídos; Computação de Alto Desempenho |
| IHC | Design de Interação Humano-Computador |
| Segurança | Teoria da Informação: Compressão e Criptografia |
| Ética | Ética e Tecnocultura (optativa); Computação: Conceitos e Tendências da Profissão |

## Plano sugerido até a prova (29/11/2026)

| Semana | Foco |
|---|---|
| 1 (19–25/10) | Algoritmos e estruturas de dados, complexidade |
| 2 (26/10–01/11) | Grafos + teoria da computação |
| 3 (02–08/11) | Sistemas operacionais + arquitetura + sistemas digitais |
| 4 (09–15/11) | Lógica e matemática discreta + probabilidade + bancos de dados |
| 5 (16–22/11) | Engenharia de software + IHC + segurança + ética/LGPD |
| 6 (23–28/11) | IA, redes, sistemas distribuídos, paradigmas, compiladores, computação gráfica; simulado com a prova de 2021 |

Em cada semana: revisar o conteúdo, resolver as questões das provas antigas sobre o tema e anotar os erros. Depois do Enade, seguir a grade completa para fechar a base de conhecimento do curso.
