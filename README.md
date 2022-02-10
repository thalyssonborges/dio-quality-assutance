## QUALITY ASSUTANCE (QA)

Teste de software é um processo que faz parte de vida do software, e tem como principal objetivo avaliar a qualidade do software e reduzir o risco de falha no software em operação;

Os bugs são inevitáveis no desenvolvimento de um produto. Por isso, existe, diversas técnicas de desenvolvimento e processos de controla de qualidade realizados durante o ciclo de desenvolvimento de software que buscam evitar que um erro afete a experiência e confiança do usuário na aplicação;

A desculpa de não se testar o software, é que teste custa caro, mas Pressman já apresentou em seu Livro de Engenharia de Software que o custo do defeito é progressivo, ou seja, encontrar o defeito na fase de engenharia de requisitos custa 1 enquanto encontrar o defeito durante a fase de produção custa 100 vezes mais, então utilizar o teste, reduz custo e não aumenta;

<img src="C:\Users\Thalysson\Pictures\custo de um bug.png" alt="custo de um bug" style="zoom: 80%;" />



#### Princípios de Testes de Software:

- O teste mostra a presença de defeitos e não a sua ausência;
- Testes exaustivos são impossíveis;
- O teste inicial economiza tempo e dinheiro;
- Cuidado com o paradoxo do pesticida (Fazer testes exaustivos a fim de confirmar que o código esta a prova de erros);
- O teste depende do contexto;
- Ausência de erros é uma ilusão.



## COMO TESTAR O SOFTWARE? 

### FUNDAMENTOS DE QUALIDADE DE SOFTWARE

#### Tipos x Técnicas x Níveis

![img](https://totvs.github.io/tir-docs/testes/images/testes-tipos1.png)



#### Processo de Teste



<img src="C:\Users\Thalysson\Pictures\processo de teste.png" alt="processo de teste" style="zoom: 67%;" />





<img src="C:\Users\Thalysson\Pictures\Ferramentas de teste.png" alt="Ferramentas de teste" style="zoom: 67%;" />





<img src="C:\Users\Thalysson\Pictures\visão geral de teste.png" alt="visão geral de teste" style="zoom: 67%;" />



## Testes Estáticos

São os testes iniciais, realizados antes de executar o sistema (APIs, outros recebíveis etc.)



## PLANEJAR

- Leitura dos requisitos : Verifica a documentação dos analistas de requisitos e realiza a leitura destes documentos.
- Levantamento de dúvidas:  Esclarecer as dúvidas.
- Ideias de teste: Propor a lista de cenários de testes de acordo com a leitura dos requisitos depois de esclarecidos.
- Estimativa: Leva em consideração diversos fatores, experiência do analista, complexidade dos requisitos etc.



## PROJETAR

- Nome/Título;
- Objetivo;
- Pré-condições;
- Passo a passo;
- Resultado esperado.



#### Técnicas utilizadas para se gerar casos de testes:

- **Participação por Equivalência (Equivalence Partition);**



- **Análise do Valor Limite (Boundary Value Analysis)**:  O "Valor Limite" (bordas extremas de uma partição) são uma área em que os testes podem gerar defeitos. Os testes podem ser desenhados para cobrir tanto os valores válidos, quanto os inválidos. Deve ser feito um caso de teste para cada valor limite;

  A técnica é executada da seguinte forma: 

  1. Identificar as partições equivalentes e os ranges de valores relacionados.
  2. Identificar os valores máximos e mínimos (resultando em partições válidas e inválidas).
  3. Desenvolver as condições de testes para cada valor limite identificado;

  

- **Tabela de Decisão (Decision Table):** Uma tabela de decição ajuda a testar regras de negócios sobre várias condições do sistema (input do usuário) e as ações correspondentes (System outputs).

  A técnica de tabela de decisão analisa essencialmente dois parâmetros: 

  1. Condições;
  2. Ações.

  

- **Testes por Transição de Estados (State Transitioning) Testing):** São utilizados no design da aplicação para representar o comportamento de um sistema em um número finito de estados. Esses diagramas são extremamente úteis em situações aonde a análise e testes de sistemas são requeridos utilizando como base o comportamento/situação anterior da aplicação com o que está ocorrendo no presente. A transição é iniciada por um evento ( entrada de um valor em um campo). O evento resulta em uma transição. A mudança de estado pode fazer com que o software execute uma ação.

  

#### Técnicas de Testes Baseadas na Experiência.

**Suposição de erro:**
Como o aplicativo funcionou no passado;
Quais tipos de erros os desenvolvedores tendem a fazer;
Falhas ocorridas em outros aplicativos. 

**Teste exploratório**
Sem um roteiro previamente definido.
São modelados, executados, registrados e avaliados dinamicamente durante a execução do teste.



## EXECUTAR

Posso testar?

- Ambiente está atualizado?
- Tenho todos os acessos necessários?
- Preciso de alguma massa de teste?



Evidências de **Erro**:

Itens que uma boa evidência deve ter:

- Print do erro;
- Descrição do passo a passo de como chegar ao problema;
- Descrição do erro mostrado na tela;
- Navegador, sistema operacional usado;
- Versão do sistema testado.



Evidências de **Sucesso**:

Itens que uma boa evidência deve ter:

- Print do resultado esperado;
- Nome ou id do caso de teste;
- Data da execução e versão do sistema realizado;
- Ciclo do teste.



#### Quando parar os testes?

A cultura de se testar o software pode ou tem algumas barreiras como:

- Tempo insulficiente;
- Orçamento curto;
- Falta de capacitação para identificar risco;
- Falta de capacitação dos desenvolvedores para executar ao menos um teste unitário;

Testaremos até atingirmos uma confiança nos requisitos, quando os critérios de encerramento forem atingidos ou quando o custo para identificação dos defeitos não compensarem mais.



## ENTREGAR

- Documentação (Casos de Teste/ Script de Teste)
- Status Report
- Evidências de Testes



<hr>

#### Fonte:

https://web.dio.me/course/introducao-qualidade-de-software/learning/d381c70c-0b96-49ee-a2a1-9a3516ae64e1?back=/track/cognizant-java-developer



<hr>

#### 🤝 Contribuindo

Este repositório foi criado para fins de estudo, então contribua com ele.<br>
Se te ajudei de alguma forma, ficarei feliz em saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.

Se possível:

⭐️  Star o projeto


------------

Disponibilizado por [thalysson-borges](https://www.linkedin.com/in/thalysson-borges/ "thalysson-borges").
