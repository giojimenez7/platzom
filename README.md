# Platzom

Platzom es un idioma inventado para el 
[Curso de Fundamentos de JavaScript](https://platzi.com/js) 
de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o mas letras, se debe partir en dos por la mitad
y unir con guión medio
- Por ultimo, si la palabra original es un palíndromo, ninguna regla anterior cuenta
y se devuelve la misma palabra pero intercambiando letras mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Créditos
- [Giovanny Jimenez](https://www.facebook.com/Giojimarc)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
