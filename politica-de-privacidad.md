---
title: Política de Privacidad
permalink: /privacidad/
---
# Política de Privacidad de OmniTutor

**Versión 3.2 · Última actualización: 17 de agosto de 2026**

Cómo tratamos tus datos cuando usas la aplicación OmniTutor para iOS (la "App"), conforme al Reglamento (UE) 2016/679 ("RGPD") y a la Ley Orgánica 3/2018 ("LOPDGDD"). El responsable se identifica al final. Privacidad y ejercicio de derechos: **privacidad@omni-tutor.com**.

## 1. Datos que permanecen solo en tu dispositivo

Leer tus documentos, trocearlos, indexarlos, buscar en ellos y construir la guía ocurre en tu iPhone o iPad. Estos datos no se transmiten a nuestros servidores ni a terceros, salvo los mensajes recientes del chat que se indican:

- **Tus documentos de estudio** (PDF, DOCX, imágenes) y el **índice de búsqueda** creado con ellos. La copia temporal de la importación se borra al crear el curso. Lo que sí sale del dispositivo es el **nombre** del archivo: acompaña a cada apartado de la guía que sincronizamos (sección 2) y a cada fragmento que enviamos para generar una respuesta del tutor (sección 3). Si revela algo que prefieres no compartir, renómbralo antes de importarlo.
- **El historial de chat con el tutor**, que se conserva **completo** solo en tu dispositivo, y **los cuestionarios**. Al escribir al tutor sí salen, con tu pregunta, los **mensajes recientes** de esa conversación, porque necesita el hilo para responder (sección 3).
- **Tu progreso** (resultados, racha, estadísticas), **tus preferencias** (tema, onboarding) y la **copia local** de tu aceptación de estos documentos, que es la que rige el acceso a la App.

La guía se **construye** aquí, pero su texto **sí se copia a nuestros servidores** (sección 3). Borrar un curso elimina en cascada sus documentos indexados, guía, chat y cuestionarios; desinstalar la App, todo lo local.

## 2. Datos que tratamos en nuestros servidores

Si creas una cuenta:

- **Identificativos:** nombre y correo. Con *Iniciar sesión con Apple* o *Google*, los que autorices (Apple permite un correo privado de retransmisión). Se añade un **identificador interno de usuario**.
- **Credenciales:** la contraseña la guarda nuestro proveedor de autenticación con hash irreversible; nunca la vemos en claro.
- **Datos de conexión de la sesión:** nuestro proveedor de autenticación registra en cada inicio o renovación de sesión la **dirección IP** y el **agente de usuario** (dispositivo y versión de la App), para seguridad de la cuenta y detección de accesos anómalos, y los conserva según sus propios plazos. No los usamos para perfilarte ni para deducir tu ubicación.
- **Sincronización de cursos** (tabla `courses_meta`, en la Unión Europea): título, subtítulo, icono, modo (estándar o Máx. calidad), porcentaje de progreso y **el texto de los apartados de la guía** —de cada uno: título, cuerpo tal cual se extrajo, **el nombre del archivo** del que procede (p. ej. `Apuntes de fisiología.pdf`) y si lo has marcado como completado—. Control de acceso a nivel de fila: solo tu cuenta puede leerla.

  **No** se sincronizan ni se almacenan tus **documentos originales**, tu **índice de búsqueda**, tu **historial de chat** ni tus **cuestionarios**. Del chat, los **mensajes recientes** se envían al proveedor de IA para redactar la respuesta (sección 3), pero tampoco se guardan. Si no quieres que el texto de la guía de un curso salga del dispositivo, bórralo: su fila se elimina también aquí.
- **Contadores de uso** (tabla `usage_counters`): cuántos cuestionarios y cuántos mensajes de chat has generado en el periodo, más el consumo agregado (tokens y coste estimado), para aplicar los cupos. **No contienen el contenido de tus preguntas ni de tus documentos.**
- **Verificación de suscripción:** validamos tu recibo con Apple y guardamos identificador de transacción, producto, fecha de expiración, estado (activa, en periodo de gracia, expirada o revocada) y entorno (producción o pruebas). Las suscripciones las procesa la App Store: **no recibimos ni almacenamos datos de pago**.
- **Aceptación legal** (tabla `legal_acceptances`): con sesión iniciada, la **versión** aceptada y la **fecha**, como prueba de tu consentimiento (art. 7.1 RGPD). **Como invitado no se envía nada.**
- **Soporte:** si nos escribes, tu correo y el mensaje.

