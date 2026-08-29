# PulseUp: Your Social Copilot

Quiero construir una aplicación web/mobile-first llamada PulseUp.

1. CONCEPTO GENERAL

PulseUp es una aplicación de bienestar social para personas que:

trabajan remoto desde casa;

viven solas;

no conviven con pareja, familiares o roomies;

pueden pasar muchas horas o días con poca interacción humana presencial;

quieren moverse, cambiar de ambiente, conocer personas o simplemente trabajar cerca de otros;

no quieren usar aplicaciones de citas ni redes sociales tradicionales para resolver este problema.

La idea principal es:

“Vivir solo no debería significar sentirse solo.”

PulseUp funciona como un copiloto social.

La app entiende qué necesita la persona en ese momento, analiza su energía social, tiempo disponible, ubicación aproximada e intereses, y le propone una pequeña misión presencial con personas compatibles cerca de ella.

El objetivo no es aumentar el tiempo de pantalla.

El objetivo es utilizar tecnología para sacar a la persona de la pantalla y llevarla a una experiencia real.

2. PRINCIPIO DEL PRODUCTO

NO quiero construir otra red social tradicional.

No quiero:

feed infinito;

followers;

likes;

contenido viral;

perfiles estilo Tinder;

swipe de personas;

chats sin contexto;

rankings de popularidad.

Quiero este flujo:

Necesidad → IA → misión → mapa → pequeño grupo → encuentro presencial → puntos → repetir conexión → comunidad → rewards.

La frase conceptual es:

“Una red social que intenta sacarte de la red social.”

3. PÚBLICO OBJETIVO

Persona principal:

25 a 45 años;

profesional;

freelancer;

emprendedor;

trabajador remoto;

trabaja principalmente desde casa;

vive solo;

está ubicado inicialmente en ciudades urbanas;

valora su independencia;

puede pasar gran parte del día frente al computador;

no necesariamente está buscando “hacer mejores amigos”;

quiere aumentar pequeñas interacciones humanas reales.

Ejemplos de necesidades:

tomar un café acompañado;

caminar 15 o 30 minutos;

trabajar cerca de otras personas;

conversar;

salir de casa;

hacer actividad física;

tomar una pausa;

participar en una actividad grupal;

ampliar su círculo social.

4. PROPUESTA DE VALOR

PulseUp debe responder principalmente a esta pregunta:

“Estoy trabajando solo en casa. ¿Qué puedo hacer ahora para salir de la rutina?”

La aplicación debe reducir al máximo el esfuerzo del usuario.

No preguntarle primero:

“¿Qué evento quieres organizar?”

Primero decir:

“Encontré algo para ti.”

La IA debe funcionar como un facilitador social.

5. BRANDING

Nombre:

PulseUp

Concepto:

Social wellness + remote work + comunidad + IA + gamificación.

Diseño:

dark mode premium;

moderno;

tecnológico;

humano;

energético;

dinámico;

no corporativo;

no infantil;

no parecer dating app.

Colores aproximados:

Background:
#06101D

Panel:
#0C1A2B

Secondary panel:
#10243A

Cyan:
#5BE7FF

Mint:
#59EFB7

Violet:
#9B7CFF

Pink:
#FF80BF

Yellow:
#FFD56B

Primary text:
#F5FBFF

Secondary text:
#91A5B9

Utilizar:

gradientes suaves;

glassmorphism ligero;

cards redondeadas;

sombras suaves;

microanimaciones;

iconos Lucide;

progress indicators;

mapas visuales;

markers personalizados.

Mobile-first.

Debe verse excelente en:

iPhone;

Android;

tablet;

desktop.

6. STACK

Construir utilizando:

React;

TypeScript;

Tailwind CSS;

shadcn/ui;

Lucide Icons.

Backend:

Supabase.

Mapas:

Google Maps Platform.

Utilizar APIs modernas y actuales.

Preparar la arquitectura para:

Google Maps JavaScript API;

Google Maps Routes Library;

Google Places API New;

Advanced Markers;

Supabase Database;

Supabase Realtime;

autenticación futura;

IA futura;

