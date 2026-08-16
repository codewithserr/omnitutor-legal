---
title: Política de Privacidad
permalink: /privacidad/
---
# Política de Privacidad de OmniTutor

**Versión 3.1 · Última actualización: 16 de agosto de 2026**

## 1. Quiénes somos (Responsable del tratamiento)

El responsable del tratamiento de tus datos personales es:

- **Titular:** [NOMBRE Y APELLIDOS DEL TITULAR / DENOMINACIÓN SOCIAL]
- **NIF:** [NIF/CIF]
- **Domicilio:** [DIRECCIÓN COMPLETA], España
- **Correo de contacto y privacidad:** privacidad@omni-tutor.com

Esta Política describe cómo tratamos tus datos cuando usas la aplicación OmniTutor para iOS (la "App"), conforme al Reglamento (UE) 2016/679 ("RGPD") y a la Ley Orgánica 3/2018 ("LOPDGDD").

## 2. Resumen: qué se queda en tu dispositivo y qué sale de él

- **Tus archivos no salen de tu dispositivo.** La lectura de tus documentos, su troceado, la creación del índice de búsqueda, las búsquedas que haces sobre él y la construcción de la guía de estudio ocurren íntegramente en tu iPhone o iPad. Nunca subimos tus ficheros a ningún servidor. Lo que no sale es **el archivo**: su **nombre** sí, y lo hace por dos vías —acompaña a cada apartado de la guía que sincronizamos (sección 3.2) y acompaña también, junto con el **número de página** y el **título del apartado** en el que se encuentra, a cada fragmento que enviamos para generar una respuesta del tutor (sección 5)—. Si el nombre de un fichero revela algo que prefieres no compartir, renómbralo antes de importarlo.
- **Para generar contenido sí se envía texto a la nube.** Cuando escribes al tutor o creas un cuestionario, la App manda a nuestro servidor —y este a nuestro proveedor de inteligencia artificial— **una selección acotada del texto** de tu material: los fragmentos o extractos necesarios para esa petición concreta, nunca el documento entero ni el archivo original. El detalle está en la sección 5.
- **El texto de la guía se guarda en nuestros servidores** (en la Unión Europea) para que puedas recuperar tus cursos en otros dispositivos. Tus documentos originales, tu índice de búsqueda, tus chats y tus cuestionarios no se sincronizan. El detalle está en la sección 3.2.
- **No hay analítica de terceros, ni publicidad, ni rastreo entre apps o webs, y nunca vendemos tus datos.**
- **No usamos tus documentos, tus chats ni tus cuestionarios para entrenar modelos de inteligencia artificial.**

En nuestros servidores tratamos los datos mínimos de tu cuenta, los datos de tus cursos —incluido el texto de los apartados de la guía— para sincronizarlos y los contadores de uso necesarios para aplicar los cupos de tu plan, tal y como se detalla a continuación.

## 3. Qué datos tratamos y de dónde proceden

### 3.1 Datos que permanecen solo en tu dispositivo

Estos datos se guardan localmente en tu dispositivo y **no se transmiten a nuestros servidores ni a terceros**, con la única excepción de los mensajes recientes del chat que se indica más abajo:

- **Tus documentos de estudio** (PDF, DOCX, imágenes) —los **documentos originales**— y el **índice de búsqueda** generado a partir de ellos. La copia temporal usada durante la importación se elimina automáticamente tras crear el curso.
- **El historial de chat con el tutor**, que se conserva **completo** solo en tu dispositivo, y **los cuestionarios** generados a partir de tus documentos. Cuando escribes al tutor sí salen del dispositivo, junto con tu pregunta, los **mensajes recientes** de esa conversación, porque el tutor necesita el hilo para responder: el detalle está en la sección 5.
- **Tu progreso de estudio**: resultados de cuestionarios, racha y estadísticas.
- **Tus preferencias** (tema de la interfaz, estado del onboarding) y la **copia local** del registro de tu aceptación de estos documentos legales, que es la que rige el acceso a la App. Si tienes una cuenta, esa aceptación además se replica a nuestros servidores: ver la sección 3.2.

