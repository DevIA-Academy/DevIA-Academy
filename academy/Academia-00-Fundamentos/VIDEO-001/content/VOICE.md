# VOICE.md
## VIDEO-001

Duración objetivo:
4:30 a 5:00 minutos

---

# Escena 1

¿Alguna vez te has preguntado qué ocurre realmente cuando creas una Web API en Visual Studio?

Miles de desarrolladores crean proyectos nuevos todos los días.

Pero muy pocos se detienen a entender qué acaba de generar realmente la plantilla.

Y comprender ese punto de partida puede marcar una enorme diferencia cuando empiezas a construir aplicaciones profesionales.

Hoy no vamos a escribir código.

Hoy vamos a descubrir qué acaba de crear Visual Studio.

Bienvenido a DevIA Academy.

(Pausa 1 segundo)

---

# Escena 2

Este proyecto es exactamente el que Visual Studio acaba de generar.

No hemos agregado absolutamente nada.

No hemos eliminado ninguna línea.

Vamos a recorrerlo juntos.

Comencemos por la estructura.

Controllers.

Aquí vivirán los endpoints de nuestra API.

Cada petición HTTP llegará aquí.

Después encontramos appsettings.json.

Este archivo almacenará la configuración de nuestra aplicación.

Conexiones.

Opciones.

Variables por ambiente.

Más adelante trabajaremos mucho con él.

WeatherForecast y WeatherForecastController existen únicamente como ejemplo.

Su objetivo es demostrar que la plantilla funciona correctamente.

En nuestra serie los reemplazaremos por código real.

Y finalmente llegamos al archivo más importante de este episodio.

Program.cs.

---

# Escena 3

Toda aplicación ASP.NET Core comienza aquí.

La primera línea crea el WebApplicationBuilder.

Puedes imaginarlo como el punto donde comenzamos a preparar todo lo que la aplicación necesitará antes de iniciar.

Después registramos soporte para Controllers.

Más adelante veremos cómo este contenedor se convierte en una de las piezas más importantes de ASP.NET Core.

La plantilla también registra soporte para OpenAPI.

No profundizaremos todavía.

Porque dedicaremos el siguiente episodio exclusivamente a entender por qué forma parte de la plantilla moderna.

Una vez registrados todos los servicios...

Construimos la aplicación.

Después configuramos el comportamiento durante el desarrollo.

Y finalmente...

Con una sola instrucción...

app.Run();

Nuestra aplicación comienza a escuchar solicitudes.

(Pausa)

Y en ese momento...

La Web API ya está viva.

---

# Escena 4

Ejecutemos la aplicación.

Todavía no hemos escrito una sola línea de código propia.

Y sin embargo...

La API ya funciona.

Eso demuestra todo el trabajo que la plantilla realiza por nosotros desde el primer segundo.

---

# Cierre

Comprender el punto de partida es el primer paso para construir aplicaciones profesionales.

En el siguiente episodio descubriremos por qué la plantilla incluye OpenAPI y comenzaremos a transformar este proyecto en una API real.

Nos vemos en DevIA Academy.