ElevenLabs futuro;

Web Push Notifications;

PWA.

Variables de entorno:

VITE_GOOGLE_MAPS_API_KEY

SUPABASE_URL

SUPABASE_ANON_KEY

Nunca hardcodear credenciales.

7. NAVEGACIÓN

Bottom navigation móvil:

Inicio

Pulse Map

Misiones

Rewards

Perfil

En desktop:

sidebar o navbar.

8. HOME

La Home NO debe mostrar feed.

Debe comenzar con:

Hola, Eli 👋

Texto:

“Tu casa es tu oficina. Hoy no tiene que ser todo tu mundo.”

Mostrar estado:

🏠 Remote · Home alone

Después mostrar sección protagonista:

✨ BREAK ME OUT

Texto:

“¿Qué necesita tu día?”

Opciones:

🤝 Ver personas
“Quiero conversar.”

🚶 Moverme
“Necesito salir de la silla.”

🌿 Recargar
“Necesito cambiar de aire.”

💻 Compañía
“Quiero trabajar cerca de alguien.”

9. SOCIAL BATTERY

Después preguntar:

¿Cuánta energía social tienes hoy?

Opciones:

🔋 LOW

“Quiero compañía sin hablar demasiado.”

🔋🔋 MEDIUM

“Me gustaría conversar un poco.”

🔋🔋🔋 HIGH

“Quiero conocer gente.”

✨ SORPRÉNDEME

“Que la IA decida.”

Este concepto debe llamarse:

Social Battery

No utilizar términos como introvertido/extrovertido.

La Social Battery cambia todos los días.

10. TIEMPO DISPONIBLE

Preguntar:

¿Cuánto tiempo tienes?

Opciones:

15 min

30 min

60 min

Esta tarde

Esta noche

11. MOTOR DE MISIONES

Para el MVP utilizar reglas simuladas.

Inputs:

necesidad;

Social Battery;

tiempo;

ubicación;

eventos existentes;

distancia;

intereses.

Generar una misión personalizada.

12. EJEMPLO BREAK ME OUT

Necesidad:

Ver personas.

Social Battery:

Medium.

Tiempo:

30 minutos.

Resultado:

☕ Coffee Connection

Texto:

“Sal de casa, camina hasta un café aliado y comparte una pausa con tres personas que también trabajan remoto y viven solas.”

Mostrar:

⏱ 30 min

👥 4 personas

📍 800 m

⚡ +80 Pulse Points

✨ 92% para ti

También mostrar:

¿Por qué esta misión?

“Tu Social Battery está en nivel medio. Encontramos una experiencia suficientemente social para conectar, pero en un grupo pequeño.”

CTA:

Aceptar misión

13. EJEMPLOS DE MISIONES

Social Battery Low:

Silent Cowork 💻

“Trabaja cerca de otras personas sin obligación de conversar.”

Social Battery Medium:

Coffee Connection ☕

Walk & Talk 🚶

Social Battery High:

Remote Social Sprint ⚡

Recharge:

Park Reset 🌿

Move:

Move Crew 🏃

Company:

Cowork Sprint 💻

Surprise:

Mystery Meetup ✨

14. PULSE MAP

Crear una funcionalidad principal llamada:

Pulse Map

Debe ser una de las pantallas más importantes.

Objetivo:

Mostrar:

“¿Qué está pasando cerca de mí?”

El mapa debe mostrar experiencias reales disponibles alrededor del usuario.

15. TIPOS DE EVENTOS

Mostrar:

☕ Coffee Connections

🚶 Walk & Talk

💻 Cowork Sprint

🧘 Yoga

🌿 Park Reset

🥗 Remote Lunch

🏃 Sport

🎨 Talleres

🎯 Misiones

👥 Pulse Pods

🎵 Experiencias culturales

📚 Learning Sessions

16. EXPERIENCIA DEL MAPA

En móvil:

Mapa ocupando aproximadamente 60% de la pantalla.

Abajo:

Bottom sheet deslizable.

Debe mostrar:

8 cosas pasando cerca de ti

Cards horizontales o verticales.

17. UBICACIÓN DEL USUARIO

