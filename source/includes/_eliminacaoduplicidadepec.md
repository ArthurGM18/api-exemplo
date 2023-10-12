# Módulo | Eliminar Duplicidade PEC

## Obter Duplicidades

```php

```

```python

```

> O JSON abaixo representa o retorno esperado:

```json
[
  {
    "nome":"ACACIO RAMOS MARTINS",
    "nascimento":"04/04/1971",
    "mae":"PASTORINA ANTONIA MARTINS"
  },
  {
    "nome":"ADALBERTO DE FARIA",
    "nascimento":"28/06/1947",
    "mae":"MARIANA COSTA"
  }
]
```

Retorna todas as duplicidades de um determinado tipo. Utilize como referência os arquivos em [`/elosus/assets/sql/eliminacaoduplicidadepec/`](https://bitbucket.org/elosistemas/elosus/src/master/assets/sql/eliminacaoduplicidadepec/).

### HTTP Request

`GET http://apiesuspec.gestaoemsaudepublica.inf.br/bot/eliminacaoduplicidadepec/obter-duplicidades`

### Query Parameters

Parâmetro | Valor Padrão | Descrição |
--------- | ------------ | --------- |
modulo    | Identico     | Seleciona o tipo de unificação `[Identico ~ DataFonetico ~ MaeFonetico ~ NomeFonetico]`

<aside class="notice">
Lembre-se de usar o X-token no header para autenticar o acesso ao endpoint!
</aside>

## Obter Resumo de Unificação por Compentência

```php

```

```python

```

> O JSON abaixo representa o retorno esperado:

```json
[
  {
    "ANO_MES":202307,
    "QUANTIDADE":"8486"
  },
  {
    "ANO_MES":202308,
    "QUANTIDADE":"8801"
  }
]
```

Retorna um resumo geral da quantidade de unificações feitas. Utilize como referência o arquivo [`/elosus/assets/sql/eliminacaoduplicidadepec/resumo.sql`](https://bitbucket.org/elosistemas/elosus/src/master/assets/sql/eliminacaoduplicidadepec/resumo.sql).

### HTTP Request

`GET http://apiesuspec.gestaoemsaudepublica.inf.br/bot/eliminacaoduplicidadepec/obter-duplicidades`