La guía de estudio se **construye** en tu dispositivo, pero su texto **sí se copia a nuestros servidores** para sincronizar el curso entre tus dispositivos: ver la sección 3.2.

**Lo que sale de tu dispositivo para generar son fragmentos de texto, no tus ficheros.** El archivo que importaste se queda en tu dispositivo; a la nube viaja únicamente el texto seleccionado para la petición que has hecho, y no lo conservamos en nuestros servidores.

Puedes eliminar los datos locales en cualquier momento borrando el curso correspondiente dentro de la App (se eliminan en cascada sus documentos indexados, guía, chat y cuestionarios) o desinstalando la App.

### 3.2 Datos de tu cuenta (tratados en nuestros servidores)

Si creas una cuenta, tratamos:

- **Datos identificativos:** nombre y dirección de correo electrónico. Si usas *Iniciar sesión con Apple* o *Google*, recibimos el nombre y el correo que autorices (con Apple puedes usar un correo privado de retransmisión).
- **Credenciales:** tu contraseña se almacena de forma cifrada e irreversible (hash) por nuestro proveedor de autenticación; nunca tenemos acceso a ella en claro.
- **Identificador interno de usuario** asignado al crear la cuenta.
- **Datos de conexión de la sesión:** nuestro proveedor de autenticación registra, cada vez que inicias sesión o se renueva tu sesión, la **dirección IP** y el **agente de usuario** (la identificación del dispositivo y la versión de la App) desde los que te conectas. Sirven para la seguridad de la cuenta y la detección de accesos anómalos, y los conserva conforme a sus propios plazos de registro. No los usamos para perfilarte ni para deducir tu ubicación.
- **Datos de sincronización de cursos** (tabla `courses_meta`, alojada en la Unión Europea): título y subtítulo del curso, icono, modo del curso (estándar o Máx. calidad), porcentaje de progreso y **el texto de los apartados de la guía**. De cada apartado se guardan cuatro cosas: su título, su cuerpo tal y como se extrajo de tus documentos, **el nombre del archivo del que procede** (por ejemplo, `Apuntes de fisiología.pdf`) y si lo has marcado como completado. Se guardan para que puedas recuperar tus cursos al iniciar sesión en otro dispositivo o tras reinstalar la App. Cada fila está protegida por control de acceso a nivel de fila: solo tu cuenta puede leerla.

  Lo que **no** se sincroniza ni se almacena en nuestros servidores: tus **documentos originales**, tu **índice de búsqueda**, tu **historial de chat** con el tutor y tus **cuestionarios**. Esos datos se guardan en tu dispositivo y no los copiamos a ninguna tabla nuestra; del chat, los **mensajes recientes** de la conversación se envían al proveedor de IA para poder redactar la respuesta que pides (sección 5), pero tampoco se almacenan.

  Si no quieres que el texto de la guía de un curso salga de tu dispositivo, elimina ese curso: su fila se borra también de nuestros servidores.
- **Contadores de uso** (tabla `usage_counters`): cuántos cuestionarios y cuántos mensajes de chat has generado en el periodo en curso, más el consumo agregado asociado (tokens y coste estimado). Sirven para aplicar los cupos de tu plan. **No contienen el contenido de tus preguntas ni de tus documentos.**
- **Verificación de suscripción:** para activar las funciones de pago validamos tu recibo de compra con Apple y guardamos el estado de tu suscripción (identificador de transacción, producto, fecha de expiración, estado —activa, en periodo de gracia, expirada o revocada— y entorno —producción o pruebas—) vinculado a tu cuenta.
- **Registro de aceptación legal** (tabla `legal_acceptances`): si tienes la sesión iniciada, guardamos la **versión** de estos documentos que aceptaste y la **fecha** de aceptación, vinculadas a tu cuenta, como prueba de tu consentimiento (art. 7.1 RGPD). **Como invitado, sin sesión iniciada, no se envía nada**: tu aceptación queda solo en tu dispositivo (sección 3.1).

