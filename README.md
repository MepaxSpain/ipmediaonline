# ipmediaonline

Selección de noticias de las webs de IPM para el panel Mepax Mailing test (pestaña News Selector).

- `news.json`: las 5-8 mejores noticias de cada web (esquema `news_selector_v1`). Cada web trae `ids` con los números de noticia.
- El panel descarga este archivo desde su dirección pública y lo importa.
- Cada noticia lleva `topic` (frase corta) y `theme` (tema en pocas palabras, sin verbo, en el idioma de la web), escritos por Claude. El panel enlaza los `theme` en una frase para el resumen de 150-300 caracteres de cada edición de LinkedIn.
