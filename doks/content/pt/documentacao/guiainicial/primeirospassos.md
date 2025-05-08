---
title: "Primeiros Passos"
description: ""
lead: ""
date: 2025-05-08T08:54:32-03:00
lastmod: 2025-05-08T08:54:32-03:00
draft: false
weight: 81
sidebar:
  collapsed: true
seo:
  title: "Primeiros Passos" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

A Multiplus Card oferece diversas soluções de pagamento, como TEF, Pix (QRMultiplus), Gateway de Pagamento (Link Pago), App PinPDV Lite, entre outras. Cada uma dessas soluções pode ser integrada de diferentes maneiras. Por exemplo, no caso do TEF, há quatro opções distintas de integração: DLL TefClientMC Modo Interativo, DLL TefClientMC Modo Client, Troca de Arquivos e Webservice. Por isso, antes de iniciar o processo de integração, recomendamos que você consulte nossos times de Integração e Comercial para identificar a solução que melhor atende às necessidades de sua automação.


{{< callout context="caution" title="Atenção" icon="outline/alert-triangle" >}}
A documentação é atualizada continuamente. Recomendamos consultá-la regularmente para se manter informado sobre novos recursos, alterações de funcionalidades e eventuais descontinuações. Em caso de *breaking changes*, você será notificado caso sua aplicação esteja integrada às soluções da Multiplus Card.
{{< /callout >}}

## APIs

Os produtos integrados via APIs podem utilizar diferentes métodos de autenticação. Alguns utilizam um **token** fornecido pela Multiplus Card, enquanto outros utilizam **JWT (JSON Web Token)**. Portanto, é normal encontrar variações nesse aspecto entre os produtos.

Em relação às URLs, em alguns casos você poderá se deparar com o domínio `webapi.relatoriotef.com.br`. Isso ocorre devido à característica *white label* dos produtos. No entanto, o domínio `webapi.multipluscard.com.br` pode ser utilizado da mesma forma, sem prejuízo ao funcionamento da integração.


## Links Úteis

- [Site da Multiplus Card](https://multipluscard.com.br)
- [Portal do Representante](https://portal.multipluscard.com.br/representante)
- [Portal do Cliente](https://portal.multipluscard.com.br/)
- [Portal PinPDV](https://portal.pinpdv.com.br/)


## Dúvidas?

Se tiver qualquer dúvida ou precisar de suporte, estamos à disposição pelo e-mail: atendimento@multipluscard.com.br