### 3.3 Datos de compra

Las suscripciones se contratan y procesan a través de la App Store de Apple. **No recibimos ni almacenamos tus datos de pago** (tarjetas, facturación); únicamente comprobamos, a través del sistema de Apple, si tu suscripción está activa.

### 3.4 Datos de soporte

Si nos escribes, trataremos tu correo y el contenido del mensaje para atenderte.

### 3.5 Datos que NO tratamos

No recopilamos: localización, contactos, fotos (más allá de los archivos que tú eliges importar), micrófono, cámara, identificadores publicitarios, datos de navegación de terceros ni datos de categorías especiales (art. 9 RGPD). No realizamos perfilado ni publicidad comportamental.

## 4. Para qué usamos tus datos y con qué base jurídica (art. 6 RGPD)

- **Crear y gestionar tu cuenta; autenticarte.** Datos: cuenta, credenciales. Base jurídica: ejecución del contrato (6.1.b).
- **Prestar el servicio: sincronizar tus cursos entre sesiones y dispositivos.** Datos: datos de cursos, incluido el texto de los apartados de la guía. Base jurídica: ejecución del contrato (6.1.b).
- **Generar el contenido de estudio que nos pides** (respuestas del tutor, cuestionarios). Datos: fragmentos del texto de tus documentos, tu pregunta y los mensajes recientes de la conversación. Base jurídica: ejecución del contrato (6.1.b).
- **Gestionar tu suscripción y aplicar los cupos de generación de tu plan.** Datos: estado de suscripción (vía Apple), contadores de uso. Base jurídica: ejecución del contrato (6.1.b).
- **Atender tus consultas y el ejercicio de derechos.** Datos: datos de soporte. Base jurídica: ejecución del contrato / obligación legal (6.1.b y 6.1.c).
- **Garantizar la seguridad del servicio y prevenir abusos.** Datos: registros técnicos mínimos de autenticación —incluidos la dirección IP y el agente de usuario de cada sesión (sección 3.2)—, contadores de uso y límites de frecuencia. Base jurídica: interés legítimo (6.1.f).
- **Comunicarte cambios relevantes del servicio o de estos documentos.** Datos: correo de la cuenta. Base jurídica: ejecución del contrato (6.1.b).
- **Funciones opcionales que requieran consentimiento** (p. ej. futuros recordatorios con notificaciones). Datos: los estrictamente necesarios. Base jurídica: consentimiento (6.1.a), revocable en cualquier momento.

No tomamos decisiones automatizadas con efectos jurídicos sobre ti (art. 22 RGPD). La IA de la App genera material de estudio bajo tu control; no evalúa tu persona ni condiciona derechos.

## 5. Procesamiento con inteligencia artificial

**La guía de estudio (el índice de apartados) se construye íntegramente en tu dispositivo** a partir del texto extraído de tus documentos; **no se envía nada a la nube para crearla**. **Las respuestas del tutor y los cuestionarios sí se generan en la nube**: la App envía la petición a nuestro servidor intermediario, alojado en la Unión Europea, y este la reenvía al proveedor del modelo de IA (**Anthropic**, modelo Claude). La clave de acceso al modelo vive solo en nuestro servidor: la App nunca habla directamente con el proveedor.

**Ocurre para cualquier usuario con la sesión iniciada, incluida la prueba gratuita.** No es una función exclusiva de los planes de pago ni algo que actives aparte: es cómo funciona la generación. Lo que cambia según el plan es el cupo de cuestionarios y mensajes, no el hecho de que el texto se procese en la nube.

**Qué se envía, y cuánto**, según lo que estés haciendo:

