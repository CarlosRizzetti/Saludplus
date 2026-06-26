# PROMPT MAESTRO – Diseño UX/UI para Centro de Salud "SaludPlus"

## Rol

Actúa como un **Senior UX/UI Designer**, especialista en experiencia de usuario, arquitectura de información, diseño de interfaces médicas y accesibilidad.

Debes diseñar el prototipo completo de una plataforma web para un **Centro de Salud privado multiespecialidad**, cuya única finalidad es permitir que un paciente pueda reservar un turno médico de la forma más rápida, clara y confiable posible.

Este proyecto corresponde a una materia universitaria llamada **Visualización de Interfaces**, por lo que todas las decisiones de diseño deben estar justificadas desde la teoría.

No desarrollar código.

No implementar funcionalidades.

Diseñar únicamente las interfaces en html y css.

---

# Contexto del producto

El sistema pertenece a un único Centro de Salud.

No es un marketplace de médicos.

No pertenece a una prepaga.

No es un portal hospitalario complejo.

Su principal ventaja competitiva consiste en que el usuario puede resolver la reserva de un turno en muy pocos pasos, sin llamadas telefónicas ni trámites presenciales.

Todo el diseño debe transmitir simplicidad, organización y confianza.

---

# Público objetivo

Diseñar pensando principalmente en personas entre 25 y 65 años.

Usuarios acostumbrados a utilizar:

* Home Banking
* Mercado Libre
* Aplicaciones bancarias
* Redes sociales
* Compras online

No diseñar para usuarios expertos.

Toda la navegación debe poder comprenderse intuitivamente.

---

# Objetivo principal de UX

El usuario debe poder reservar un turno en menos de un minuto.

Debe sentirse acompañado durante todo el recorrido.

Nunca debe preguntarse:

"¿Qué hago ahora?"

La interfaz debe guiarlo permanentemente.

---

# Mobile First

Diseñar primero la versión para Smartphone.

Luego adaptar el mismo diseño a Desktop.

No crear dos diseños distintos.

Debe mantenerse la misma identidad visual.

---

# Sistema de Diseño

## Paleta

Color primario

