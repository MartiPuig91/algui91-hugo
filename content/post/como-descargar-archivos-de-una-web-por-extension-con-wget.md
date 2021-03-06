---
author: alex
categories:
- aplicaciones
- how to
- internet
date: '2016-01-01'
lastmod: 2017-03-20T10:03:58+01:00
mainclass: linux
url: /como-descargar-archivos-de-una-web-por-extension-con-wget/
tags:
- "android studio español guia"
- android studio tutorial
- descargar por extension wget
- wget
title: "Cómo descargar archivos de una web por extensión con wget"
---

Seguramente alguna vez hayas encontrado alguna web con montones de ficheros que te interesa descargarte, pero resulta un tanto arduo descargar los ficheros uno a uno. Si eres usuario Linux seguramente conozcas el comando *wget*. Este comando permite descargar todo el contenido de una web por extensión, de modo que si queremos descargar todos los ficheros con extensión *tar.gz* basta con ejecutar el siguiente comando:

```bash
wget -r -A.tar.gz <url>
```

Donde:

* **-A ó -accept** es una lista separada por comas de los sufijos o patrones de los ficheros que queremos descargar.
* **-r ó -recursive** actúa recursívamente sobre la web indicada.

Este comando no siempre funciona, ya que algunos servidores pueden haber bloqueado el acceso a *wget*.
