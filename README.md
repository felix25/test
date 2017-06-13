# Idioma

Este es un platzom inventado para fundamentos de JavaScript [luis](https://twitter:com/felixALFM)

## Descripción del platzom
- Si la palabra termina en "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regal anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso
```
import platzom form 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") //SoMeTeMoS
```

## Créditos
- [Luis Felix](https://twitter.com/felixALFM)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
```