# Módulo | Unificação de Documentos

## Obter Cidadãos

```php

```

```python

```

> O JSON abaixo representa o retorno esperado:

```json
[
  {
    "nu_cns":"898004997600921",
    "no_cidadao":"JOÃO LUCAS SILVA PEREIRA"
  },
  {
    "nu_cns":"700000441832703",
    "no_cidadao":"GABRIREL ANTÔNIO MATEUS"
  }
]
```

Retorna todos os cidadãos ativos que não possuem cadastro com CPF no e-SUS. Utilize como referência o arquivo [`/elosus/assets/sql/unificacaoDocumentos/obter_cidadaos_cns.sql/`](https://bitbucket.org/elosistemas/elosus/src/master/assets/sql/unificacaoDocumentos/obter_cidadaos_cns.sql).

### HTTP Request

`GET http://apiesuspec.gestaoemsaudepublica.inf.br/bot/unificacaodocumentos/obter-cidadaos`

<aside class="notice">
Lembre-se de usar o X-token no header para autenticar o acesso ao endpoint!
</aside>