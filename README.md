## Eventos SCRUM

Sprint Planning - Primer Viernes despues del comienzo del Sprint alrededor de 17:30.

Daily - Lunes, Miercoles y Viernes por Whatsapp a las 13:00.

Sprint Review - El dia antes a la entrega. (Sabado o Domingo)

Sprint Retrospective - El dia antes a la entrega. (Sabado o Domingo).
Utilizaremos [Metroretro](https://metroretro.io/) como herramienta para las restrospectivas.

## Roles

- Scrum Master - Tomas

- Product Owner - Romina

- Development Team - Todos

## Estategias de branching

Utilizaremos GitFlow como estrategia de branching con un leve cambio, agregamos un nuevo tipo de rama llamada <strong>bug/X</strong> para diferenciar los bugs de los hotfixes.

- Main - Rama principal.

- Dev - Rama de desarollo. Esta sera la rama donde se mergeara los cambios realizados para cada iteracion.

- feature/X - Feature sobre historia X a desarollar.

- hotfix/X - Hotfix sobre historia X ya desarollada.

- bug/X - Fix de bug sobre historia X.

## Estategias de Pull request

Seguiremos la siguiente estrategia para los pull requests, y al final de cada sprint se creara un pull request de <strong>dev</strong> a <strong>main</strong> para pushear los cambios realizados sobre la iteracion.

- feature/X - Feature sobre historia X a desarrollar.

- hotfix/X - Hotfix sobre historia X ya desarrollada.

- bug/X - Fix de bug sobre historia X.

## Politicas de Trabajo

### Definition of Ready

Consideraremos que una Historia de Usuario estará lista para desarrollarese cuando cumpla con el criterio INVEST: Independiente, Negociable, Valiosa, Estimable, Corta (Short) y Testeable.

Es decir, para que una Historia de Usuario sera incluida en el siguiente Sprint por el equipo de desarrollo debe presentar las siguientes características:

- Independiente: no tendrá dependencias con otras historias que pudieran impedir su desarrollo. Por tanto, si para que la funcionalidad A sea posible es necesario tener la B, entonces la historia A no es independiente.

- Negociable: debe permitir espacio para la discusión con el Product Owner.

- Valiosa: debe aportar valor al cliente. Cumpliendo este criterio evitas desarrollar algo inútil.

- Estimable: puede ser estimada por el DevTeam (en tamaño relativo, en puntos de historia, etc).

- Corta: debe poder terminarse durante el Sprint. Si se encuentra una Historia demasiado grande, eso exige al Product Owner que la subdivida en varias Historias más pequeñas.

- Testeable: la Historia en su descripción debe contar con la información suficiente como para poder ser probada.

### Definition of Done

Consideraremos que una Historia de Usuario estará terminada cuando cumpla con las siguientes caracteristicas:

- Existencia de prototipo sobre la Historia de Usuario.

- Review sobre los cambios realizados por al menos 2 reviewers.

- Documentacion actualizada sobre los cambios realizados.

# Sprints

### Sprint 1 - [link](https://github.com/RominaGiaccio/Biladoniga-Amado-Oller-Giaccio/tree/dev/Sprint1)
