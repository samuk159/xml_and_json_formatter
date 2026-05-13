# XML and JSON Formatter

Formatador online de JSON e XML com:

* formatação automática
* syntax highlighting
* detecção automática de JSON/XML
* histórico persistente usando Local Storage
* interface simples e leve
* funcionamento totalmente client-side

## Acessar aplicação

urlXML and JSON Formatter[https://samuk159.github.io/xml_and_json_formatter/](https://samuk159.github.io/xml_and_json_formatter/)

## Funcionalidades

### Formatação automática

Ao colar um conteúdo no textarea, a aplicação identifica automaticamente se o conteúdo é:

* JSON
* XML

E realiza a formatação automaticamente.

---

### Syntax Highlight

A aplicação utiliza urlHighlight.js[https://highlightjs.org](https://highlightjs.org) para destacar:

* propriedades
* strings
* números
* tags XML
* atributos XML

facilitando a leitura humana.

---

### Histórico persistente

O histórico é salvo automaticamente no navegador usando Local Storage.

Recursos do histórico:

* até 50 registros
* ordenação do mais recente para o mais antigo
* armazenamento de data e hora
* persistência entre recarregamentos da página

---

## Tecnologias utilizadas

* HTML
* CSS
* JavaScript Vanilla
* urlHighlight.js CDN[https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.11.1/highlight.min.js](https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.11.1/highlight.min.js)

---

## Como executar localmente

Clone o repositório:

```bash
git clone https://github.com/samuk159/xml_and_json_formatter.git
```

Depois abra o arquivo:

```text
index.html
```

em qualquer navegador moderno.

---

## GitHub Pages

O projeto pode ser publicado usando:

* entity["product","GitHub Pages","GitHub Pages"]

Sem necessidade de backend ou servidor.
