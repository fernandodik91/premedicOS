CONTEXTO MAESTRO — Proyecto VIVANTE

Documento de referencia para todas las conversaciones con Claude sobre este proyecto.
Última actualización: Junio 2026 — v6.
Subir como archivo adjunto al proyecto en Claude.ai. Reemplaza al anterior (v5).
Cambios v6 vs. v5: estructura de Meta COMPLETADA (cuenta publicitaria + método de pago + Pixel en landing + verificación de dominio + evento Lead + test end-to-end) → Bloque A cerrado por completo; estado general avanzado a listo para encender la primera campaña (ya no hay bloqueantes técnicos); hero de la landing en transición de video a fondo WebGL interactivo (gradiente teal reactivo al mouse/scroll, three.js cargado vía CDN, sin migrar a React — sigue siendo HTML estático).
Cambios v5 vs. v4: Meta BM/portfolio + página de Facebook + Instagram ya creados (Bloque A pasos 1-4 cerrados; falta cuenta publicitaria + pago + Pixel + verificación + evento Lead + test); aclarado que hoy hay UNA sola landing en vivante.ar (no existe /empleados); horarios de atención actualizados a L-V 9-19 y Sáb 9-13; solo se usa vivante.ar (vivante.com.ar fuera de uso); decisión sobre creativos revisada: primer ad set en Canva y luego se incorpora video IA + character + voz IA (con nota del CTO sobre disclosure y A/B); registrado que crear campañas directo desde Claude vía connector NO es posible hoy (connectors Meta son solo lectura) → flujo = Claude redacta spec, founder valida en Ads Manager; Sección 12 reformulada de "Prohibido" a "Guía de foco" (guardarraíles, no muros).
Cambios v4 vs. v3: Bloque A casi cerrado (acuerdo entre socios firmado, número de WhatsApp activo, vivante.ar resolviendo vía Cloudflare → Netlify); landing avanzada a v14 (publicada y viva, retoques menores pendientes); Cloudflare y Resend incorporados al stack real (DNS + mail corporativo hola@vivante.ar); decisión loggeada sobre método de creativos para mes 1 (Canva + CapCut + Claude, sin video IA / character / voz IA); único bloqueante restante de Bloque A = estructura Meta; riesgo "conflicto entre socios" actualizado a resuelto.
Cambios v3 vs. v2: actualización institucional PreMedic (22 años, no 21), Premedic Medical Center Mendoza incorporado como diferencial real, prensa externa (Clarín, IProfesional) sumada como prueba de respaldo, cobertura 100% en internación/UCI/UCO sumada como diferencial concreto, matiz crítico sobre copagos en Plan por Aportes (consultas sin copago / prácticas sí pueden tener copago), reformulación del bloque "servicios incluidos que comunicamos pero no son diferenciales", lista de red mendocina por jerarquía de planes, estado actualizado (landing v10 creada, próxima v11).


0. CÓMO USAR ESTE DOCUMENTO
Cuando abras un chat nuevo con Claude:

Adjuntá este archivo al proyecto.
Empezá con un briefing corto (3-5 líneas):

En qué bloque del roadmap estás.
Qué tarea concreta querés resolver hoy.
Pedile a Claude que lea el contexto antes de responder.



Template de briefing:

Estoy trabajando en VIVANTE, fase 1.5 entrando a pre-lanzamiento de ads (landing única v14 viva en vivante.ar, segmento empleados; acuerdo de socios firmado, WhatsApp activo, Meta BM + FB + IG creados; falta cuenta publicitaria + Pixel + verificación de dominio + evento Lead + test). Hoy necesito resolver: [tarea concreta]. Por favor revisá el contexto maestro antes de responder.


1. QUIÉNES SOMOS Y QUÉ HACEMOS
VIVANTE es una comercializadora independiente de medicina prepaga enfocada en captar y derivar afiliados a PreMedic Medicina Privada en el Gran Mendoza.

3 socios (ver Sección 6 para roles detallados).
Marca propia VIVANTE. Es el activo estratégico de largo plazo: dominio, funnels, base de leads, redes, reputación.
Modelo: partner externo / lead-gen as a service bajo marca propia. VIVANTE genera demanda calificada → atiende, califica y cierra por WhatsApp → la afiliación final la procesa Nexio (comercializadora oficial de PreMedic) con código NX27.
Posicionamiento público Fase 1: "canal oficial de PreMedic en Mendoza". A futuro, cuando VIVANTE tenga reconocimiento propio, puede evolucionar hacia "asesor independiente en medicina prepaga".

