# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educaci�n online

## Descripci�n del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le a�ade "pe" al final
- Si la palabra traducida tiene 10 o m�s letras, se debe partir en dos por la mitad y unir con un gui�n medio
- Por �ltimo, si la palabra original es un pal�ndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras may�sculas y min�sculas

## Instalaci�n

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

## Cr�ditos
- [Sacha Lifszyc](https://twitter.com/@slifszyc)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
