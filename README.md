# platzom

Platzom es un idioma inventado para el [Curso de fundamentos de javascript](https://platzi.com/js)
de [Platzi](https://platzi.com/js)

## Descipción del idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras,se debe partir a la mitad y
  unir con un guión del medio
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y
  se devuelve la misma palabra intercalando mayúsculas y minúsculas

## instrucciones de installación

```
npm install platzom
```

## Uso


```
import platzom from 'plazom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```


## Créditos

- [Adrian Ortiga](https://www.adrianortiga.com)

## license

[MIT](https://opensource.org/licenses/MIT)