Activo clave: uno de los socios (Juan Manuel) es Gerente Comercial de Nexio. Acceso directo a reportes, Intranet y decisores de la comercializadora.
Dominios:

vivante.ar → único dominio en uso. Apuntando (Cloudflare → Netlify).
vivante.com.ar → fuera de uso por el momento. Solo se usa vivante.ar.

No somos PreMedic. No somos Nexio. Somos VIVANTE.

2. CONDICIONES COMERCIALES CON NEXIO

Código vendedor: NX27 (compartido, sin sub-código por decisión propia).
Comisión: se paga prácticamente al instante una vez completada la afiliación.
Clawback: si el afiliado se da de baja antes de 4 meses, devolvemos la comisión completa.
Marca: podemos usar marca PreMedic y material oficial.
Exclusividad: ninguna. Hay otros NX en paralelo.
Reportes: acceso completo vía Juan Manuel + Intranet Nexio.

Implicancia financiera clave: flujo de caja bueno, pero el clawback obliga a calificar duro. El KPI que importa NO es "afiliaciones del mes" — es afiliaciones netas que persisten a 4 meses.

3. PÚBLICOS Y SEGMENTACIÓN
Foco geográfico definitivo (primeros 6 meses)
Gran Mendoza únicamente: Mendoza Capital, Godoy Cruz, Guaymallén, Luján de Cuyo, Maipú. Radio ~30km desde el centro.
Fuera de scope (regla dura): cero campañas fuera de Gran Mendoza. Reevaluación recién en el mes 7 según performance.
Segmentos (cada uno tendrá su campaña; landings por segmento son a futuro)

Hoy hay UNA sola landing (vivante.ar), enfocada en empleados, con mención breve de los otros planes. Las landings dedicadas por segmento son objetivo de fases posteriores (ver Sección 7).

PrioridadSegmentoPlan principalEstado1 (ACTIVO)Empleados en relación de dependencia (~1-1.2M ARS/mes)Plan por Aportes ($0 de bolsillo)Landing única v14 viva (empleados-first + mención breve de otros planes)2MonotributistasPlan 200 directoMes 2-33Familias jóvenes con hijosPlan 300 (MEDIKIDS + Hospital Español)Mes 2-34Personas sin cobertura médicaPlan 200 directoMes 3+
Mapa Segmento ↔ Promo aplicable (no equivocarse acá)
SegmentoPlanPromo aplicableRazónEmpleadosPor AportesNINGUNAYa es $0, no hay sobre qué descontarMonotributistas200 directoMZA25 (25% off permanente) + descuento monotributoPagan de bolsilloFamilias300MZA25Pagan de bolsilloSin cobertura200 directoMZA25Pagan de bolsillo
Regla: MZA25 NUNCA en copy del segmento empleados. Confunde el mensaje principal.

4. DIFERENCIALES, RESPALDO E INFORMACIÓN A COMUNICAR
Esta sección distingue 3 niveles de mensaje según cómo se usan en landing, ads y WhatsApp:
4.1 Diferenciales REALES (lo que SÍ usamos en hero, headlines y ads)
Son los argumentos que mueven la decisión y que no todo el mercado puede igualar:

Plan por Aportes a costo $0 para empleados con obra social (segmento prioritario).
25% off permanente con MZA25 (solo en segmentos que pagan).
Sin copagos en consultas de clínica médica, ginecología y pediatría. ⚠️ Ver matiz crítico en 4.4.
Red real reconocible en Mendoza: Hospital Español, Clínica de Cuyo, Sociedad Española, Hospital Santa Isabel de Hungría, MEDIKIDS, Centro Médico La Barraca, Clínica Francesa, Hospital Universitario. Ver lista completa por plan en 4.5.
PreMedic Medical Center Mendoza — Av. Colón 102, Local 2. Centro propio con +30 especialidades médicas + odontología propia (Smile Group). Es físico, mendocino, verificable, y muy pocas prepagas tienen centro propio acá. Diferencial fuerte.
Cobertura 100% en internación, terapia intensiva y UCO. Concreto, sin letra chica, sin coseguros.
22 años de trayectoria de PreMedic + llegada nueva a Mendoza.

4.2 Pruebas de respaldo externo (no diferencial, pero refuerza credibilidad)
Va en bloques de "pruebas" o "por qué confiar", no en hero:

Reconocimiento en prensa nacional: Clarín e IProfesional listan a PreMedic entre las prepagas más accesibles del país (entre las top 3-5). Validación externa, no autopromoción.
+5000 prestadores a nivel nacional (útil mencionar como respaldo institucional, no como argumento principal porque al empleado mendocino no le mueve un prestador en Misiones).