- **Cuestionarios:** una selección del temario de tu curso, repartida entre todos sus apartados y recortada a unos **8 000** caracteres de contenido de los apartados —**15 000** si el curso está en modo **Máx. calidad**, función del plan Pro—, más los títulos de esos apartados, que no se recortan. En un curso con muchos apartados los títulos hacen que el envío real supere esa cifra; el techo absoluto del envío es de 40 000 caracteres. El recorte lo aplica también nuestro servidor antes de llamar al proveedor, de modo que el límite se cumple aunque la App pidiese más.
- **Chat con el tutor:** solo los fragmentos que la búsqueda local ha identificado como relevantes para tu pregunta (como mucho seis pasajes cortos, con un tope conjunto de 16 000 caracteres), tu pregunta y los mensajes recientes de esa conversación. **Con cada fragmento viaja su procedencia:** el **nombre del archivo** del que se extrajo, el **número de página** cuando se conoce y el **título del apartado** en el que se encuentra (por ejemplo, `4.2.3. Navegación por estima`), que es texto de tu propio documento. En los archivos sin paginación real, como los `.docx`, el título del apartado es el único localizador posible. Sirven para que el tutor pueda citarte de dónde sale cada afirmación, y salen del dispositivo igual que el fragmento. En los cuestionarios no se envía el nombre del archivo: solo los títulos y el texto de los apartados.

En ningún caso se envía el archivo original ni el documento completo.

**Sin cuenta o sin conexión no se envía nada.** La generación en la nube exige una sesión iniciada y conexión a internet. Si falta cualquiera de las dos, la App no envía nada: el tutor no redacta una respuesta, sino que te muestra el pasaje que encuentra en tu propio material, señalado como tal y advirtiendo de que no ha podido conectar; y el cuestionario directamente no se genera, la App te dice por qué y conserva intacto el último que sí generaste, para que puedas repasarlo sin conexión. Todo lo que ya tienes en el dispositivo se puede seguir consultando sin conexión.

**Tu contenido no se usa para entrenar modelos**, ni por nuestra parte ni por la del proveedor.

## 6. Destinatarios: quién puede acceder a tus datos

No vendemos ni cedemos tus datos. Solo intervienen estos proveedores, en calidad de encargados del tratamiento o responsables independientes:

- **Supabase** (autenticación, base de datos de sincronización y servidor intermediario de generación): aloja los datos de tu cuenta, los datos de cursos —incluido el texto de los apartados de la guía—, los contadores de uso y los datos de conexión de tus sesiones (dirección IP y agente de usuario), en servidores ubicados en la **Unión Europea**, bajo contrato de encargo de tratamiento.
- **Apple** (App Store, In-App Purchase, Sign in with Apple): actúa como responsable independiente respecto de tus compras y tu ID de Apple, conforme a su propia política de privacidad.
- **Google** (solo si eliges iniciar sesión con Google): responsable independiente respecto de tu cuenta de Google.
- **Anthropic** (proveedor del modelo de IA Claude), encargado del tratamiento:
  - **Qué recibe:** únicamente el texto que se le envía para cada petición según la sección 5 —fragmentos o extractos de tu material, tu pregunta y los mensajes recientes de la conversación—, y, en el caso del chat, la **procedencia de cada fragmento**: el nombre del archivo del que se extrajo y, cuando se conoce, el número de página. No le enviamos tu nombre, tu correo, tu identificador de usuario ni tus archivos: **ningún dato de tu cuenta viaja con la petición**.
  - **Cuánto lo conserva:** borra las entradas y salidas de la petición en un plazo de **30 días**.
  - **Excepción de seguridad:** si sus sistemas automáticos de detección de abusos marcan un contenido, puede conservarlo hasta **dos años** a efectos de seguridad y cumplimiento.
  - **No entrena con esos datos:** el contenido enviado desde OmniTutor no se utiliza para entrenar ni mejorar sus modelos.

Podremos comunicar datos a autoridades competentes cuando una obligación legal lo exija.

## 7. Transferencias internacionales

Los servidores donde viven tu cuenta, los datos de tus cursos y los contadores de uso están en la **Unión Europea**.