Solicitar permiso únicamente cuando sea necesario.

Mostrar:

📍 Tú

No mostrar públicamente dirección exacta.

No compartir coordenadas residenciales.

Para preferencias persistentes utilizar:

Zona frecuente.

Ejemplo:

Chapinero

Radio:

3 km.

18. RADIO DE EVENTOS

Crear selector:

¿Qué tan lejos quieres salir?

Opciones:

1 km

3 km

5 km

10 km

Toda la ciudad

También puede existir slider.

Cuando cambie:

actualizar eventos.

Mostrar círculo visual alrededor del usuario.

19. PULSE RADAR

Crear una funcionalidad visual llamada:

Pulse Radar

Mostrar anillos:

0–1 km

1–3 km

3–5 km

Ejemplo:

1 km
3 experiencias

3 km
8 experiencias

5 km
14 experiencias

Debe generar sensación:

“Hay vida cerca de mí.”

20. FILTROS

Agregar chips:

Todos

☕ Café

🚶 Walk

💻 Cowork

🧘 Wellness

🌿 Outdoor

🏃 Sport

🎨 Experiences

👥 Pulse Pods

Filtros de tiempo:

Ahora

Hoy

Esta tarde

Esta noche

Mañana

Weekend

Ejemplo:

Wellness + Hoy + ≤3 km

Resultado:

“4 experiencias cerca.”

21. MARKERS

Utilizar Advanced Markers.

Cada evento debe tener iconografía propia.

Ejemplo:

☕ Cyan

🚶 Mint

💻 Violet

🧘 Pink

🌿 Green

👥 Pulse Pods especial

No utilizar pins genéricos iguales.

Los eventos recomendados:

✨ Para ti

Eventos próximos:

🔥 Empieza en 20 min

Casi llenos:

⚡ Queda 1 cupo

Pulse Pods:

👥 Tu Pod está aquí

22. CLUSTERING

Cuando existan muchos eventos:

agruparlos.

Ejemplo:

círculo:

12

Al hacer zoom:

mostrar markers individuales.

23. EVENT CARD

Al tocar marker abrir bottom sheet.

Ejemplo:

Coffee Connection ☕

Hoy · 4:00 PM

📍 Café aliado

🚶 750 m

⏱ 30 min

👥 3 / 5 personas

⚡ +80 Pulse Points

✨ 92% para ti

Social Battery:

🔋🔋 Medium

Mostrar avatares.

Badges:

✓ Lugar público

✓ Perfiles verificados

CTA:

Unirme

Cómo llegar

Opciones:

Guardar

Compartir

Reportar

24. GOOGLE MAPS ROUTES

Al hacer clic en:

Cómo llegar

No sacar inmediatamente al usuario.

Mostrar ruta dentro de PulseUp.

Origen:

ubicación actual.

Destino:

lugar del evento.

Utilizar Google Maps Routes Library.

Dibujar polyline.

25. MODOS DE TRANSPORTE

Mostrar:

🚶 Caminando

🚲 Bicicleta

🚗 Vehículo

🚌 Transporte público

Mostrar:

tiempo;

distancia.

Ejemplo:

🚶 12 min · 850 m

🚲 4 min · 850 m

🚗 5 min · 1.1 km

Cambiar visualmente ruta según selección.

26. MODO GUÍA

Pantalla:

Vamos a Coffee Connection ☕

Destino:

Coffee Lab

Inicio:

4:00 PM

Llegada estimada:

3:52 PM

Mostrar:

Mapa.

Ruta.

Usuario.

Destino.

Mostrar:

850 m restantes.

12 min caminando.

“Llegarás 8 minutos antes.”

CTA:

Abrir navegación en Google Maps

Si está disponible:

abrir app Google Maps.

Si no:

Google Maps web.

27. ESTADO DE PARTICIPANTES

Mientras va en camino:

mostrar:

Ana ✓ Confirmada

Mateo ✓ Confirmado

Sofía · En camino

Eli · Tú

No compartir ubicaciones exactas de otros usuarios.

Solo estados.

28. MATCHING SOCIAL

