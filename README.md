# taller-git-github-iaw

Repositorio para el taller de git y github de IAW.

Se añade una nueva línea.

Se añade otra nueva línea.

# Encabezado de tipo h1

## Encabezado de tipo h2

### Encabezado de tipo h3

bla bla bla

**Texto en negrita**

__Texto en negrita__

*Texto en cursiva*

_Texto en cursiva_

# Instalación del servidor web apache

Para instalar el servidor ejecutamos el comando `apt update && apt install apache2`.

Ejecuta los siguientes comandos:

```
apt update
apt install apache2
```

```bash
apt update
apt install apache2
```

Crea el siguiente script:

```bash
#!/bin/bash
echo "Hola mundo"
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

# Enlaces a URLs externas

[Web del Celia](https://iescelia.org)

# Enlaces entre documentos internos

[Ir al archivo nuevo_archivo.md](nuevo_archivo.md)

[Ir a ciber.md](seguridad/ciber.md)

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

Enlace a [texto][web].

[web]: https://google.es
[1]: https://iescelia.org
[2]: https://github.com

# Imágenes

![Texto alternativo](https://s1.abcstatics.com/abc/sevilla/media/viajar/2021/06/14/s/vistas-almeria-general-kMgF--1248x698@abc.jpg)

# Imágenes internas

![](screenshots/01.jpg)

![](screenshots/02.jpg)

![](screenshots/03.webp)

# Listas desordenadas

* Elemento 1
* Elemento 2
* Elemento 3
- Elemento 4
- Elemento 5
- Elemento 6

- Apartado 1
  - Apartado 1.1
  - Apartado 1.2
- Apartado 2
  - Apartado 2.1
  - Apartado 2.2

Escribo una línea.  
Escrito otra línea.

Una línea.

Otra línea.

<!- Este texto es un comentario y no será renderizado -->

> [!NOTE]
> Useful information that users should know, even when skimming content.