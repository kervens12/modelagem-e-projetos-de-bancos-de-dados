# Modelo Conceitual – Sistema Condomínio

## Entidades e Atributos

### Condomínio
- id_condominio (Identificador)
- nome
- endereco

### Edificio
- id_edificio (Identificador)
- data_construcao
- data_ultima_vistoria
- quantidade_apartamentos

### Apartamento
- id_apartamento (Identificador)
- numero
- area_m2
- bloco

### Pessoa
- nome
- cpf (Identificador)
- data_nascimento
- sexo

---

## Relacionamentos

- Um condomínio pode possuir vários edifícios (1:N).
-Um edifício pertence a apenas um condomínio.
- Um edifício tem vários apartamentos (1:N).
-Um apartamento pertence a apenas um edifício.
- Um apartamento mora vários moradores (1:N).
-Um morador pertence a apenas um apartamento.