4.3 Información importante que comunicamos (no son diferenciales, pero el cliente debe saber que lo incluye)
Estos servicios no son diferenciales (la competencia también los tiene), pero son información valiosa que el cliente necesita conocer para entender el alcance del producto. Decisión: comunicarlos con peso visual claro, pero nunca en hero, headlines de ads ni promesa madre.
Dónde sí van:

Bloque "Todo lo que incluye, sin costo adicional" en landing (con íconos, abajo del flow principal).
FAQ desplegable.
Materiales que se mandan por WhatsApp después del primer contacto.
Posts educativos en redes.

Servicios a comunicar:

Médico online 24/7 (Llamando al Doctor): videoconsultas con Clínica Médica, Ginecología, Pediatría + nuevo Médico IA.
App PreMedic Móvil: credencial digital + token, cartilla con geolocalización, autorización de órdenes online, factura online.
App PreMedic Bienestar: +14 especialidades en videoconsulta (psicología, asesoría deportiva, nutrición, financiera/legal, embarazo, sueño, salud bucal, veterinaria).
ECCO Emergencias 24/7 (0810-888-3226).
Cardinal Assistance (asistencia al viajero nacional + países limítrofes).
CARE MD: centros de vacunación gratis para todos los planes.
NUME: anticonceptivos a domicilio.
AMAR Mascota: veterinaria a domicilio (Buenos Aires) + videoconsulta nacional.
Plan Materno Infantil: asesorías virtuales embarazo + primer año, regalo nacimiento, canal exclusivo.
Red de ópticas (Hipervisión + 10 ópticas más) con descuentos.
Farmacias con hasta 40% off en venta bajo receta (Farmacity + red).
Turnos digitales vía App, WhatsApp MATI, web.

4.4 Matiz crítico sobre copagos (no equivocarse en copy)
⚠️ Diferencia entre planes — usar las palabras exactas:

Plan por Aportes (empleados): sin copago en consultas de clínica médica, ginecología y pediatría. Las prácticas (estudios, ecografías, laboratorio, etc.) sí pueden tener copago. En copy: usar siempre "sin copagos en consultas", nunca "sin copagos" a secas.
Planes 200 y PMO: copagos moderados según prestación.
Planes 300 y 400: sin copagos.

Razón: prometer "sin copagos" a secas en segmento empleados → afiliado descubre copago en su primera ecografía → reclamo → baja antes de 4 meses → clawback. La precisión protege la economía.
4.5 Red mendocina por jerarquía de plan (referencia para copy y materiales)
Top tier — Planes 300 y 400 (los nombres que pesan en Mendoza):

Hospital Español de Mendoza (Av. San Martín 965, Godoy Cruz)
Clínica de Cuyo (Plan 400 exclusivo — Luján de Cuyo)
CDC Centro Médico (Boedo, Primitivo, San Martín — Plan 400)
Clínica Arizu
Clínica Francesa
Hospital Universitario (Paso de los Andes 3051)
Centro Médico La Barraca (Las Cañas 1833, Guaymallén)
MEDIKIDS (medicina infantil, Plan 300)
Centro Médico Chacras (Italia 5795, Luján de Cuyo)
Centro Médico Cervantes
Terradonna Clínica

Base — PMO, Plan 200 y Plan por Aportes:

Hospital Santa Isabel de Hungría (Pedro del Castillo 2854, Guaymallén)
Sociedad Española de Socorros Mutuos
Attimo Salud (Hipólito Yrigoyen 52, Godoy Cruz)
Maipumed (solo Plan 200)
Uroclínica
Clínica San Donà (Av. San Martín 650, Godoy Cruz)
Clínica Santa Rosa
Clínica Santa Clara
Sanatorio Regional
Clínica Santa María (J. Federico Moreno 1549)
Clínica del Pilar
Centro Médico Don Bosco
Terrazas Alta Medicina
Clínica Araucaria
Avera

Centro propio en Mendoza (todos los planes):

PreMedic Medical Center — Av. Colón 102, Local 2, Ciudad de Mendoza. +30 especialidades + diagnóstico por imágenes.
Smile Group — red odontológica propia (odontología general, odontopediatría, blanqueamientos, carillas, implantes).

4.6 NO usar NUNCA (principio anti-clawback, ver Sección 5)
"rápido", "fácil", "en 5 minutos", "sin papeleo", "lo hacemos por vos en un día", ni nada que prometa velocidad de afiliación.

5. MARCA, TONO Y COPY
Identidad visual
Definida en el archivo vivante-brand-guide.html del proyecto. Resumen operativo:

