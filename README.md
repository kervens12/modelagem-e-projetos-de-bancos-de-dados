# modelagem-e-projetos-de-bancos-de-dados
📚 Repositório dedicado ao estudo e prática de modelagem de dados (Conceitual e Lógico) e projetos de banco de dados.

🗄️
# Fundamentos de Modelagem de Bancos de Dados
Para o desenvolvimento de sistemas robustos, é essencial compreender que um Banco de Dados não é apenas um depósito de arquivos, mas, conforme definido por Korth, uma coleção de dados inter-relacionados que representam informações sobre um domínio específico. Em suma, trata-se de um agrupamento de registros utilizáveis que se conectam para atender a uma finalidade comum.

🏗️ Níveis de Abstração
A modelagem de um banco de dados não ocorre de forma direta; ela atravessa três níveis de abstração que garantem a integridade do projeto:

Conceitual: Onde se define "o quê" o banco conterá, focando na visão do usuário e do negócio.

Lógico: Onde se define "como" os dados serão estruturados (tabelas, colunas, chaves).

Físico: A implementação real nos arquivos de armazenamento do SGBD.

📊 O Diagrama Entidade-Relacionamento (DER)
A peça central da modelagem conceitual é o DER, modelo introduzido por Peter Chen em 1976. Ele permite a representação visual da essência de um problema, mapeando como conceitos da realidade se conectam.

🧩 Entidades e Atributos
As Entidades são as abstrações de objetos do mundo real (pessoas, produtos, eventos) sobre os quais desejamos salvar informações. Elas podem ser classificadas como:

Fortes: Existem por si só, sem dependências.

Fracas (ou Quebradas): Dependem de outra entidade para existir ou para serem identificadas.

Para qualificar essas entidades, utilizamos os Atributos, que podem variar em natureza:

Simples: Armazenam um valor único.

Compostos: Formados por subpartes (ex: Endereço composto por rua e número).

Multivalorados: Podem conter múltiplos valores do mesmo tipo (ex: vários números de telefone).

Derivados: Valores calculados a partir de outros (ex: Idade baseada na Data de Nascimento).

Identificadores: Essenciais para garantir que cada registro seja único no sistema.

🔗 Relacionamentos e Cardinalidade
O Relacionamento é a conexão lógica entre entidades. Quando uma entidade se conecta a si mesma, chamamos de Auto-relacionamento. A complexidade dessa conexão é medida pelo seu Grau (binário, ternário ou n-nário, dependendo do número de entidades envolvidas).

Para definir as regras de negócio com precisão, utilizamos dois conceitos fundamentais:

Cardinalidade: Define o volume da conexão, sendo os tipos mais comuns o 1:1 (um para um), 1:N (um para muitos) e N:N (muitos para muitos).

Participação: Indica se a presença de uma entidade no relacionamento é Total (obrigatória) ou Parcial (opcional).pação de uma entidade em um relacionamento é obrigatória (Total) ou opcional (Parcial).
