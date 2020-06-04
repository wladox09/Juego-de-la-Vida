# Juego-de-la-Vida

juego de la vida en python basado en el ejemplo de Dot CSV

El Juego de la Vida
En 1970, el matemático británico John Conway creó su "Juego de la vida", un conjunto de reglas que imita el crecimiento caótico pero modelado de una colonia de organismos biológicos.

El "juego" tiene lugar en una cuadrícula bidimensional que consiste en células "vivas" y "muertas", y las reglas para pasar de generación en generación son simples:

* Sobrepoblación: si una célula viva está rodeada por más de tres células vivas, muere.
* Estasis: si una célula viva está rodeada por dos o tres células vivas, sobrevive.
* Subpoblación: si una célula viva está rodeada por menos de dos células vivas, muere.
* Reproducción: si una célula muerta está rodeada por exactamente tres células, se convierte en una célula viva.
Al hacer cumplir estas reglas en pasos secuenciales, pueden aparecer patrones hermosos e inesperados.

## Virtualenv

    pip3 install virtualenv

    virtualenv jv

    source jv/bin/activate

    deactivate

## Dependencies

    pip install -r requirements.txt
