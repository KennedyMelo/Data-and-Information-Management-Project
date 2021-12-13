# Data-and-Information-Management-Project

## Grupo  
1. Rafael dos Reis de Labio - RRL3 - Líder  
2. Pedro Vítor Cunha - pvc3  
3. Kennedy Edmilson Cunha Melo - kecm  
4. Rodrigo Santos Batista - rsb6  
5. Vinícius Sales Oliveira - vso2  
6. Leonardo Gabriel Moreira de Oliveira - lgmo  

## Uma Rede de lanchonetes

- Uma franquia (cod_franquia, nome_franquia) deseja manter uma rede de lanchonetes. Para isso ela permite que várias dessas lanchonetes (cod_lanchonete, Endereço (RUA, NUMERO) ) possam ser cadastradas por uma empresa. Porém uma lanchonete apenas  pode ser cadastrada a uma empresa. Uma lanchonete não pode ser cadastrada sem franquia.
- Uma franquia possui vários lanches e um lanche é apenas de uma franquia, não podendo haver lanche não cadastrado a uma franquia.    
- Toda lanchonete emprega vários funcionários ( Cpf_func , Nome, Telefone(possui 2, o 1° é obrigatório)), os quais não podem ser empregados sem a lanchonete, e que TODOS são segmentados entre ou gerente(SETOR) ou atendente(TURNO). Um funcionário não pode ser gerente e atendente ao mesmo tempo.
- Um gerente pode gerenciar vários atendentes e um atendente é gerenciado por apenas um gerente. Pode haver gerente sem gerenciar atendente, da mesma forma de uma atendente sem ser gerenciado por gerente.  
- Nessa empresa, um gerente pode supervisionar vários gerentes (SETOR), mas um gerente só pode ser pode ser supervisionado por um gerente.
- Além disso, cada atendente(Turno) pode atender muitos clientes(Cpf_cli, Nome_cli), assim como um cliente pode ser atendido(Data) por muitos atendentes numa data. Porém, um atendimento há a venda de um lanche.  