El usuario NO debe elegir personas con swipe.

Elige una experiencia.

Luego PulseUp forma un grupo.

Formato recomendado:

3–5 personas.

Mostrar:

Tu grupo

Ejemplo:

Eli

Ana
Product Designer

Mateo
Developer

Sofía
Marketing

Mostrar:

78% compatibilidad social

Texto:

“Todos trabajan remoto. Tres tienen intereses en tecnología y creatividad. Nadie se conoce todavía.”

29. VARIABLES DE MATCHING

Considerar:

zona;

idioma;

horarios;

Social Battery;

intereses;

tipo de actividad;

distancia;

presupuesto;

intensidad social;

modalidad laboral.

Nunca mostrar puntuaciones negativas.

30. ICEBREAKERS

Antes del encuentro:

🎙️ PulseUp Social Facilitator

Ejemplo:

“Antes de pedir el café: ¿cuál ha sido el lugar más raro desde el que han trabajado?”

Otros:

“¿Desde qué lugar del mundo trabajarías durante un mes?”

“¿Qué hábito mejoró tu trabajo remoto?”

“¿Qué cosa extrañas del trabajo presencial?”

“¿Qué canción representa tu día?”

31. CHAT DE MISIÓN

El chat solo aparece asociado a una misión.

Ejemplo:

Ana:
“Hola 👋 ya voy saliendo.”

Mateo:
“Estoy a 10 minutos.”

PulseUp:
“Recuerden que el encuentro es en un lugar público.”

Permitir enviar mensajes localmente.

No crear DMs aleatorios en el MVP.

32. CHECK-IN

Cuando llega:

Misión activa

Mostrar:

Eli ✓

Ana ✓

Mateo ✓

Sofía · En camino

CTA:

Hacer check-in

Puede usar:

QR

o código.

Ejemplo:

PULSE24

33. BONUS DE MISIÓN

Después del check-in:

🎯 Bonus

“Encuentren algo que los cuatro tengan en común.”

Otros:

“Pregunten cuál sería su semana de trabajo ideal.”

“Descubran un interés inesperado compartido.”

34. COMPLETAR MISIÓN

CTA:

Completar misión · +80 ⚡

Al completar:

mostrar microanimación.

+80 Pulse Points

Actualizar saldo.

35. PULSE POINTS

Sistema de puntos.

Ejemplos:

Pausa activa:
+20

Caminar:
+30

Walk con persona:
+60

Conocer persona:
+80

Repetir conexión:
+100

Crear evento:
+150

Completar balance semanal:
+200

36. GAMIFICACIÓN

Premiar:

consistencia;

movimiento;

conexiones;

participación;

variedad;

recurrencia;

comunidad.

NO premiar:

followers;

likes;

popularidad;

número de mensajes.

37. POST-MISSION

Después de la misión preguntar:

¿Te gustaría coincidir nuevamente?

Mostrar:

Ana

❤️ Sí

🙂 Me da igual

🚫 Prefiero no coincidir

Respuestas privadas.

No utilizar estrellas.

38. PULSE PODS

Si varias personas quieren coincidir:

mostrar:

⚡ Encontraste tu Pulse Pod

Ejemplo:

Eli

Ana

Mateo

Texto:

“Una amistad necesita más de una oportunidad.”

CTA:

Crear Pulse Pod

Después:

sugerir siguiente misión.

Ejemplo:

🌿 Sunday Park Reset

Domingo

9:30 AM

39. REWARDS

Crear pantalla:

Rewards

Mostrar:

780 Pulse Points

Nivel:

Nivel 3 · Connector

XP:

420 / 800

Racha:

12 días 🔥

40. SOCIAL REWARDS

Priorizar rewards sociales.

Ejemplos:

☕☕ 2×1 Coffee Pod
300 ⚡

💻👥 Cowork para 2
500 ⚡

🧘🤝 Yoga +1
650 ⚡

🥗👥 Remote Lunch
800 ⚡

🏋️ Gym Pass
400 ⚡

Al canjear:

restar puntos.

Mostrar:

Reward desbloqueado 🎁

41. PERFIL

Mostrar:

