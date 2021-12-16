# DontWait

## Descripción problema
En un supermercado surge el problema de las colas en espacios como la pescadería
charcutería, etc... El problema principal es predecir el intervalo de tiempo
entre cliente y cliente para que estos puedan seguir comprando en otras zonas,
sin tener que perder tiempo en la cola.

## Instalación
Necesitamos instalar el gestor de dependencias elegido, en mi caso [Poetry](docs/objetivo-3.md).
Seguimos los pasos de la [documentación oficial](https://python-poetry.org/docs/#installation) para poder instalarlo:
```shell
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

### Instalación del resto de dependencias
Ahora para instalar las dependencias, los siguientes pasos son: clonar el repositorio, hacemos `cd` para entrar
y por último `poetry install`.

Al hacer esto, también estamos instalando Invoke, ya que lo hemos incluido en el archivo pyproject.toml.


### Uso

Podemos ver la lista de tareas definidas con:
```shell
invoke --list
```

Para poder comprobar la sintaxis usamos:
```shell
 invoke check-sintax
```

Para poder comprobar buenas prácticas usamos:
```shell
invoke check-good-pratices
```

Para poder comprobar los tests usamos:
```shell
invoke test
```

## Documentación adicional

### Historias de usuarios.

Si quiere informarse acerca de las historias de usuario, hágalo [aquí](docs/usuarios.md).

### Elección de gestor de tareas y dependencias.
Si quiere informarse acerca de las elecciones de gestor de tareas y depencias, hágalo [aquí](docs/objetivo-3.md).

### Elección de herramienta para tests.
Si quiere informarse acerca de las elecciones de la herramienta de tests, hágalo [aquí](docs/objetivo-4.md).