Paleta: teal principal #2D8880, con gama clara/oscura definida. Grises de texto #4A4A52 y #7A7A84. Fondo #F8FAFA.
Tipografías: Josefin Sans (logo, headlines) + DM Sans (cuerpo). Ambas en Google Fonts.
Logo: 3 versiones en el proyecto — vertical 3D 4K, horizontal 3D 4K, isotipo 3D 4K.
Reglas do/don't: ver brand guide. No deformar, no usar sobre fondos sin contraste, isotipo solo para favicon/redes/WhatsApp.

Tono de voz (decisión tomada)
Profesional pero cálido. Voseo argentino.

Voseo siempre en marketing, landing, WhatsApp, redes.
Registro formal solo en clausulado legal, términos y condiciones, mails transaccionales.
Cero emojis en headlines de landing.
Emojis discretos en redes (máx 1 por post) y en WhatsApp cuando aporta calidez.
Cero exclamaciones de venta agresiva ("¡aprovechá ya!", "¡última oportunidad!").
Imperativo en CTAs ("Pedí", "Hablá", "Atendete"), no infinitivo ni futuro.

Ejemplos:

✅ "Atendete en Hospital Español sin pagar de más."
✅ "Usá tus aportes de obra social como corresponde."
❌ "Cuidá lo que importa ❤️"
❌ "Nosotros le ofrecemos a usted..."
❌ "Cambiá tu vida con VIVANTE"

Ángulo creativo principal — Segmento Empleados (el activo hoy)
Idea madre: VIVANTE no le vende prepaga al empleado. Le muestra cómo dejar de regalarle plata a una obra social mediocre.

Mecánica psicológica: reasignar aportes que ya hace, sin costo extra.
Villano implícito: la obra social asignada por convenio (lenta, derivativa, con copagos, turnos a 45 días).
Posicionamiento emocional: no es consumo, es jugada inteligente.

Promesa madre (titular de landing y ads):

Tus aportes ya están pagando una obra social. Hacé que paguen una mucho mejor.

Variantes para A/B en ads:

"Tu obra social no es lo único que podés tener. Y ya lo estás pagando."
"Lo que tu sueldo aporta a tu obra social puede pagar PreMedic. Sin un peso de más."
"Cambiá tu obra social por PreMedic usando los mismos aportes que ya hacés."

Estructura obligada de landing (segmento empleados)

Promesa madre — hero, una sola frase potente, tipografía liviana, mucho aire.
Dolor activado — bullets cortos, afirmaciones secas, sin "¿estás cansado de…?":

Turnos con tu obra social: 45 días.
Derivación a clínicas que no elegiste.
Copagos por todo.
Atención donde hay lugar, no donde querés.
Cuando lo necesitás de verdad, no aparece.
Cierre del bloque: "Esperar 7-10 días una vez en la vida para cambiar todo eso, vale la pena."


La movida en 3 pasos (versión honesta, sin vender velocidad):

Te asesoramos sobre tu situación particular.
Te acompañamos en cada paso del trámite (PreMedic pide documentación específica y la afiliación toma unos días).
Empezás a usar la mejor red médica de Mendoza.


Pruebas de respaldo (versión v11):

Prensa nacional: Clarín e IProfesional reconocen a PreMedic entre las prepagas más accesibles del país.
22 años de trayectoria de PreMedic.
Centro propio en Mendoza: PreMedic Medical Center, Av. Colón 102, +30 especialidades + odontología propia.
Red mendocina concreta: Hospital Español, Clínica de Cuyo, Hospital Universitario, MEDIKIDS, La Barraca, Sociedad Española.
Cobertura 100% en internación, terapia intensiva y UCO.
Sin copagos en consultas de clínica médica, ginecología y pediatría (precisión: ver Sección 4.4).


Bloque "Todo lo que incluye" (información importante, no diferencial) — íconos + microcopy de los servicios incluidos sin costo adicional (ver Sección 4.3 para el listado completo).
CTA: "Quiero saber si me conviene" → WhatsApp. Micro-copy debajo: "Te respondemos en menos de 15 minutos. Te explicamos qué plan te conviene antes de cualquier trámite."

Principio anti-clawback (no negociable)

VIVANTE nunca vende velocidad de afiliación ni facilidad de papeleo. Vende calidad de cobertura, acompañamiento durante el trámite, y respaldo a largo plazo. Cualquier promesa de rapidez del trámite está prohibida en landing, ads, WhatsApp y redes.

Razón financiera: expectativa de velocidad incumplida → frustración temprana → baja antes de 4 meses → clawback. El copy honesto protege la economía del negocio.

