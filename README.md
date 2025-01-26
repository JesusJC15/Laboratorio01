# Laboratorio 1
## Jesus Alberto Jauregui Conde

## Parte 1

### Punto 1
Crea un repositorio localmente.
![](/assets/punto1/1.png)

### Punto 2
Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opcion.
![](/assets/punto1/2.png)

### Punto 3
Averigua para que sirve y como se usan estos comandos git add y git commit -m
- git add

![](/assets/punto1/3.1.png)
- git commit -m

![](/assets/punto1/3.2.png)

### Punto 4
- Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
![](/assets/punto1/4.png)

### Punto 5
- Crea un repositorio en blanco (vacio) en GitHub.
![](/assets/punto1/5.png)

### Punto 6
- Configura el repositorio local con el repositorio remoto.
![](/assets/punto1/6.1.png)
![](/assets/punto1/6.2.png)
![](/assets/punto1/6.3.png)
![](/assets/punto1/6.4.png)
![](/assets/punto1/6.5.png)
![](/assets/punto1/6.6.png)

### Punto 7
- Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3.
![](/assets/punto1/7.1.png)
![](/assets/punto1/7.2.png)
![](/assets/punto1/7.3.png)

### Punto 8
- Configura el correo en git local de manera correcta.
![](/assets/punto1/8.png)

### Punto 9
- Vuelve a subir los cambios y observa que todo este bien en el repositorio remoto (en GitHub).
![](/assets/punto1/9.png)

## Parte 2

### Punto 1
- Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.
- Owner Jesus Alberto Jauregui Conde
- Colaborador Natalia Espitia Espinel

### Punto 2
- El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1.
![](/assets/punto2/2.1.png)
![](/assets/punto2/2.2.png)

### Punto 3
- El owner le comparte la url via Teams al colaborador.
![](/assets/punto2/3.png)

### Punto 4
- El colaborador acepta la invitación al repositorio.
![](/assets/punto2/4.png)

### Punto 5
Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.
- Jesus realizo cambios en el README.

### Punto 6
¿Que sucedió?
- Solo a un integrante en este caso Jesus le dejo realizar los cambios.

### Punto 7
La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos <<< === y >>> (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

### Punto 8
Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.
- Jesus realizo mas cambios en el README.

## Parte 3

### Punto 1
¿Hay una mejor forma de trabajar con git para no tener conflictos?

- Hacer commits pequeños y frecuentes: Esto reduce la probabilidad de conflictos grandes y facilita la revisión de cambios.
- Sincronizar a menudo: Mantén tu rama actualizada con la rama principal regularmente usando git pull o git fetch seguido de git merge.
- Usar ramas temáticas: Desarrolla nuevas características o arreglos en ramas separadas. Esto organiza mejor el trabajo y facilita la integración.
- Revisar y probar antes de hacer merge: Asegúrate de que los cambios sean revisados y probados antes de integrarlos a la rama principal.
- Comunicación constante: Coordina con tu equipo para estar al tanto de los cambios que cada uno está realizando.
- Resolver conflictos localmente: Si encuentras un conflicto, resuélvelo en tu entorno local antes de empujar los cambios.

### Punto 2
¿Qué es y como funciona el Pull Request?
- Es una solicitud para que los cambios sean revisados e integrados en la rama principal o en cualquier otra rama de destino del repositorio. Es especialmente útil para trabajar en equipo, ya que permite una revisión colaborativa del código.

Como funciona:
- Se crea una rama: Empieza creando una nueva rama en tu repositorio local para hacer los cambios. Por ejemplo, si estás trabajando en una nueva característica, crearías una rama llamada feature/nueva-caracteristica.
- Haz tus cambios y commits: Realiza tus modificaciones en esta rama y confirma (commit) tus cambios regularmente.
- Sube tu rama al repositorio remoto: Cuando hayas terminado, sube (push) tu rama al repositorio remoto.
- Abre un Pull Request: En la plataforma de gestión de código como GitHub, crea un Pull Request desde tu rama hacia la rama de destino (por lo general, la main o develop). Proporciona una descripción clara de los cambios.
- Revisión del código: Los miembros de tu equipo revisarán el código propuesto. Pueden dejar comentarios, sugerencias y aprobar o pedir cambios adicionales.
- Revisión y correcciones: Responde a los comentarios y realiza los cambios necesarios. Tus commits adicionales se agregarán al Pull Request.
- Merge: Una vez que todos están satisfechos con los cambios, alguien con permisos de merge integrará tu Pull Request en la rama de destino. Esto actualizará la rama de destino con los cambios propuesto.

### Punto 3
Creen una rama cada uno y suban sus cambios.
Imagenes: 