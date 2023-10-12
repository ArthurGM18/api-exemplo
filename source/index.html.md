---
title: API ESUS PEC

language_tabs: # must be one of https://github.com/rouge-ruby/rouge/wiki/List-of-supported-languages-and-lexers
  - php
  - python

toc_footers:
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - auth
  - eliminacaoduplicidadepec
  - unificacaodocumentos

search: true

code_clipboard: true

meta:
  - name: description
    content: Documentação para API ESUS PEC
---

# Introdução

API desenvolvida para padronizar as consultas feitas ao banco do e-SUS AB PEC. 

Inicialmente, será construida para ser consumida por duas aplicações distintas, sendo elas o [bot](https://bitbucket.org/elosistemas/elosus/) e o módulo Gestão em Saúde em [elosis](https://bitbucket.org/elosistemas/elosis/). Portanto, teremos exemplos de como integrar a API tanto em Python quanto em PHP.