6. EQUIPO Y ROLES (concretos por socio)
SocioRol operativoFounder (vos)Desarrollo, landing, campañas Meta Ads, copy, tracking, redes, todo lo digitalRamónAtención WhatsApp, primer contacto, calificación, seguimiento de leadsJuan ManuelNexo con Nexio, números, comisiones, finanzas, reportes (Gerente Comercial Nexio)
SLA realista de WhatsApp

Horario formal de atención: Lunes a Viernes 9 a 19 hs. Sábados 9 a 13 hs.
Domingos y feriados: autorespuesta — "Te respondemos el lunes a primera hora."
Primera respuesta dentro del horario: ≤15 minutos.
Operador principal: Ramón.
Cobertura de respaldo (cuando Ramón no puede): cualquier socio responde con un "Hola, te respondo en X minutos / mañana a primera hora". El lead no queda plantado.

Notificaciones internas (Fase 1.5 — minimalista)

Cada lead que escribe al WhatsApp comercial llega directo al celular de Ramón.
Grupo de WhatsApp interno entre los 3 socios para: leads complicados, dudas de cotización, escalación a Juan Manuel sobre Nexio.
Telegram bot / Slack / Discord: NO instalar todavía. Volver a evaluar cuando haya formulario en landing y leads en Supabase (Fase 3+).

Reuniones internas

Daily/weekly de socios: 2 veces por semana, formato corto (10-15 min). Sugerencia: lunes (planificación) y jueves (review).


7. STACK TECNOLÓGICO REAL (Fase 1.5)
Stack en uso HOY
CapaHerramientaEstadoLandingHTML/CSS estático (armado con Claude)✅ v14 viva, retoques menores pendientesHostingNetlify✅ DeployadoDNS / ruteo de dominioCloudflare✅ vivante.ar resuelve vía Cloudflare → NetlifyMail corporativoCloudflare Email Routing + Resend✅ hola@vivante.ar recibe (Cloudflare) y responde (Resend)Dominio principalvivante.ar✅ Apuntando (Cloudflare → Netlify)Dominio defensivovivante.com.arA confirmar estadoCaptura de leadBotón directo a WhatsApp (sin formulario)✅ Número activo y cargado en landingWhatsAppWhatsApp Business app, multi-dispositivo✅ Número activoAsistente IAClaude (web + proyecto)✅
Stack archivado / NO usar en Fase 1.5
Estas cosas estaban en el contexto v1 y se descartaron explícitamente para esta fase porque no aportan valor hoy y agregan complejidad innecesaria:
HerramientaPor qué no ahoraCuándo reevaluarNext.js / VercelEl founder no programa. Una landing estática alcanza para 1 segmento.Fase 3+ si hay 4+ landings o panel adminCursor + WSL2 + Node.jsNo necesarios para editar HTML estáticoCuando se migre a Next.js (si pasa)SupabaseNo hay formulario que capture a base de datosCuando se agregue formulario antes de WhatsAppTelegram botSobra el grupo interno de WhatsAppFase 3+ con leads en BDn8nCuenta creada, sin usoMes 3+ (follow-up automático a leads fríos)Meta CAPI server-sideRequiere backend que no tenemosMes 4+ si CPL se vuelve críticoLovable, Webflow, v0, BoltDecisión: HTML estático directoNo reevaluar
Sobre Cloudflare y Resend (incorporados en v4)

Cloudflare: DNS de vivante.ar + Email Routing para recibir en hola@vivante.ar. El proxy de Cloudflare no afecta el Pixel de Meta (es JS client-side) y facilita la verificación de dominio en Meta vía registro TXT.
Resend: envío de mail desde hola@vivante.ar para responder clientes de forma manual/transaccional. ⚠️ Resend NO se usa para email marketing masivo (sigue prohibido en los 90 días, ver Sección 12). Si en el futuro se quiere hacer campañas de mail, es otra decisión y otra fase.

Costo mensual real del stack actual

Netlify: gratis (free tier alcanza).
Cloudflare: gratis (free tier: DNS + Email Routing).
Resend: gratis (free tier alcanza para el volumen actual de respuestas manuales).
Dominios: ~USD 30/año combinados.
Cursor Pro: NO contratar todavía (estaba en v1, se descarta).
Total: prácticamente USD 0/mes hasta que arranquen Meta Ads.

Arquitectura de URLs
Hoy (real): una sola landing en la raíz vivante.ar/, enfocada en empleados, con mención breve de los otros planes. No existe /empleados ni rutas por segmento.
A futuro (cuando se desdoblen segmentos):
vivante.ar/                    → landing actual (empleados-first) o home institucional
vivante.ar/empleados           → landing dedicada empleados (a futuro)
vivante.ar/monotributistas     → landing monotributistas (Fase 2.5)
vivante.ar/familias            → landing familias (Fase 2.5)
vivante.ar/sin-cobertura       → landing sin cobertura (Fase 3)
vivante.ar/gracias             → thank-you genérica
Regla: un dominio, muchas landings. NO comprar dominios por segmento.

