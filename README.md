# Terraform

---

Curso de Terraform en Platzi

## Definición

La infraestructura como código es un enfoque para la automatización de infraestructura basado en las prácticas de desarrollo de software.

Tu escribes la infraestructura que quieres y luego construyes la infraestructura que quieres con esa información.

## Principios

- Los sistemas se pueden reproducir fácilmente
- Los sistemas son desechables
- Los sistemas son consistentes
- Los sistemas son repetibles
- El diseño siempre está cambiando

### Los sistemas se pueden reproducir fácilmente

Si tengo un archivo de definición yo sé lo que quiero crear. Si tengo la definición de la estructura es más fácil reproducir el sistema con los valores.

### Los sistemas son desechables

Si un servidor falla puedes desecharlo y volverlo a construir porque tengo la estructura ya escrita.

### Los sistemas son consistentes

Tienes un archivo que dice lo que tienes en el servidor. Cuentas con una fuente de verdad que dice lo que debería verse reflejado en el servidor.

### Los sistemas son repetibles

Puedes escribir una definición de código una única vez y utilizarla n veces.

### El diseño siempre están cambiando

Es más fácil cuando tu tienes el diseño plasmado en un archivo de definición porque sabes lo que tienes que hacer.

## Infraestructura cómo código: Prácticas generales

### Utilizar archivos de definición

Todas las herramientas de infraestructura como código tienen un formato propio para definir infraestructura.

### Los procesos y los sistemas deben ser autodocumentados

Utilizar el enfoque de infraestructura como código nos permite reutilizar el código. Otras personas pueden utilizarlo y por eso es importante debe estar documentado.

### Versionar todas las cosas

Trazar los cambio, si algo sale mal puedo regresar el archivo puedo regresar en el tiempo y dejarlo como si no hubiese pasado nada.

### Preferir cambios pequeños

Para no impactar tanto y mantener los servicios siempre disponibles.

