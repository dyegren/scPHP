# scPHP

Librería con funciones varias para PHP.

Este se divide en distintas finalidades de funciones usando como prefijo `sc_`

**Ejemplo:** `sc_test_var_dump('prueba')`

* **str:** manejo de string
```
sc_str_reemplazar_expresion_regular('Hola', '\w+',' ')
```
* **test:** manejo de testeo
```
sc_test_echo('texto')
```
* **sql:** manejo de testeo
```
sc_sql_lookup('SELECT * FROM usuario')
```
* **js:** manejo de testeo
```
sc_js_alert('texto')
```
* **is:** saber que tipo de dato es
```
sc_is_array(array('valor'))
```
* **url:** manejo de url
```
sc_url_informacion_sitio_actual()
```
* **arr:** manejo de array
```
sc_arr_incluye_expresion_regular(array('prueba'),'\w+')
```
* **fec:** manejo de fechas
```
sc_fec_formatear('2021-12-12 02:20:00','Y-m-d')
```

## Instalación 
#### Al descargarla para añadir se incluye con un require

```
require_once '/scPHP.php'
```

## Ejecutando las pruebas

Puedes escribir `sc_var_dump('prueba')` o `sc_test_var_dump('prueba')` para saber si esta fue instalada correctamente

## Construido con 

* PHP - Lenguaje de programación

## Licencia 

Este proyecto está bajo la Licencia (MIT) 


---
⌨️ con ❤️ por [yosoymitxel](https://github.com/yosoymitxel)

