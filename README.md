# MVC - Model-View-Controller
- Padrão de arquitetura de Software
- Tem o objeto de seprar o sistema em três componentes
- Cada componente tem funções bem definidas

## Model
- Regras de Negócio
- Regras de Acesso a Dados
- Regras de Validação de Dados
- Entidades do Negócio

## View
- Exibir Dados para fora do sistema
- Coletar Dados para dentro do sistema

## Controller
- Converte solicitações da `View` em chamadas para o `Model`
- Converte respostas do `Model` em dados exibíveis para a `View`



#


## ViewModel
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


# Regras de negócio
- São os processo realizados pela empresa e que devem ser automatizados pelo sistema

# Entidadas
- São objetos usados nos processos realizados pela empresa e que devem ser representados pelo sistema