**La generación de contenido, en cambio, se procesa fuera del Espacio Económico Europeo**, porque nuestro proveedor de IA opera desde Estados Unidos. No podemos garantizarte que ese tratamiento ocurra en territorio europeo. La transferencia se ampara en las **cláusulas contractuales tipo** aprobadas por la Comisión Europea y, cuando resulte aplicable al proveedor, en el marco de adecuación UE-EE. UU., junto con las medidas complementarias correspondientes.

Puedes solicitarnos información sobre estas garantías en privacidad@omni-tutor.com.

## 8. Cuánto tiempo conservamos tus datos

- **Datos locales del dispositivo:** bajo tu control; se eliminan al borrar el curso o desinstalar la App.
- **Datos de cuenta y datos de cursos (incluido el texto de los apartados de la guía):** mientras mantengas la cuenta, o hasta que borres el curso —al borrarlo se elimina también su fila en nuestros servidores—. Al eliminar la cuenta se suprimen de forma permanente todas sus filas, salvo el mínimo bloqueado que una obligación legal nos exija conservar (p. ej. registros a efectos de responsabilidad, durante los plazos de prescripción legales).
- **Contadores de uso:** mientras la cuenta exista; se eliminan con ella.
- **Registro de aceptación legal:** mientras la cuenta exista; se elimina con ella, en cascada con tu cuenta.
- **Datos de conexión de la sesión** (dirección IP y agente de usuario): los conserva nuestro proveedor de autenticación conforme a sus propios plazos de registro, con la finalidad de seguridad descrita en la sección 4.
- **Texto enviado para generar:** no lo almacenamos en nuestros servidores; se usa para atender tu petición y se descarta. En el proveedor de IA, se borra en un plazo de **30 días**, salvo que sus sistemas automáticos de seguridad lo marquen, en cuyo caso puede conservarse hasta **dos años** (sección 6).
- **Soporte:** el tiempo necesario para atender tu consulta y los plazos de prescripción aplicables.

## 9. Tus derechos

Puedes ejercer en cualquier momento tus derechos de **acceso, rectificación, supresión, oposición, limitación del tratamiento y portabilidad**:

- **Dentro de la App:** borra cualquier curso (elimina su contenido local asociado) o elimina tu cuenta completa desde Ajustes.
- **Por correo:** escribiendo a **privacidad@omni-tutor.com** desde el correo de tu cuenta, o adjuntando información que permita verificar tu identidad. Responderemos en el plazo máximo de un mes.

Si consideras que no hemos atendido correctamente tus derechos, puedes reclamar ante la **Agencia Española de Protección de Datos** (www.aepd.es, C/ Jorge Juan 6, 28001 Madrid).

## 10. Seguridad

Aplicamos medidas técnicas y organizativas apropiadas: cifrado en tránsito (TLS) de toda comunicación con nuestros servidores, almacenamiento de contraseñas con hash robusto, control de acceso por filas en la base de datos (cada usuario solo accede a sus propios registros), la clave del proveedor de IA guardada exclusivamente en el servidor y nunca en la App, principio de minimización (solo salen del dispositivo los datos descritos en los apartados 3.2 y 5) y protección del almacenamiento local por los mecanismos de cifrado del propio dispositivo iOS.

## 11. Menores de edad

OmniTutor no está dirigida a menores de **14 años**. Si eres menor de 14, no crees una cuenta ni nos facilites datos. Si detectamos una cuenta de un menor de 14 años sin consentimiento de sus titulares de la patria potestad o tutela, la eliminaremos.

## 12. Cambios en esta Política

Si modificamos esta Política de forma sustancial, te lo notificaremos dentro de la App y, cuando proceda, te pediremos que la aceptes de nuevo antes de continuar. La versión vigente estará siempre disponible en la App (Ajustes → Legal) y en nuestra web.

## 13. Contacto

Para cualquier cuestión sobre privacidad o para ejercer tus derechos: **privacidad@omni-tutor.com**.