8. META ADS Y TRACKING
Estado real (junio 2026)
COMPLETO. Bloque A cerrado. No hay bloqueantes técnicos para encender ads.

Meta Business Manager / portfolio (Business Suite): ✅ creado.
Página de Facebook: ✅ creada.
Cuenta de Instagram: ✅ creada.
Cuenta publicitaria: ✅ creada.
Método de pago en Meta: ✅ cargado.
Pixel de Meta: ✅ instalado en la landing.
Verificación de dominio: ✅ hecha (registro TXT en Cloudflare).
Evento Lead (click en botón WhatsApp): ✅ configurado.

La estructura de tracking está lista. El siguiente movimiento es de campaña, no de setup.
Cómo se crearán las campañas (decisión v5)
Crear/lanzar campañas en Meta directamente desde Claude vía connector NO es posible hoy: los connectors de Meta disponibles (Supermetrics, Windsor.ai) son de solo lectura/analítica, no crean ni publican campañas. Crear campañas por API sería desarrollo a medida (no aplica para founder no programador).
Flujo acordado: Claude redacta la spec completa de cada campaña (objetivo, público, presupuesto, estructura de ad set, copy de cada creativo) → el founder la carga y valida en Ads Manager. Un connector de reporting (Supermetrics/Windsor.ai) se evalúa en mes 2+ para traer resultados de performance a Claude y analizarlos.
Presupuesto

Mes 1: USD 150-250 (≈ USD 5-7/día).
Mes 2-3: escalar SOLO si los datos justifican (CPL razonable + tasa de cierre decente).
Cuenta nueva → Meta penaliza presupuestos altos sin historial. Empezar tranquilo es regla, no timidez.

Metas operativas (referencia, no contrato)
MesLeadsAfiliaciones cerradasAfiliaciones netas a 4 meses130-502-41-3260-1005-84-63100-15010-158-12
Si pegamos arriba: brindamos y escalamos presupuesto. Si quedamos abajo: revisamos copy/segmentación/cierre. Sin meta no hay conversación.
KPI obsesivo único
Afiliaciones netas a 4 meses ÷ inversión total en ads.
Todo lo demás (CPL, CTR, CPM, alcance) son métricas intermedias. Lo que define éxito es esta única razón.

9. BASE DE DATOS (referencia para Fase 3+)
Esto NO está implementado todavía. Se mantiene como referencia para cuando se active Supabase (sin fecha definida).
Tabla leads:
id, created_at, nombre, telefono, edad, situacion_laboral,
segmento, landing_origen, plan_interes, fuente, utm_campaign,
utm_content, utm_medium, estado, asignado_a, notas,
ip, fbc, fbp
Tabla interacciones:
id, lead_id, created_at, tipo, contenido, quien

10. RIESGOS Y MITIGACIONES
RiesgoMitigaciónMeta banea cuenta por publicidad en saludBM con dominio verificado, copy sin promesas médicas, separación de cuentas personalesLead se enfría por respuesta lentaSLA realista de 15 min + grupo interno + cobertura de respaldo entre sociosClawback por baja antes de 4 mesesPrincipio anti-clawback en copy + calificación dura antes de pasar a Nexio + filtros en preexistencias + precisión sobre copagos (consultas vs. prácticas)PreMedic lanza canal propio en MendozaMarca propia VIVANTE + base de leads como activo + opción futura de sumar otra prepagaDisputa de atribución con otros NXDecisión actual: no pedir sub-código. Revisar si aparece conflictoConflicto entre socios por comisiones✅ Acuerdo escrito firmado por los 3 (v4). Mantener actualizado si cambian las reglasMarca VIVANTE poco conocida vs. PreMedicFase 1 apoyada en PreMedic ("canal oficial"). Reevaluar mes 6Tentación de expandir a otras provinciasRegla dura: cero campañas fuera de Gran Mendoza en los primeros 6 mesesRamón es punto único de falla en WhatsAppCobertura de respaldo entre socios + SLA cumplible vs. aspiracional

11. ROADMAP REAL (post-reescritura)
Bloque A — Pre-lanzamiento de ads (BLOQUEANTES)
Ningún ad se enciende hasta que esto esté listo. Orden sugerido:

