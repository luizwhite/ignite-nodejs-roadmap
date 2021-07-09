## O que é API?
  → *Application Programming Interface*

  → Conjunto de especificações de possíveis interações entre aplicações

  → Documentação para desenvolvedor
  
## O que é REST?
  → *Representation State Transfer*

  → Modelo de Arquitetura

  → 6 regras

&nbsp;&nbsp;&nbsp;&nbsp;∘ **Client-Server**

&nbsp;&nbsp;&nbsp;&nbsp;∘ ***Stateless***

&nbsp;&nbsp;&nbsp;&nbsp;∘ **Cache**

&nbsp;&nbsp;&nbsp;&nbsp;∘ Interface Uniforme

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;∘ **Identificação dos recursos** (p.ex. http://enderecoservidor.com.br/products)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;∘ **Representação dos recursos** (p.ex. JSON)
      
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;∘ **Mensagens auto-descritivas**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;∘ HATEOAS (Hypertext As The Engine Of Application State)

&nbsp;&nbsp;&nbsp;&nbsp;∘ Camadas

&nbsp;&nbsp;&nbsp;&nbsp;∘ Código Sob Demanda

## Métodos de Requisições - HTTP Verbs
  → GET

  → POST

  → PUT (atualização)

  → DELETE

  → PATCH (atualização parcial)

## HTTP Codes
  → 1xx: Informativo - a solicitação foi aceita ou o processo continua em andamento

  → 2xx: Confirmação

  → 3xx: Redirecionamento

  → 4xx: Erro do cliente

  → 5xx: Erro no servidor
      
## Parâmetros das Requisições
  → Header Params
  → Query Params
  → Route Params
  → Body Params

## Boas práticas de API REST
  → A utilização correta dos métodos HTTP

  → A utilização correta dos status no retorno das respostas

  → Padrão de nomenclatura

  &nbsp;&nbsp;→ Busca de usuários - GET

  &nbsp;&nbsp;→ Busca de usuário por id - GET

  &nbsp;&nbsp;→ Deleção de um usuário - DELETE

  &nbsp;&nbsp;→ Atualização do status do usuário - PATCH