**No tratamos** localización, contactos, fotos (más allá de los archivos que importas), micrófono, cámara, identificadores publicitarios, datos de navegación de terceros ni categorías especiales (art. 9 RGPD). No hay analítica de terceros, ni publicidad, ni rastreo entre apps o webs, ni perfilado.

## 3. Procesamiento con inteligencia artificial

**La guía de estudio (el índice de apartados) se construye íntegramente en tu dispositivo**; **no se envía nada a la nube para crearla**. **Las respuestas del tutor y los cuestionarios sí se generan en la nube:** la App llama a nuestro servidor intermediario, en la Unión Europea, y este al proveedor del modelo (**Anthropic**, modelo Claude); la clave del modelo vive solo en ese servidor. Ocurre con cualquier sesión iniciada, incluida la **prueba gratuita**: el plan solo cambia el cupo.

- **Cuestionarios:** una selección del temario repartida entre todos los apartados, recortada a unos **8 000** caracteres de contenido —**15 000** en modo **Máx. calidad**, del plan Pro—, más los títulos, que no se recortan; con muchos apartados el envío real supera esa cifra, con un techo absoluto de 40 000 caracteres que aplica también nuestro servidor. No se envía el nombre del archivo.
- **Chat con el tutor:** los fragmentos que la búsqueda local considera relevantes (máximo seis pasajes cortos, tope conjunto de 16 000 caracteres), tu pregunta y los mensajes recientes de esa conversación. **Con cada fragmento viaja su procedencia:** el **nombre del archivo**, el **número de página** cuando se conoce y el **título del apartado** (p. ej. `4.2.3. Navegación por estima`), que es texto de tu propio documento y, en ficheros sin paginación real como los `.docx`, el único localizador posible. Sirve para citarte de dónde sale cada afirmación.

Nunca se envía el archivo original ni el documento completo, y **tu contenido no se usa para entrenar modelos**, ni por nuestra parte ni por la del proveedor.

**Sin cuenta o sin conexión no se envía nada:** el tutor no redacta respuesta, te muestra el pasaje que encuentra en tu material señalado como tal y advirtiendo de que no ha podido conectar; el cuestionario no se genera, la App te dice por qué y conserva intacto el último que sí generaste. Lo que ya está en el dispositivo sigue consultable sin conexión.

## 4. Finalidades y bases jurídicas (art. 6 RGPD)

- **Crear y gestionar tu cuenta; autenticarte** — cuenta y credenciales. Contrato (6.1.b).
- **Sincronizar tus cursos** — datos de cursos, incluido el texto de los apartados. Contrato (6.1.b).
- **Generar lo que pides** (tutor, cuestionarios) — fragmentos de tu material, tu pregunta, mensajes recientes. Contrato (6.1.b).
- **Gestionar tu suscripción y aplicar los cupos** — estado de suscripción (vía Apple) y contadores de uso. Contrato (6.1.b).
- **Atender consultas y derechos** — datos de soporte. Contrato u obligación legal (6.1.b, 6.1.c).
- **Comunicarte cambios relevantes** — correo de la cuenta. Contrato (6.1.b).
- **Seguridad y prevención de abusos** — dirección IP y agente de usuario de cada sesión, contadores de uso, límites de frecuencia. Interés legítimo (6.1.f).
- **Funciones opcionales** (p. ej. futuros recordatorios) — los datos estrictamente necesarios. Consentimiento (6.1.a), revocable.

Sin cuenta no podemos guardar tus cursos ni generar contenido. No tomamos decisiones automatizadas con efectos jurídicos sobre ti (art. 22 RGPD): la IA genera material de estudio bajo tu control, no te evalúa.

## 5. Destinatarios

No vendemos ni cedemos tus datos. Solo intervienen:

