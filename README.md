#API RestCountries

# Sobre o projeto
Projeto em PHP que consome a API [RestCountries](https://restcountries.com/ "Site da API Restcountries").

## Telas do projeto
![Escolha dd país](https://github.com/joaopauloleitecosta/api_restcountries/blob/main/escolha_mini.png)

![Detalhes do país](https://github.com/joaopauloleitecosta/api_restcountries/blob/main/detalhes_mini.png)

## Rotas usadas na API

#### Retorna todos os países

```http
  GET https://restcountries.com/v3.1/all
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `all` | `string` | **Obrigatório**. Retorna todos os países |

#### Retorna um país

```http
  GET https://restcountries.com/v3.1/name/{name}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `name`      | `string` | **Obrigatório**. O nome do país que você quer |


# Tecnologias utilizadas
## Back end
- PHP
## Front end
- HTML / CSS / JS 
- Bootstrap