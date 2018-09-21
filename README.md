# Título completo del tema (grupo 0)

----------------

Repositorio tipo para el proyecto en equipos base. En este repositorio alojaréis el proyecto web de vuestro grupo para la asignatura Proyectos para la web.

Hay un directorio para cada unidad didáctica (o capítulo del proyecto), con la siguiente estructura:

```
0-nombreunidad
|_ actas-reuniones
|   |_ 2018MMDD.md
|   |_ ...
|_ *evaluaciones                               [evaluaciones-minombre]
|   |_ *MiApellidoMiNombre-2018MMDD.xlsx       [evaluaciones-minombre]
|_ img
|   |_ ...   
|_ README.md
```

- En el directorio `actas-reuniones` recogeréis las actas de las reuniones que el equipo base realice fuera de clase. Podéis ver más información sobre la estructura y formato de estas actas en el [modelo de acta](1-estrategia/actas-reuniones/2018MMDD.md). Un acta por reunión.
- El directorio `evaluaciones` estará presente solamente en el branch `evaluaciones-minombre` del fork en tu cuenta personal del repositorio del equipo. Más información en el `README.md` del branch modelo `evaluaciones-minombre`.
- En el directorio `img` recogeréis las imágenes que vayáis a incorporar a vuestro contenido.
- El archivo `README.md` será el que contenga el contenido de la sección o capítulo en sí.
- El archivo `roles.md` debe recoger quién se encargará de cada tarea durante el tiempo en el que estéis trabajando en el borrador del plano correspondiente. 

Este archivo `README.md` en la raíz del repositorio debería contener la introducción, presentación del proyecto etc.

Eliminad o comentad (rodeando de `<!--` y `-->`) el texto entre las dos líneas de guiones (incluidas) cuando iniciéis la redacción del proyecto.

## :construction: Flujo de trabajo para la redacción de los borradores de cada plano 

Antes de empezar con el primer borrador, cada miembro del grupo deberá hacer un fork del repositorio central (el que se encuentra en la [organización de la clase](https://github.com/DeustoPWEB2018)) a su cuenta personal. **Cada persona sólo realizará modificaciones sobre este fork, nunca directamente sobre el repositorio central.**

1. En la primera reunión del equipo, asignad los roles para el trabajo con este borrador.
    - La persona encargada de Secretaría rellenará el documento `roles.md` de la unidad correspondiente con los nombres para cada rol.
2. (EN CONSTRUCCIÓN) Realizad una división preliminar del archivo `README.md` correspondiente, con un apartado al que vaya a contribuir cada usuario.
2. Actualiza tu copia personal con las últimas modificaciones del repositorio central (tenéis [instrucciones](https://deustopweb2018.github.io/actualizar-fork) si os hacen falta)
3. Crea un nuevo branch en tu fork, con tu nombre de usuario y el nombre del plano en el que vas a trabajar (por ejemplo, `mberasategi-estrategia`).
4. Trabaja en tu ordenador sobre ese documento, realizando las modificaciones correspondientes en el apartado que vayas a trabajar tú del documento `README.md`. Recuerda hacer commit para confirmar tus cambios, y push para enviarlos a tu copia personal en la nube.
5. Cuando hayas avanzado lo suficiente en tu trabajo como para compartirlo con tus compañeros, inicia un pull request en el repositorio central:
    - clic en **compare across forks**
    - **Base fork** debe ser el repositorio central (en DeustoPWEB2018), branch `master`
    - **Head fork** debe ser tu fork personal, branch `tunombre-plano`
    -  En la barra lateral derecha, establece como **Reviewer** a la persona encargada del Control para este plano.
6. Cuando tu aportación personal esté lo suficientemente avanzada y finalizada como para incluirse en el borrador, y tenga el visto bueno de la persona de Control, la persona de Coordinación hará merge de tus cambios. 
7. Recuerda [actualizar tu fork personal](https://deustopweb2018.github.io/actualizar-fork) una vez tus cambios estén combinados con el repositorio central, y una vez más cuando hayáis realizado la entrega del borrador.

...


----------------

(vuestra introducción)

## Tabla de contenidos

1. [Estrategia](1-estrategia/README.md)
2. Alcance
3. Estructura
4. Esqueleto
5. Superficie

## Participantes en el equipo

- Apellidos, Nombre
- ...