- **Supabase** (autenticación, base de datos de sincronización y servidor intermediario), encargado del tratamiento: aloja cuenta, datos de cursos —incluido el texto de los apartados—, contadores de uso y datos de conexión, en la **Unión Europea**, bajo contrato de encargo.
- **Apple** (App Store, compras integradas, Sign in with Apple) y **Google** (solo si inicias sesión con Google): responsables independientes, según sus propias políticas.
- **Anthropic** (proveedor del modelo de IA Claude), encargado del tratamiento:
  - **Qué recibe:** solo el texto de cada petición según la sección 3 y, en el chat, la procedencia de cada fragmento. No le enviamos tu nombre, tu correo, tu identificador ni tus archivos: **ningún dato de tu cuenta viaja con la petición**.
  - **Cuánto lo conserva:** borra entradas y salidas en **30 días**.
  - **Excepción de seguridad:** si sus sistemas automáticos de detección de abusos marcan un contenido, puede conservarlo hasta **dos años**.
  - **No entrena con esos datos.**

Comunicaremos datos a las autoridades competentes cuando una obligación legal lo exija.

## 6. Transferencias internacionales

Tu cuenta, tus cursos y los contadores de uso están en servidores de la **Unión Europea**. El responsable opera desde **Suiza**, país con decisión de adecuación de la Comisión Europea.

**La generación se procesa fuera del Espacio Económico Europeo**, porque el proveedor de IA opera desde Estados Unidos. La transferencia se ampara en las **cláusulas contractuales tipo** de la Comisión Europea y, cuando resulte aplicable al proveedor, en el marco de adecuación UE-EE. UU., con las medidas complementarias correspondientes. Puedes pedirnos información sobre esas garantías.

## 7. Conservación

- **Datos locales:** bajo tu control; se eliminan al borrar el curso o desinstalar la App.
- **Cuenta y datos de cursos** (incluido el texto de los apartados): mientras mantengas la cuenta, o hasta que borres el curso. Al eliminar la cuenta se suprime todo de forma permanente, salvo el mínimo que una obligación legal exija conservar durante los plazos de prescripción.
- **Contadores de uso y aceptación legal:** se eliminan en cascada con la cuenta.
- **Datos de conexión:** según los plazos de nuestro proveedor de autenticación, con la finalidad de seguridad de la sección 4.
- **Texto enviado para generar:** no lo almacenamos; se usa y se descarta. En el proveedor de IA se borra en **30 días**, salvo marcado de seguridad (hasta **dos años**, sección 5).
- **Soporte:** lo necesario para atenderte y los plazos de prescripción aplicables.

## 8. Tus derechos

Tienes derecho de **acceso, rectificación, supresión, oposición, limitación y portabilidad**, y a retirar tu consentimiento cuando sea la base del tratamiento:

- **En la App:** borra cualquier curso o elimina tu cuenta completa desde Ajustes.
- **Por correo:** escribe a **privacidad@omni-tutor.com** desde el correo de tu cuenta, o adjunta con qué verificar tu identidad. Respondemos en el plazo máximo de un mes.

También puedes reclamar ante la autoridad de control de tu país; en España, la **Agencia Española de Protección de Datos** (www.aepd.es).

## 9. Seguridad, menores y cambios

Aplicamos cifrado en tránsito (TLS), contraseñas con hash robusto, control de acceso por filas, la clave del proveedor de IA solo en el servidor, minimización (del dispositivo solo salen los datos de las secciones 2 y 3) y el cifrado propio de iOS en local.

OmniTutor no está dirigida a menores de **14 años** (art. 7 LOPDGDD): si detectamos una cuenta de un menor de 14 sin consentimiento de sus titulares de la patria potestad o tutela, la eliminaremos.

Si modificamos esta Política de forma sustancial te lo notificaremos en la App y, cuando proceda, te pediremos aceptarla de nuevo. La versión vigente está siempre en la App (Ajustes → Legal) y en nuestra web.

## 10. Responsable del tratamiento

- **Titular:** Sergio Flores Leal, Suiza
- **Correo de contacto y privacidad:** privacidad@omni-tutor.com