Avatar

Nombre

Nivel

Puntos

Racha

Misiones completadas

Conexiones

Pulse Pods

Rewards

42. CUATRO DIMENSIONES

Mostrar progreso:

🏃 Move

🤝 Connect

🌿 Recharge

🧠 Grow

Utilizar barras o rings.

43. CREAR EVENTO

Agregar botón:

+ Crear experiencia

Formulario:

Categoría

Nombre

Fecha

Hora

Duración

Número máximo de personas

Social Battery sugerida

Descripción

Pulse Points

44. ELEGIR LUGAR

Utilizar Google Places.

Buscar:

Café

Parque

Cowork

Gym

Restaurante

Biblioteca

Centro cultural

Seleccionar lugar público.

Guardar:

Google Place ID.

Coordenadas.

Dirección.

Nombre.

45. EVENTOS EN SUPABASE

Crear tabla:

events

Campos:

id

title

description

category

latitude

longitude

venue_id

start_time

end_time

max_participants

current_participants

pulse_points

social_battery

status

creator_id

visibility

created_at

46. TABLA VENUES

venues:

id

name

address

latitude

longitude

google_place_id

type

verified

photo_url

47. EVENT PARTICIPANTS

event_participants:

id

event_id

user_id

status

joined_at

Estados:

registered

confirmed

on_the_way

checked_in

completed

cancelled

48. SUPABASE REALTIME

Actualizar eventos en tiempo real.

Ejemplos:

Si alguien crea evento:

aparece en mapa.

Si alguien se une:

3 / 5

pasa a:

4 / 5.

Si está lleno:

Completo.

Si se cancela:

actualizar marker.

Utilizar Supabase Realtime.

49. PULSE ALERTS

Crear funcionalidad:

🔔 Pulse Alerts

Usuario configura:

“Avísame cuando aparezca algo cerca.”

Radio:

1 km

3 km

5 km

10 km

Categorías:

Coffee

Walk

Cowork

Wellness

Outdoor

Sports

Pulse Pods

Horario:

Mañana

Lunch

Tarde

Noche

Días:

Semana

Weekend

50. EVENT MATCH SCORE

Crear scoring simulado:

Distancia:
30 puntos

Categoría favorita:
25

Horario:
20

Social Battery:
15

Pulse Pod:
10

Total:

Si >= 70:

crear alerta.

51. EJEMPLO DE NOTIFICACIÓN

⚡ Nuevo plan cerca de ti

Coffee Connection ☕

Hoy · 4:30 PM

📍 850 m

👥 3 personas

⚡ +80 Pulse Points

✨ 92% para ti

Botones:

Ver evento

Unirme

52. NOTIFICACIONES MVP

Inicialmente:

notificaciones dentro de app;

toast;

badge;

Notification Center.

Después:

PWA;

Web Push;

mobile push.

Nunca solicitar permiso automáticamente.

Preguntar:

“¿Quieres que PulseUp te avise cuando aparezca algo interesante cerca?”

Activar

Ahora no

53. NOTIFICATION CENTER

Campana:

🔔

Eventos:

Nuevo plan cerca.

Tu misión comienza pronto.

Tu Pulse Pod creó actividad.

Alguien se unió.

Cambio de lugar.

Evento cancelado.

Reward nuevo.

54. EMPTY STATE

Si no existen eventos:

NO decir:

“No hay resultados.”

Mostrar:

Hoy está tranquilo por aquí 🌙

“Podemos ampliar tu radio o crear algo.”

CTA:

Ampliar a 5 km

✨ Break Me Out

Crear evento

También puede mostrar:

“4 remote workers están interesados en hacer algo hoy.”

Dato mock para MVP.

55. SEGURIDAD

Como PulseUp conecta desconocidos:

Trust & Safety debe estar visible.

Agregar:

✓ perfiles verificados;

✓ teléfono/email;

✓ lugares públicos;

✓ bloquear;

✓ reportar;

✓ chat moderable;

✓ check-in;

✓ grupos pequeños;

✓ ubicación aproximada.

56. BLOQUEO

Si un usuario bloquea a alguien:

