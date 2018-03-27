1. [Error] Stray start tag `html`.  
```html
o">↩<head><html>↩↩↩ 
---
o">↩<head>↩↩↩
```

2. [Warning] The `charset` attribute on the `script` element is obsolete.  
```html
" />↩↩    <script charset="UTF-8" class="daum_roughmap_loader_script" src="https://spi.maps.daum.net/imap/map_js_init/roughmapLoader.js"></script>
---
 />↩↩    <script class="daum_roughmap_loader_script" src="https://spi.maps.daum.net/imap/map_js_init/roughmapLoader.js"></script>
```

3. [Warning] The `type` attribute is unnecessary for JavaScript resources.
```html
pt>↩    ↩↩<script src="/static/js/kakaobankWeb-lib-1521081376857.min.js" type="text/javascript"></script>
---
pt>↩    ↩↩<script src="/static/js/kakaobankWeb-lib-1521081376857.min.js"></script>
```

4. [Warning] The `type` attribute is unnecessary for JavaScript resources.
```html
/script>↩↩<script src="/static/js/kakaobankWeb-resources-1521081376857.min.js" type="text/javascript"></script>
---
/script>↩↩<script src="/static/js/kakaobankWeb-resources-1521081376857.min.js"></script>
```

5. [Error] Stray end tag `head`.
```html
>↩↩</html></head>↩↩<bod
---
>↩↩</head>↩↩<bod
```

6. [Error] Stray end tag `head`.
```html
>↩↩</html></head>↩↩<bod
---
>↩↩</head>↩↩<bod
```

7. [Error] Start tag `body` seen but an element of the same type was already open.  
8. [Fetal Error]  Cannot recover after last error. Any further errors will be ignored.
```html
>↩↩</html></head>↩↩<bod
---
>↩↩</head>↩↩<bod
```

9. non-Semantic Markup