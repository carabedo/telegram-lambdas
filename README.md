# Bot Telegram y AWS lambdas

Como armar un bot de telegram usando lambdas:

## Creamos un bot de telegram:

Hablamos con @BotFather creamos un bot `/newbot`y guardamos el token parecido a esto:

```
6697623661:AAFyWZD91HiPIeaKmF89iIsxAp9lgmfXXX
```

## Ahora creamos una lambda en aws

Utilizamos el runtime de `python` 
Y marcamos la opcion `Enable function URLInfo`

En cuerpo de la lmabda vamos a utilizar python:

```python

```
Y para que use la libreria requests tenemos que usar una layer con esa libreria.

