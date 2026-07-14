ACTO 1 — HOOK (0:00 - 0:25)

Visual Studio acaba de escribir decenas de líneas de código por ti.

En menos de diez segundos creó una aplicación completamente funcional.

La pregunta es…

¿Sabes realmente qué acaba de crear?

Porque si la respuesta es "no", probablemente estás construyendo aplicaciones sobre una base que todavía no entiendes.

Hoy vamos a descubrir exactamente qué ocurre en esos pocos segundos después de presionar el botón Crear Proyecto.

🎯 Objetivo del acto: despertar curiosidad.

ACTO 2 — EL PROYECTO (0:25 - 1:20)

Lo que estás viendo ahora mismo es exactamente el proyecto que Visual Studio acaba de generar.

No hemos agregado una sola línea de código.

No hemos eliminado absolutamente nada.

Esta es la plantilla oficial de ASP.NET Core.

Y aunque parece un proyecto muy pequeño…

Cada archivo tiene una responsabilidad específica.

Si entiendes esta estructura desde el principio…

Aprender ASP.NET Core será muchísimo más sencillo.

ACTO 3 — RECORRIENDO LA ESTRUCTURA (1:20 - 2:30)

Comencemos por la carpeta Controllers.

Aquí vivirán los endpoints de nuestra API.

Cada petición que llegue desde una aplicación, una página web o un teléfono terminará pasando por aquí.

Después encontramos appsettings.json.

Este archivo almacenará la configuración de nuestra aplicación.

Cadenas de conexión.

Variables.

Configuración por ambiente.

Más adelante se convertirá en uno de los archivos que más utilizaremos.

También encontramos WeatherForecast y WeatherForecastController.

Estos archivos no pertenecen a nuestra aplicación.

Son únicamente un ejemplo incluido por la plantilla para demostrar que todo funciona correctamente.

En los próximos episodios desaparecerán para dar paso a nuestro propio proyecto.

ACTO 4 — EL CORAZÓN DEL PROYECTO (2:30 - 4:00)

Y ahora llegamos al archivo más importante de este episodio.

Program.cs.

Toda aplicación ASP.NET Core comienza aquí.

La primera línea crea el WebApplicationBuilder.

Piensa en él como el punto donde comenzamos a preparar todo lo que la aplicación necesitará antes de iniciar.

Después registramos soporte para Controllers.

Más adelante entenderemos por qué este contenedor es una de las piezas más importantes de ASP.NET Core.

La plantilla moderna también registra soporte para OpenAPI.

Hoy no entraremos en detalle.

Porque el siguiente episodio estará dedicado exclusivamente a entender por qué aparece automáticamente desde el primer momento.

Cuando todo está preparado…

Construimos la aplicación.

Configuramos su comportamiento.

Registramos nuestros controladores.

Y finalmente…

Una sola instrucción cambia todo.

app.Run();

A partir de ese instante…

Nuestra aplicación comienza a escuchar solicitudes.

ACTO 5 — LA DEMOSTRACIÓN (4:00 - 4:40)

Vamos a ejecutarla.

Observa algo muy interesante.

Todavía no hemos escrito una sola línea de código propia.

Y aun así…

La aplicación ya funciona.

Eso demuestra todo el trabajo que la plantilla realiza automáticamente por nosotros.

ACTO 6 — CIERRE (4:40 - 5:00)

Comprender el punto de partida puede parecer un detalle pequeño.

Pero marca una enorme diferencia cuando comienzas a desarrollar aplicaciones profesionales.

En el próximo episodio descubriremos por qué ASP.NET Core incluye OpenAPI desde el primer minuto y empezaremos a construir nuestra propia API paso a paso.

Bienvenido a DevIA Academy.