✅ Acuerdo escrito entre socios sobre: % de distribución de comisiones netas, quién paga gastos comunes, qué pasa con la marca VIVANTE si alguien se va, cómo se toman decisiones (2 de 3 o veto), reglas de salida. HECHO — firmado por los 3.
✅ Activar número de WhatsApp y cargarlo en la landing. HECHO.
✅ Apuntar vivante.ar. HECHO — resuelve vía Cloudflare → Netlify (Cloudflare también da el mail hola@vivante.ar).
✅ Crear Meta Business Manager / portfolio (Business Suite). HECHO. Página de Facebook ✅ e Instagram ✅ también creadas.
✅ Cuenta publicitaria creada + método de pago cargado. HECHO.
✅ Dominio vivante.ar verificado en Meta (registro TXT en Cloudflare). HECHO.
✅ Pixel instalado client-side en la landing. HECHO.
✅ Evento Lead (click en botón de WhatsApp) configurado. HECHO.
✅ Test end-to-end realizado. HECHO.


Estado Bloque A: ✅ CERRADO por completo. No quedan bloqueantes técnicos. El próximo paso es de campaña (ver Bloque C), no de setup.

Bloque B — Iteración de copy y creativos

✅ Landing avanzada a v14 (pulidos del PDF V4 aplicados: prensa, centro propio, copagos precisos, cobertura 100%). Quedan retoques menores.
⬜ Producir 4-6 creativos para el primer ad set en Canva (u otra herramienta) + Claude para copy. Decisión del founder (v5): después de este primer set en Canva, se incorpora video IA + character + voz IA como evolución de los creativos (Leonardo / ElevenLabs / Arcads u otras). Secuencia: primero validar ángulo con creativos simples, después escalar a video IA. Nota del CTO (no bloqueante): al introducir video/character/voz IA en un producto de salud y cuenta nueva, conviene (a) cumplir el disclosure de contenido generado por IA que pide Meta, y (b) correrlos en A/B contra al menos un creativo "real/honesto", para medir si el sintético convierte mejor o solo se ve más lindo.
⬜ Definir mensajes preformateados en WhatsApp Business + etiquetas (Nuevo, Calificado, Cotizado, Pendiente Nexio, Cerrado, Perdido).

Bloque C — Lanzamiento

Primera campaña Meta Ads sobre la landing única (vivante.ar), objetivo Leads, USD 5-7/día. (No hay /empleados: la campaña dirige a la raíz, que ya está enfocada en empleados.)
4-6 creativos en un solo ad set.
Período "no tocar" de 4-5 días.
Daily lunes y jueves entre socios para revisar leads/cierres.

Bloque D — Optimización (mes 2)

Análisis del primer mes.
Iteración de creativos basada en objeciones reales de WhatsApp.
Activación de remarketing.
Lookalike 1% basado en eventos Lead (cuando haya 100+ leads).
Activación secuencial del segundo segmento (monotributistas o familias, según learnings).

Bloque E — Expansión (mes 3+)

Si los números cierran: aumentar presupuesto.
Activación de segmentos 3 y 4.
Evaluar primer escenario de n8n (follow-up a leads sin contacto en 3 días).
Programa de referidos básico.


12. GUÍA DE FOCO — PRÓXIMOS 90 DÍAS
Esto NO son prohibiciones duras. Son guardarraíles que el founder definió para proteger tres cosas: el foco, la caja y la cuenta de Meta. Si hay una razón clara para hacer algo de esta lista, se decide conscientemente y se hace — no por reflejo. Claude no debe negarse a algo solo porque figura acá: debe avisar el trade-off y, si el founder decide avanzar, avanzar. La regla operativa de fondo sigue siendo "la opción más simple que funcione", no "está prohibido".
Dos que sí conviene mantener firmes (no por rigidez — protegen la economía y la legalidad)
Estos dos no son preferencias de estilo: tocarlos dispara reclamos y clawback.

Vender velocidad o facilidad de afiliación en cualquier copy (principio anti-clawback, ver Sección 5).
Prometer "sin copagos" a secas en segmento empleados. Siempre "sin copagos en consultas" (ver Sección 4.4).

Defaults de foco (evitar salvo razón clara y decidida)

Migrar a Next.js / Vercel / Supabase sin razón operativa que lo justifique.
Instalar Cursor + WSL2 + Node.js sin necesidad.
Cambiar stack de hosting (mantener Netlify) sin motivo.
Comprar leads de terceros.
Hacer Google Ads en paralelo antes de validar Meta.
Pagar influencers.
Sumar otra prepaga al portfolio.
Construir chatbot conversacional.
Email marketing masivo (Resend hoy es solo para respuestas manuales/transaccionales).
Refactor de código.
SEO orgánico como prioridad (buen camino, pero rinde a 6-12 meses).
Sumar herramientas nuevas a un ritmo que sature al equipo (la idea de "una por mes" es para no fundirse, no una ley).
Lanzar campañas fuera del Gran Mendoza.
Crear landings fuera de la estructura de URLs definida.
Comprar dominios adicionales más allá de vivante.ar (hoy no hace falta).
Lanzar ads sin acuerdo escrito entre socios (ya está firmado, así que destrabado).
Usar MZA25 en el segmento empleados (confunde el mensaje, ver Sección 3).