Azul (#1976D2)

Color secundario

Verde (#4CAF50)

Fondo

Blanco

Color de apoyo

Celeste muy claro

Errores

Rojo suave

Éxito

Verde

Advertencias

Amarillo suave

---

## Tipografía

Sans Serif moderna.

Ejemplos:

* Inter
* Poppins
* Roboto

---

## Componentes reutilizables

Crear un pequeño Design System.

Debe reutilizar:

* Botones
* Cards
* Inputs
* Dropdowns
* Calendario
* Navbar
* Footer
* Breadcrumb
* Modales
* Alertas
* Chips
* Badges
* Tarjetas de médicos
* Tarjetas de especialidades

Todos los componentes deben mantener consistencia visual.

---

# Layout

Todas las pantallas deben compartir exactamente la misma estructura.

## Header

Logo del Centro de Salud.

Navbar:

* Inicio
* Pedir Turno
* Especialidades
* Profesionales
* Estudios
* Mis Turnos
* Mi Perfil
* Contacto

A la derecha:

* Buscar
* Avatar del usuario
* Notificaciones

Debe existir un botón destacado:

"Solicitar Turno"

Ese debe ser el principal Call To Action de todo el sitio.

---

## Footer

Debe incluir:

Dirección

Mapa

WhatsApp

Email

Teléfono

Horarios

Preguntas Frecuentes

Redes Sociales

Términos y Condiciones

Política de privacidad

---

# Arquitectura de Información

Diseñar un flujo lógico donde cada pantalla pueda alcanzarse desde la navegación.

No generar páginas aisladas.

---

# Flujo completo

Diseñar las siguientes vistas.

## 1

Splash Screen

Logo

Slogan

Botón Ingresar

---

## 2

Login

Usuario

Contraseña

Recordarme

Crear cuenta

Recuperar contraseña

---

## 3

Registro

Formulario completo.

---

## 4

Recuperar contraseña

Email

Enviar

---

## 5

Home

Banner principal.

Buscador.

Especialidades destacadas.

Consejos de salud.

Noticias.

CTA principal.

---

## 6

Especialidades

Grid de especialidades.

---

## 7

Detalle Especialidad

Información.

Médicos disponibles.

Botón Pedir Turno.

---

## 8

Profesionales

Cards.

Foto.

Especialidad.

Calificación.

Experiencia.

---

## 9

Perfil Profesional

Currículum.

Disponibilidad.

Opiniones.

Botón Solicitar Turno.

---

## 10

Elegir Fecha

Calendario grande.

Disponibilidad visual.

---

## 11

Elegir Horario

Lista de horarios.

Franjas.

Disponibles y ocupados.

---

## 12

Confirmar Turno

Resumen.

Paciente.

Profesional.

Especialidad.

Fecha.

Hora.

Botón Confirmar.

---

## 13

Turno Confirmado

Mensaje positivo.

Número de turno.

Código QR.

Descargar comprobante.

Agregar al calendario.

---

## 14

Mis Turnos

Próximos.

Finalizados.

Cancelar.

Reprogramar.

---

## 15

Detalle del Turno

Información completa.

Indicaciones.

Ubicación.

Preparación.

---

## 16

Estudios Médicos

Listado.

Filtros.

---

## 17

Detalle Estudio

Preparación.

Duración.

Preguntas frecuentes.

---

## 18

Perfil del Paciente

Datos.

Obra social.

Historial.

Editar.

---

## 19

Contacto

Formulario.

Mapa.

FAQ.

---

## 20

Error 404

Ilustración amigable.

Botón Volver al Inicio.

---

# Metáforas de Interfaz

Utilizar metáforas ampliamente reconocidas:

📅 Calendario → Selección de fecha.

🕒 Reloj → Horarios.

👨‍⚕️ Tarjetas → Profesionales.

📁 Carpeta → Estudios.

👤 Avatar → Perfil.

🔔 Campana → Notificaciones.

🔍 Lupa → Buscar.

❤️ Cruz médica → Salud.

Estas metáforas deben permitir comprender el sistema sin necesidad de explicaciones.

---

# Visualización

Aplicar:

* Jerarquía visual.
* Contraste.
* Proximidad.
* Alineación.
* Repetición.
* Espacios en blanco.
* Escaneo visual en "F".
* Botones principales claramente diferenciados.

---

# Mapeado

Cada acción debe producir un resultado evidente.

Ejemplo:

Seleccionar especialidad → aparecen únicamente los médicos correspondientes.

Seleccionar médico → aparecen únicamente sus horarios disponibles.

La relación entre acción y resultado debe ser inmediata.

---

# Diseño Emocional

El usuario debe sentir:

✔ tranquilidad

✔ confianza

✔ rapidez

✔ organización

✔ seguridad

Nunca ansiedad.

Nunca incertidumbre.

---

# Heurísticas de Nielsen

Aplicar explícitamente las diez heurísticas.

Indicar en qué parte del diseño aparece cada una.

---

# Semiótica Cognitiva (Carlos Scolari)

Justificar el uso de:

* signos
* iconos
* símbolos
* convenciones
* metáforas
* affordances
* consistencia comunicacional
* carga cognitiva

Explicar cómo estos elementos ayudan al usuario a comprender el sistema sin necesidad de instrucciones.

---

# Accesibilidad

Considerar:

* Alto contraste.
* Tipografía legible.
* Botones grandes.
* Estados hover y focus.
* Navegación clara.
* Buen tamaño táctil para dispositivos móviles.

---

# Resultado esperado

Generar un prototipo moderno, elegante y profesional, con un nivel visual similar al de una clínica privada de alta calidad.

Cada pantalla debe mantener la misma identidad visual, los mismos componentes y un lenguaje gráfico consistente.

Al finalizar, explicar brevemente las decisiones de UX/UI tomadas en cada vista y cómo se relacionan con:

* Semiótica Cognitiva.
* Metáforas de Interfaz.
* Visualización.
* Mapeado.
* Diseño Emocional.
* Heurísticas de Nielsen.
