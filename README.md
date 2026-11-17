# ipmediaonline

Selección de noticias de las webs de IPM para el panel Mepax Mailing test (pestaña News Selector).

- `news.json`: las 5-8 mejores noticias de cada web (esquema `news_selector_v1`). Cada web trae `ids` con los números de noticia.
- El panel descarga este archivo desde su dirección pública y lo importa.
- Cada noticia lleva `topic`: una frase corta (máx. 120 caracteres) escrita por Claude, en el idioma de la web, que cuenta de qué trata la noticia. El panel las junta para el resumen de 150-300 caracteres de cada edición de LinkedIn.
