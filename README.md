# Informe de pruebas del proyecto

```py
integrantes_entrega: List =  ["Angel Mejia", "Xiang Zamata", "Frank Munguia", "Eduardo Perez"]
```

## Pruebas unitarias

### Almacenamiento de cookies primarias de la aplicación web

Cuando el usuario se registre a través de la API de Google, sus datos deben quedar
alojados de tal manera que cuando se ralice una petición al servidor, no se le solicite
volver a iniciar sesión.

### Cambio de lenguaje al seleccionar inglés o español

Cuando el usuario seleccione uno de los idiomas disponibles de la plataforma, el lenguaje
de la misma debe cambiar exitosamente sin presentar ninguna incoherencia en la traducción.

### El motor de busqueda de ofertas de trabajo halla palabras clave

Las oportunidades de trabajo filtradas son mostradas a partir de la entrada del usuario, por lo que si existen
coincidencias, no se muestra ningun resultado, asi como si existen resultados, estos son mostrados
con los detalles correspondientes.

### Filtrado de ofertas de trabajo

Los usuarios deben poder filtrar las ofertas de trabajo en la sección de oportunidades laborales en función
a sus preferencias iniciales y además sus intereses reales dependiendo de la industria y sector.


### Categorización de oportunidades laborales

Cuando un reclutador publica una oferta de trabajo, esta es categorizada con una de las etiquetas
relacionada a la industria y el sector de la oportunidad laboral de tal manera que los usuarios puedan filtrar la misma
en base a sus preferencias.

## Conexión a aplicación de videoconferencia

El sistema embedido debe permitir a los involucrados unirse a la videoconferencia de forma automatica según el flujo de selección
añadido al reclutador y notificado al postulante al buscar obtener un puesto de trabajo, por lo que la interacción debe asegurar el intercambio
de información sin retrasos mayores a 1 segundo.

## Pruebas integrales

### Filtrado de datos importantes de postulantes para confirmar y agendar posible entrevista

Cuando un reclutador analiza las competencias de un postulante a través de la herramienta de revisión
de prospecto, este peude identificar lo apto del postulante para el puesto aplicado.

### Indexación de las ofertas de trabajo en la sección de oportunidades laborales

Las ofertas de trabajo deben ser indexadas en orden alfabetico por defecto; sin embargo,
si uno de los reclutadores está relacionado a una empresa que contrató el servicio premium
de la aplicación, sus ofertas de trabajo son indexadas de manera prioritaria
independientemente del orden alfabetico de las oportunidades laborales en general.

### Adición de los postulantes a oportunidades laborales a monitoreo de proceso de selección

Cuando un usuario postula a una oferta de trabajo, este es añadido al flujo de reclutamiento
del reclutador que publico el puesto, por lo que es notificado de las fases de este hasta ser
contratado o rechazado por alguna razón en específico.

## Pruebas de aceptación

### Cumplimiento de tutorial
Si los agentes dependiendo del tipo de usuarios completan la exploración de la aplicación
web exitosamente validando el correcto funcionamiento de la plataforma, entonces podemos
concluir que hemos pasado la prueba de aceptación del producto respecto a aquellos involucrados
que interactuan con el sistema.


## Prueba del sistema

### Flujo de uso estable

1. Almacenamiento de registro de usuarios
2. Recomendaciones de puestos de trabajo basado en habilidades
3. Indexación de oportunidades laborales
4. Aplicación a oportunidades laborales
5. Análisis de postulantes a oportunidades laborales
6. Filtrado de datos de postulantes para validar competencia
7. Monitoreo de proceso de reclutamiento para usuario
8. Monitoreo de proceso de reclutamiento para reclutador
9. Funcionamiento de la aplicación de videoconferencia embedida
10. Enrutamiento de elementos de la barra de navegación a páginas de la aplicación
11. Botón para cerrar sesión
12. Botón para iniciar sesión
13. Entrada de detalles de oportunidades laborales al publicar anuncio
14. Entrada de datos de usuarios en su perfil
15. Configuración de privacidad para reclutadores
16. Configuración de privacidad para usuarios
17. Implementación de servidor para la interacción de agentes por chat
18. Monitoreo de comunicados a través de sección de notificaciones
