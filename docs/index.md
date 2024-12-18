
<table class="header">
  <tbody><tr>
    <td colspan="2" rowspan="2" class="width-auto">
      <h1 class="title">The Monospace Web theme for Mkdocs 🤘</h1>
      <span class="subtitle">A minimalist design </span>
    </td>
    <th>Version</th>
    <td class="width-min">v0.1.1</td>
  </tr>
  <tr>
    <th>Updated</th>
    <td class="width-min"><time style="white-space: pre;">2024-12-18</time></td>
  </tr>
  <tr>
    <th class="width-min">Authors</th>
    <td class="width-auto">
<a href="https://wickstrom.tech"><cite>Oskar Wickström (CSS)</cite></a><br>
<a href="https://www.scamp.fr"><cite>Sébastien Campion (mkdoc)</cite></a>
</td>
    <th class="width-min">License</th>
    <td>MIT</td>
  </tr>
</tbody></table>



## Welcome to MonoWeb Mkdocs theme


For full documentation of mkdocs visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Sub commands h2

- bullet 1
- bullet 2


## Project layout

    .
    ├── __init__.py
    ├── base.html
    ├── css
    │   └── theme.css
    ├── js
    │   └── theme.js
    ├── main.html
    ├── mkdocs_theme.yml
    ├── nav.html
    └── search.html


## Table

| Titre 1 | Titre 2 | Titre 3 |
| --- | --- | --- |
| Contenu 1 | Contenu 2 | Contenu 3 |
| Contenu 4 | Contenu 5 | Contenu 6 |


Include a json example file:

```json
{
  "title": "Person",
  "type": "object",
  "properties": {
    "firstName": {
      "type": "string"
    },
    "lastName": {
      "type": "string"
    },
    "age": {
      "description": "Age in years",
      "type": "integer",
      "minimum": 0
    }
  },
  "required": ["firstName", "lastName"]
}
```
 Include a image example file:
 
![Image Mont Saint Michel](https://upload.wikimedia.org/wikipedia/commons/7/78/Mont-Saint-Michel_vu_du_ciel.jpg)




