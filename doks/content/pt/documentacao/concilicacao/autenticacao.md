---
title: "Autenticação"
description: ""
lead: "Congrats on setting up a new Doks project!"
date: 2025-05-08T08:54:32-03:00
lastmod: 2025-05-08T08:54:32-03:00
draft: false
weight: 702
seo:
  title: "Autenticação" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

Para acessar os recursos da API é necessário que seja realizada primeiramente a autenticação para gerar o JWT Token utilizado nas requisições.

A autenticação é feita utilizando os dados do cliente (estabelecimento).

```bash {title="Exemplo de Requisição de Autenticação"}
curl -X POST --location 'https://webapi.relatoriotef.com.br/autenticacao' \
--header 'Content-Type: application/json' \
--data '{
    "usuario": "<USUARIO>",
    "senha": "<SENHA EM BASE64>",
    "portal": "<SUFIXO>"
}'
```

{{< callout note >}}
A senha deve estar codificada em **Base64**.
{{< /callout >}}

{{< callout note >}}
A URL do portal deve ser informada no campo SUFIXO, identificando o portal que deseja acessar.
{{< /callout >}}