13. CONTACTOS Y RECURSOS DE NEXIO / PREMEDIC
Nexio (comercializador)

Documentación de afiliación: reclutamiento@nexio.com.ar
Formulario cotización directos/monotributo: https://admin.grupopremedic.io/lppremedic/premedic/formulario.aspx (código NX27)
Formulario desregulados: https://admin.grupopremedic.io/vendedores/premedic/agregasolicitud.aspx?id=79
Excepciones / consultas particulares: mkalinscky@grupopremedic.com.ar
Promo activa permanente Mendoza: código MZA25 (25% off, solo planes pagos)

PreMedic (institucional)

Web institucional: www.grupopremedic.com.ar
Atención al cliente: 0810-222-5522 / WhatsApp 11 2264 7285 (L-V 10-18 hs)
Sucursal Mendoza: Av. Colón 102, Local 2 — (0261) 5200592
PreMedic Medical Center Mendoza (centro propio): Av. Colón 102, Local 2 — Turnos vía App, web o WhatsApp MATI (+54 9 11 3569-7805)
ECCO Emergencias: 0810-888-3226
Asistencia al viajero (Cardinal): 0810-666-7676 (nacional) / +54 11 4129 7676 (exterior)
Redes: @premedicmedicina (IG) / /premedicmedicinaprepaga (FB)


14. CÓMO ME GUSTA QUE CLAUDE TRABAJE CONMIGO

Sin respuestas genéricas. Específico para este proyecto y mi contexto.
Una decisión por vez, una opción recomendada con justificación. No menús de 5 alternativas.
Pasos numerados + comandos exactos para copiar/pegar (cuando aplique).
Qué tengo que ver después de cada paso para saber si fue bien.
Qué hacer si algo falla anticipado.
Pregunta de cierre al final para confirmar avance.
No asumas que sé algo. Si dudás, preguntá.
Sin sobreingeniería. La opción más simple que funcione.
Honestidad técnica. Si algo es mala idea, decímelo aunque lo haya pedido.
Cero refactor en los primeros 90 días (salvo razón clara).
Una herramienta nueva por mes como guía, no como ley: el objetivo es no saturar al equipo, no frenar algo que claramente conviene.
Si algo tarda más de 2 horas, pedir ayuda explícita.


15. ESTADO ACTUAL DE UN VISTAZO (actualizar cuando cambie)

Última actualización del estado: Junio 2026 — v6.


Fase real: 1.5 — lista para encender ads (Bloque A cerrado por completo).
Segmento activo: Empleados (Plan por Aportes).
Landing: única, v14 publicada y viva en vivante.ar (Netlify vía Cloudflare), enfocada en empleados con mención breve de otros planes. No existe /empleados. Pendiente: retoques menores.
Dominio/mail: solo vivante.ar (Cloudflare → Netlify). Mail hola@vivante.ar activo (Cloudflare Email Routing + Resend para responder manual/transaccional).
Atención WhatsApp: L-V 9-19, Sáb 9-13. Operador: Ramón.
Bloqueantes para lanzar ads:

✅ Acuerdo escrito entre socios — firmado.
✅ Número de WhatsApp — activo y en la landing.
✅ vivante.ar apuntando — HECHO (Cloudflare → Netlify).
✅ Meta BM/portfolio + Página de Facebook + Instagram — creados.
✅ Cuenta publicitaria + método de pago + Pixel en landing + verificación de dominio (TXT Cloudflare) + evento Lead + test end-to-end — HECHO.
🔸 Retoques menores de la landing v14 (no bloqueante duro). Hero en transición de video → fondo WebGL interactivo.


Creativos: primer ad set en Canva + Claude para copy; luego se incorpora video IA + character + voz IA (decisión del founder, v5).
Campañas: Claude redacta la spec completa → founder la carga y valida en Ads Manager (no hay connector que cree campañas en Meta hoy).
Próximo hito: lanzar la primera campaña Meta Ads sobre vivante.ar (objetivo Leads, USD 5-7/día). Claude redacta la spec completa → founder la carga y valida en Ads Manager. Setup técnico ya cerrado.
