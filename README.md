# Projecto_16

No documento "https://www.mdpi.com/2306-5729/7/11/146", é descrito um conjunto de dados criado a partir de várias bases de dados desagregadas de uma instituição de ensino superior, relacionado a estudantes matriculados em diferentes cursos de graduação, como agronomia, design, educação, enfermagem, jornalismo, gestão, serviço social e tecnologias2. Este conjunto de dados inclui informações conhecidas no momento da matrícula do estudante, como dados demográficos, socioeconômicos, macroeconômicos e o desempenho acadêmico dos estudantes no final do primeiro e segundo semestres2.

O problema foi formulado como uma tarefa de classificação de três categorias: desistência, matrícula e graduação, ao final da duração normal do curso2. O conjunto de dados contém 4424 registros com 35 atributos, onde cada registro representa um estudante individual2. A análise exploratória de dados foi realizada usando a biblioteca Pandas versão 1.4.3, a biblioteca Scikit-learn versão 1.1.1 e a biblioteca Bokeh versão 2.4.3 para visualizações.

O documento também discute a importância da característica de permutação, que é uma técnica usada para medir a importância das características, observando o aumento ou diminuição do erro quando os valores de uma característica são permutados9. Além disso, o conjunto de dados é compatível com os princípios FAIR (Findability, Accessibility, Interoperability, and Reusability) para a gestão de dados científicos.

Como conclusão, o estudo concluiu que o conjunto de dados criado a partir do Instituto Politécnico de Portalegre é útil para pesquisadores que desejam conduzir estudos comparativos sobre o desempenho acadêmico dos estudantes e também para treinamento na área de aprendizado de máquina11. O conjunto de dados contém 4424 registros com 35 atributos, incluindo informações conhecidas no momento da matrícula dos estudantes, dados demográficos, socioeconômicos, macroeconômicos e o desempenho acadêmico dos estudantes no final do primeiro e segundo semestres11.

Além disso, o estudo destaca a importância de abordar o problema de classes desbalanceadas, uma vez que a classe majoritária, "Graduado", representa 50% dos registros, enquanto "Desistência" representa 32% e "Matriculado" apenas 18%6. Para lidar com esse desbalanceamento, recomenda-se o uso de técnicas de amostragem como SMOTE ou ADASYN, ou algoritmos de aprendizado de máquina que já incorporam etapas de balanceamento, como o Balanced Random Forest6.

O estudo também aplicou a técnica de Importância de Características por Permutação para identificar as características mais importantes para os modelos de aprendizado de máquina, destacando que as unidades curriculares aprovadas no segundo semestre, o curso e as taxas de matrícula em dia são características importantes em todos os algoritmos analisados.

NOSSO TRABALHO, FOI APLICAR ML PARA TESTAR AS HIPÓTESE LEVANTADAS NESTES ARTIGO SOBRE O PROBLEMA DE MULTICLASSES. Antes disso, foi feito um conjunto de analises que são demostradas no notebook.



