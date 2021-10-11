# Data-and-Information-Management-Project

## Grupo  
1. Rafael dos Reis de Labio - RRL3 - Líder  
2. Pedro Vítor Cunha - pvc3  
3. Kennedy Edmilson Cunha Melo - kecm  
4. Rodrigo Santos Batista - rsb6  
5. Vinícius Sales Oliveira - vso2  
6. Leonardo Gabriel Moreira de Oliveira - lgmo  

## Uma Rede de lanchonetes

- Uma empresa (código, nome) deseja manter uma rede de lanchonetes. Para isso ela permite que várias dessas lanchonetes (ID, Endereço (RUA, NUMERO) ) possam ser cadastradas. Porém apenas uma empresa pode cadastrar várias delas, de forma que cada lanchonete seja identificada por um ID.  
- Toda lanchonete ( ID, Endereço, (Rua, Numero)) emprega vários funcionários ( Cpf , Nome, Telefone)  e que são segmentados entre gerentes e atendentes.  
- Nessa empresa, um gerente pode ser supervisionado por outros gerentes (SETOR), assim como vários atendentes(Turno) podem ser supervisionados por um gerente.  
- Além disso, cada atendente(Atende) pode atender muitos clientes(Cpf, Nome), assim como um cliente pode ser atendido(Data) por muitos atendentes. Porém, em um atendimento de um atendente com um cliente, não há, necessariamente, a veda de um lanche.  
- Ademais, cada lanchonete pode ter diversos lanches (Id, Descrição, Nome_lanche), porém todo lanche precisa de uma lanchonete para ser vendido. 