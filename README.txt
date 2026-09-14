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

BANNER DE COOKIES Y ENLACE DE PRIVACIDAD (a petición del cliente):
- BUG REAL — no existía ningún banner de cookies en todo el
  repositorio. Añadido el estándar de la familia (Aceptar / Rechazar
  / Política de privacidad → https://kelatos.com/privacy-policy/),
  con recuerdo en localStorage y diseño apilado a ancho completo en
  móvil.
- BUG REAL — la casilla "Acepto la política de privacidad." del
  formulario de contacto era texto plano, sin ningún enlace. Añadido
  el enlace estándar de la familia a
  https://kelatos.com/privacy-policy/, resaltado en azul y subrayado
  (clase .privacy-link).

REVISIÓN COMPLETA DE INDICACIONES PENDIENTES (a petición del cliente):
Repaso contra el checklist unificado completo de la familia. Ya
estaban correctos: Cal.com con parámetros nuevos, correo de soporte
no visible, WhatsApp con marca (PymeTech), cierre del menú móvil,
header fijo al hacer scroll, sin etiqueta rotada tipo hero-chip, sin
patrón de franja de insignias (familia Dyson), banner de cookies y
enlace de privacidad (ya corregidos en la pasada anterior), sitemap.xml
y robots.txt correctos. Se encontraron y corrigieron dos pendientes:
- BUG REAL — la fila "Horario" no incluía "Sábados, domingos y días
  festivos estamos cerrados" (regla estándar de toda la familia).
  Añadido.
- BUG REAL — el texto decorativo gigante ".art:before" ("MENOS HORAS
  PERDIDAS", 64px) no tenía ninguna reducción de tamaño en
  tablet/móvil, mismo patrón ya corregido en decenas de repos de la
  familia. Añadida reducción (40px en ≤920px, 28px en ≤600px).
- Sin Google Analytics: sigue sin proporcionarse un ID propio para
  PymeTech (no aplica, no es un bug).

REVISIÓN DE DISEÑO (a petición del cliente, "algo más profesional"):
- Tipografía: añadida "Sora" (Google Fonts) para titulares (h1, h2,
  h3, marca, botón de envío) manteniendo Inter para el cuerpo de
  texto — antes todo usaba Inter, sin jerarquía tipográfica distinta
  entre titular y párrafo.
- Eyebrow del hero: sustituido el texto plano por una píldora con
  punto de acento, patrón habitual en landing pages profesionales.
- Tarjetas (.problem, .service, .plan): añadido efecto hover sutil
  (elevación + sombra) para que se perciban interactivas.
- Servicios: añadido un icono propio a cada una de las 6 tarjetas
  (llave inglesa, código, rayo, escudo, nube, tendencia), en vez de
  solo una etiqueta de texto — ayuda a diferenciar cada área de un
  vistazo.
- Bloque decorativo "Automatizar no es poner IA por poner IA": el
  texto gigante con contorno ("MENOS HORAS PERDIDAS") se ha
  sustituido por una tarjeta flotante con icono y mensaje concreto
  ("Menos tareas manuales"), un tratamiento más contenido y propio de
  diseño profesional que el texto de fondo tipo plantilla.
- Confianza (Google/YouTube): añadido un icono a cada tarjeta y
  degradado sutil en el fondo en vez de color plano.
- Plan "Empresa": marcado como destacado (borde de color + etiqueta
  "Más elegido"), patrón estándar en tablas de precios para guiar la
  elección.
- Pasos del proceso: números de tarjeta llevados a la tipografía de
  titular, para que combinen con el resto de la jerarquía.
- Formulario: estados de foco visibles en campos e inputs (accesible
  por teclado), sombra sutil al enfocar.
- Accesibilidad: añadido contorno de foco visible (:focus-visible) en
  enlaces, botones y campos; respeta prefers-reduced-motion.
- Refinados espaciados, radios de borde y sombras para que se sientan
  consistentes en toda la página, en vez de varían de una sección a
  otra.

IMAGEN DE FONDO DEL HERO (a petición del cliente, con imagen de referencia):
- Añadida assets/images/pymetech-fondo-isometrico-web.webp (subida
  por el cliente vía GitHub) como fondo decorativo del hero.
- Escritorio (>920px): la ilustración se posiciona a la derecha del
  hero, con background-size:contain (sin deformarla, respeta el
  aspect-ratio real 1850x850) y un degradado en los bordes
  (mask-image) para que se funda con el fondo oscuro en vez de
  cortarse en seco. Tiene una animación de flotación muy sutil
  (translateY ±12px, 7s, ease-in-out) usando solo transform (GPU,
  sin repintar), respetando prefers-reduced-motion (ya definido
  globalmente en el sitio). Se posiciona por debajo del texto y de la
  caja de información (z-index) para no interferir con la legibilidad.
- Móvil/tablet (≤920px): NO se muestra la ilustración completa (sería
  pesada visualmente y competiría con el texto en pantallas
  pequeñas). En su lugar, la misma imagen se usa como una textura de
  fondo muy sutil a pantalla completa (opacity:.14, sin animación),
  igual que pidió el cliente ("solo iría un patrón basado en la
  imagen de fondo").
- Rendimiento: una sola imagen de 47.7 KB, sin JavaScript añadido,
  animación limitada a transform (compositada por GPU, no afecta al
  layout/paint), desactivada por completo en móvil.