no volver a emparejarlos.

Simular esta lógica en MVP.

57. PRIVACIDAD GEOGRÁFICA

Muy importante porque el público vive solo.

NO almacenar públicamente:

dirección de casa;

ubicación residencial exacta;

historial completo;

live location visible.

Guardar:

zona frecuente;

radio;

preferencias.

Ejemplo:

“Chapinero · 3 km”

58. PRIVACIDAD EMPRESARIAL

La empresa NO puede ver:

“Eli se siente sola.”

ubicación individual.

con quién estuvo.

mensajes.

estado emocional.

Sí puede ver:

participación;

misiones;

conexiones;

recurrencia;

categorías de actividades;

datos agregados.

59. DASHBOARD B2B

Crear vista demo.

Mostrar:

Participación:
76%

Misiones:
1.284

Conexiones:
438

Repetición:
42%

Move:
82%

Connect:
76%

Recharge:
64%

Grow:
69%

Mensaje:

Bienestar sin vigilancia.

60. MODELO DE NEGOCIO

B2C:

usuario gratuito + premium futuro.

B2B:

empresa paga acceso.

B2B2C:

empresa financia bienestar.

Partners:

cafés;

coworkings;

gimnasios;

restaurantes;

espacios culturales;

experiencias.

61. PARTNERS

Partners pueden:

crear beneficios;

patrocinar misión;

aparecer como lugar recomendado;

ofrecer rewards.

Ejemplo:

Coffee Lab:

10% PulseUp.

Cowork:

Day Pass.

Gym:

Clase gratis.

62. LANDING PÚBLICA

Crear landing visual.

Hero:

Trabajar remoto sin vivir aislado.

Subtítulo:

“PulseUp convierte pequeños momentos del día en movimiento, compañía y conexiones reales.”

CTA:

Probar PulseUp

63. PROBLEMA

Mostrar:

🧍 Aislamiento

🪑 Sedentarismo

💬 Falta de interacción espontánea

🏠 Casa = oficina permanente

🌫️ Fatiga mental

64. DIFERENCIAL

Mostrar:

No construimos otra red social.

Construimos una red que intenta sacarte de la pantalla.

Comparación:

NO FEED → acción.

NO SWIPE → experiencias.

NO LIKES → hábitos.

NO FOLLOWERS → conexiones reales.

NO DMs RANDOM → chat contextual.

65. JOURNEY VISUAL

Mostrar:

🏠 Trabajo solo

↓

🔋 Social Battery

↓

✨ IA

↓

🗺 Pulse Map

↓

🎯 Misión

↓

👥 Grupo

↓

🧭 Ruta

↓

📍 Check-in

↓

🤝 Experiencia

↓

⚡ Pulse Points

↓

❤️ Repetir

↓

👥 Pulse Pod

↓

🎁 Social Reward

66. FLUJO PRINCIPAL MVP

Prioridad absoluta:

Home

→ Qué necesitas hoy

→ Social Battery

→ tiempo

→ Pulse Map

→ IA recomienda evento

→ misión

→ aceptar

→ grupo

→ cómo llegar

→ ruta

→ chat

→ check-in

→ completar

→ puntos

→ repetir conexión

→ Pulse Pod

→ Reward

67. EXPERIENCIA DEL MAPA

El mapa debe sentirse:

vivo;

social;

dinámico;

gamificado;

seguro;

personalizado.

No parecer únicamente Google Maps con markers.

La sensación debe ser:

“No sabía que había tantas cosas pasando cerca de mí.”

68. MICROINTERACCIONES

Utilizar:

marker pulse;

pequeñas animaciones;

progress bars;

skeleton loading;

transitions;

toast;

confetti discreto;

haptic-like visual feedback;

highlight en misión recomendada.

69. DATA MOCK INICIAL

Usuario:

Eli.

Puntos:

Nivel:

XP:

420 / 800.

Racha:

Personas:

Ana
Product Designer.

Mateo
Developer.

Sofía
Marketing.

Laura
UX Researcher.

Daniel
Founder.

70. EVENTOS MOCK

Crear mínimo 10 eventos alrededor de una ciudad demo.

