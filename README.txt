ONE PAGE - SERVICIOS IT EMPRESAS

Marca: se deja como texto editable "Nombre de empresa".
Isotipo: assets/isotipo.svg (terminal + nodos, azul/cian/índigo).
Dominio: https://serviciotecnicoinformaticomadrid.com.es/
WhatsApp: +34 649 97 01 28
Teléfono: +34 914 46 85 03

Enfoque: mantenimiento informático, desarrollo de software y automatización para empresas en España.
Redacción: problema de negocio -> coste en tiempo -> solución -> confianza -> CTA.

Incluye Google Business, YouTube, Cal.com, formulario SMTP y chatbot n8n con fix consolidado.
Variables Vercel: SMTP_HOST, SMTP_PORT=465, SMTP_SECURE=true, SMTP_USER, SMTP_PASS, CONTACT_EMAIL.
El correo no aparece visible en la web.
No se añadió Google Analytics porque no se proporcionó un ID.

REVISIÓN ADICIONAL (checklist unificado de la familia, a petición del cliente):
- BUG REAL — enlace de Cal.com desactualizado. Actualizado a
  https://cal.com/kelatos/30min?embed=true&theme=light&attendeePhoneNumber=%2B34&overlayCalendar=true.
- Verificado: el correo soporte@kelatos.com no aparece visible.
- No se ha tocado el texto de WhatsApp ("¡Hola Kelatos", sin marca):
  esta es una plantilla deliberadamente sin marcar (ver nota de
  arriba, "Nombre de empresa" es texto editable), así que no
  corresponde inventar un nombre de marca aquí. Aplicar el nombre
  real de marca cuando esta plantilla se reutilice para un cliente
  concreto.
- BUG REAL — no existía ningún botón de menú en móvil/tablet
  (.links{display:none} a partir de 920px, sin alternativa), así que
  la navegación desaparecía por completo por debajo de ese ancho.
  Añadido botón .menu-btn + desplegable #mobileMenu con los mismos
  enlaces, y su script de cierre al pulsar un enlace.
- Verificado: sin iconos ni imágenes con proporciones fijas
  incorrectas.
- BUG REAL — el H1 en móvil estaba en 40px. Corregido a 48px.
- BUG REAL — botones del hero (.cta) con border-radius de 15px y sin
  estado hover. Aumentado a border-radius:999px; añadido
  filter:brightness(.88) en wa/phone (ambos de color sólido, verde y
  blanco respectivamente) y relleno blanco + texto oscuro en el botón
  "Agenda una reunión" (.meet, estilo contorno fantasma sobre el
  hero oscuro) al pasar el ratón.
- No aplica la franja de aviso de servicio técnico independiente:
  agencia de servicios IT/mantenimiento para empresas, mismo criterio
  que InformaticoChamberi (sin enfoque de reparación de equipos de
  marca concreta).
- Verificado: este repo no usa el patrón de franja de insignias bajo
  el H1 (familia Dyson); no aplica la reubicación.

⚠️ AVISO — COLISIÓN DE DOMINIO (no resuelta, no tocada):
El dominio indicado arriba (serviciotecnicoinformaticomadrid.com.es)
es, confirmado por el cliente, el dominio real de otro repositorio de
la familia (InformaticoChamberi). Si esta plantilla llega a
desplegarse en vivo para un cliente real, hay que asignarle su propio
dominio distinto antes de publicarla, y actualizar canonical/og:url/
sitemap.xml/robots.txt en consecuencia.
