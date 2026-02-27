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
- id_pessoa (Identificador)
- nome
- cpf
- data_nascimento
- sexo

---

## Relacionamentos

- Condomínio possui Edifício (1:N)
- Edifício possui Apartamento (1:N)
- Apartamento abriga Pessoa (1:N)
