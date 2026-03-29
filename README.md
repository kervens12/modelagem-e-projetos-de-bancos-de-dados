# modelagem-e-projetos-de-bancos-de-dados
📚 Repositório dedicado ao estudo e prática de modelagem de dados (Conceitual e Lógico) e projetos de banco de dados.

# 🧠 O que é um banco de dados?

Segundo Korth, é uma coleção de dados inter-relacionados que representam informações sobre um domínio específico. Basicamente, é o agrupamento de informações que se relacionam e tratam de um mesmo assunto, reunindo registros utilizáveis para um mesmo fim.

# 🏗️ Quais os níveis de abstração de banco de dados?

Existem três níveis: Conceitual, Lógico e Físico.

# 📊 O que representa o D.E.R.?

O Diagrama Entidade Relacionamento (D.E.R.) faz parte do modelo criado por Peter Chen em 1976. Ele é utilizado para a representação e entendimento dos dados que compõem a essência de um problema, baseando-se no relacionamento entre conceitos da realidade estudada.

# 🔧 Quais os componentes do D.E.R.?

Os componentes fundamentais são as Entidades, os Atributos e os Relacionamentos.

# 🧩 O que é uma entidade?

É uma abstração de um objeto do mundo real ou qualquer coisa sobre a qual se deseja guardar informação. Ela representa um conjunto de objetos individuais chamados de instâncias.

# 🔄 Quais os tipos de entidade?

As entidades podem ser do tipo Forte ou Fraca.

# 💪 O que é uma entidade forte?

É aquela que existe por si só, ou seja, não depende de nenhuma outra entidade para existir no modelo.

# 🔗 O que é uma entidade fraca?

É uma entidade que depende de outra para sua existência (dependência por existência) ou para sua identificação (dependência por identificação). Ela só existe enquanto a entidade forte à qual está ligada existir.

# 🏷️ O que é um atributo?

São as características das entidades que servem para qualificá-las.

# 📌 Quais os tipos de atributos e suas características?
🔹 Simples: armazena apenas um valor.
🔹 Composto: armazena mais de um valor, que podem ser do mesmo tipo ou de tipos diferentes.
🔹 Derivado/Calculado: seu valor depende de outro atributo para existir (ex: idade calculada a partir da data de nascimento).
🔹 Multivalorado: armazena mais de um valor do mesmo tipo.
🔹 Identificador/Determinante: identifica unicamente uma ocorrência (registro) no banco de dados.

# 🔗 O que é um relacionamento?

É a ligação ou conexão entre duas ou mais entidades.

# 🔁 O que é um auto-relacionamento?

Ocorre quando uma entidade se relaciona com ela mesma ou com outra do mesmo conjunto.

# 🔢 O que é o grau do relacionamento?

É definido pelo total de entidades ligadas no mesmo relacionamento. Pode ser binário (duas entidades), ternário (três), quaternário ou n-nário.

# 📏 O que é cardinalidade do relacionamento?

É a propriedade que define exatamente com quantas instâncias de uma entidade uma outra pode se relacionar. Os tipos comuns são: um para um (1x1), um para muitos (1xN) e muitos para muitos (NxN).

# ⚖️ O que é a participação do relacionamento?

É a propriedade que define se a participação de uma entidade em um relacionamento é obrigatória (Total) ou opcional (Parcial).
