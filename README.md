# Controller
- Criar uma `ViewModel` para repassar a um `View`

#


# ViewModel
- Modelo de Dados usada por uma `View`
- Contém apenas os dados que se deseja apresentar\exibir na `View`
    - Ex: Conteúdo estático de uma `Label`
    - Ex: Conteúdo dinâmico de um `Dropdown List`
- Um `ViewModel Object` pode conter dados de vários `DTOs`
- Um `ViewModel Object` NÃO DEVE ter `Business Logic`
- O `Data Type` das propriedades de `ViewModel Object` pode ser diferente do `Data Type` de um `DTO`
    - Dinheiro (double) por ser armazenado como um texto (string)

# DomainModel
- 

# DTO
- Usado para tansporta dados
