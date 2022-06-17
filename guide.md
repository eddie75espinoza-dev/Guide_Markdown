# Guía práctica básica de Markdown

<!-- Encabezados -->
# Titulo H1
## Titulo H2
### Titulo H3
#### Titulo H4
##### Titulo H5
##### Titulo H6
 <!-- Lineas divisorias ---  o ___ -->
___

<!-- Heading ID -->
(#custom-id)
### My Great Heading {#custom-id}
---
<!-- Texto -->
Texto en *Italic* 

Texto en **negrita**
 
Texto ~~tachado~~ 

<!-- Listas UL y OL -->
---
* listado 1
* listado 2
* listado 3
    * sublistado 3

1. orden 1
    1. suborden 1
2. orden 2
3. orden 3
 
<!-- Links -->
---
[Nombre del link](http://www.eddie.com)   
[Nombre del link personalizado](http://www.eddie.com "Eddie")   

___

<!-- Cita -->

> Eso es una cita

---
<!-- scripts de 1 linea entre backstics-->
`console.log('Hello World!')`

<!-- scripts de varias lineas entre backstics seguido del lenguaje -->
```python
import locale
from decouple import config
config.encoding = locale.getpreferredencoding(False)

DEBUG = config('DEBUG', default=True, cast=bool)   #default=False

def get_env_variable():
```
___
<!-- Tablas -->

|Titulo 1|Titulo 2|Titulo 3|
|--------|--------|--------|
|valor 1 | valor 2| valor 3|
|valor 4 | valor 5| valor 6|

| Syntax      | Description | Test Text          |
| :---        |    :----:   |               ---: |
| Header      | Title       | Here's this        |
| Paragraph   | Text        | And more           |
___

<!-- Fenced Code Block -->
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
<!-- Footnote -->
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

<!--  -->
I need to highlight these ==very important words==.

---

<!-- Deshabilitar enlace -->
`http://www.example.com`
http://www.example.com

---