Ejemplos:

Coffee Connection

Walk & Talk

Silent Cowork

Park Reset

Yoga Break

Remote Lunch

AI Builders Coffee

Sunday Run

Designers Cowork

After Work Social

Cada evento debe tener:

latitud;

longitud;

fecha;

horario;

cupos;

Pulse Points;

categoría;

Social Battery.

71. CIUDAD DEMO

Para el MVP utilizar:

Bogotá, Colombia

Preferiblemente:

Chapinero;

Zona G;

Parque 93;

Usaquén;

Teusaquillo.

Usar lugares públicos reales si Google Places está conectado.

Si no hay API key todavía:

utilizar datos mock claramente separados de la arquitectura final.

72. PRIORIDAD TÉCNICA

Primero:

hacer experiencia funcional.

No bloquear construcción por backend.

Si Supabase aún no está configurado:

usar mock data.

Si Maps API aún no está configurada:

crear mapa mock visual.

Pero dejar componentes preparados.

73. COMPONENTES

Crear componentes reutilizables:

PulseMap

EventMarker

EventCard

EventBottomSheet

PulseRadar

RouteViewer

TransportSelector

MissionCard

SocialBattery

NeedSelector

PulsePoints

RewardCard

PulsePodCard

UserAvatar

CheckIn

NotificationCenter

EventFilters

74. ARQUITECTURA

Organizar carpetas:

components/

features/

maps/

missions/

rewards/

social/

notifications/

lib/

services/

types/

mock/

75. EXPERIENCIA DE DEMO

El MVP será presentado en una hackathon.

Debe poder demostrarse en 3 minutos.

Flujo demo recomendado:

Abrir PulseUp.

Mostrar:

“Estoy trabajando solo en casa.”

Seleccionar:

“Ver personas.”

Social Battery:

Medium.

30 min.

IA recomienda:

Coffee Connection.

Abrir Pulse Map.

Mostrar varios eventos cerca.

Seleccionar Coffee Connection.

Unirse.

Mostrar grupo.

Mostrar ruta caminando.

Check-in.

Completar.

+80 Pulse Points.

Elegir personas para repetir.

Crear Pulse Pod.

Canjear 2×1 café.

76. CRITERIOS DE ÉXITO

Después de usar PulseUp 2 minutos, el usuario debe entender:

PulseUp es para personas que trabajan remoto y viven solas.

No es una dating app.

No necesita buscar manualmente personas.

La app entiende qué necesita hoy.

Social Battery personaliza la intensidad.

El mapa muestra vida social cerca.

Puede saber cómo llegar.

Puede conocer grupos pequeños.

Los encuentros ocurren en lugares públicos.

Gana Pulse Points.

Puede volver a ver personas compatibles.

Puede formar Pulse Pods.

Los rewards incentivan nuevas experiencias.

PulseUp quiere sacarlo de la pantalla.

77. PITCH DEL PRODUCTO

Utilizar como mensaje principal:

“PulseUp es el copiloto social de las personas que trabajan remoto y viven solas.”

“Entiende cuándo necesitas moverte, recargar, trabajar acompañado o ver personas y convierte ese momento en una misión real con un pequeño grupo compatible cerca de ti.”

“Pulse Map te muestra lo que está pasando alrededor, te ayuda a llegar y te avisa cuando aparece una experiencia relevante.”

“Al completar experiencias ganas Pulse Points que puedes usar en beneficios sociales como cafés, coworking, bienestar y actividades.”

78. REGLA FINAL

No crear una app llena de funcionalidades desconectadas.

Todo debe girar alrededor del loop:

HOY NECESITO ALGO

↓

PULSEUP ENCUENTRA UNA EXPERIENCIA

↓

SALGO DE CASA

↓

CONECTO CON PERSONAS

↓

GANO PUNTOS

↓

VUELVO A COINCIDIR

↓

CONSTRUYO COMUNIDAD

Construye primero este loop perfectamente.

Después agrega funcionalidades secundarias.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://connect-out-loud.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/5ece67bb-212c-4823-a0de-61563cb13f24).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
