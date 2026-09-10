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

CORRECCIÓN DE DOMINIO (confirmado por el cliente):
- BUG REAL — el dominio real es mantenimientoinformaticopymetetuan.es
  (confirmado por el cliente). El anterior, serviciotecnicoinformaticomadrid.com.es,
  resultó pertenecer en realidad a InformaticoChamberi, otro repositorio de
  la familia. Corregido en canonical, JSON-LD (campo "url"), sitemap.xml y
  robots.txt.
- Verificado en vivo: mantenimientoinformaticopymetetuan.es actualmente
  sirve un sitio WordPress ajeno a este despliegue de Vercel (cabeceras
  PHP/wp-json/wp-content), con el título "PymeTech | Mantenimiento
  Informático Tetuán" — probablemente el sitio antiguo que hay que
  sustituir en el panel de dominios por este despliegue; eso no se puede
  hacer desde el código. De paso revela el nombre de marca real
  ("PymeTech") por si se decide dejar de usar esta copia como plantilla
  genérica y personalizarla para ese negocio concreto — pendiente de
  confirmación del cliente antes de tocar el texto "Nombre de empresa" y
  el mensaje de WhatsApp.

PERSONALIZACIÓN CON LA MARCA REAL (a petición del cliente — deja de ser plantilla genérica):
- "Nombre de empresa" → "PymeTech" en cabecera, pie de página y
  JSON-LD (campo "name").
- Mensaje de WhatsApp: "¡Hola Kelatos" → "¡Hola PymeTech" en el CTA
  del hero y en el botón flotante.
- Title y meta description reescritos incluyendo la marca: "PymeTech
  | Mantenimiento Informático y Software para Empresas en Madrid".
- Añadidos meta robots y etiquetas og:title/og:description/og:url/
  og:type (no existía ninguna); usan el título/descripción nuevos y
  el dominio ya corregido.
- No se ha añadido Google Analytics: sigue sin proporcionarse un ID
  propio para PymeTech.

AJUSTES DE HERO (a petición del cliente, con captura de pantalla):
- H1 reducido de 20 palabras a 7: "Menos problemas técnicos. Más
  tiempo para tu empresa."
- Quitado el párrafo largo bajo el H1 (.hero-copy, "Equipos que no
  responden, procesos manuales...") y la fila de píldoras (.points,
  "Mantenimiento informático · Desarrollo de software ·
  Automatizaciones · Soporte empresas") — ambos marcados para
  eliminar en la captura.
- Botones del hero (.ctas): cambiados de dos columnas a una sola
  columna (uno debajo del otro), y añadido un icono a cada uno:
  WhatsApp (bocadillo estándar de la familia), teléfono y un icono de
  calendario para "Agenda una reunión".
- Icono de WhatsApp flotante mejorado: sustituido el texto "WA" por
  el mismo icono SVG de bocadillo usado en el resto de la familia.

AJUSTES DE LA CAJA DE INFORMACIÓN Y H1 (a petición del cliente, con captura de pantalla):
- Quitadas de la caja de información: la fila "Dirección" (C.
  Joaquín María López, 26 — dirección compartida de la familia, no
  específica de este negocio), la fila "Ámbito" y el bloque
  "Referencia" (Metro/Aparcamiento) — las tres marcadas para eliminar
  en la captura.
- Añadida en su lugar una fila "Zona": Tetuán, Madrid (según el
  propio dominio/nombre del repositorio, mantenimientoinformaticopymetetuan.es).
- JSON-LD actualizado en consecuencia: quitado el streetAddress/
  postalCode de la dirección compartida; areaServed cambiado de "ES"
  a "Tetuán, Madrid".
- H1 aumentado un 40%: clamp(40-58px) → clamp(56-81px) en escritorio.
  El tamaño en móvil se mantiene en 48px, el estándar unificado de
  toda la familia (no se ha tocado, para no romper esa consistencia).
