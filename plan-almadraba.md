# Plan de identificación y preservación: caso Almadraba Diseño

**Lunes 20 de marzo, 10:45.** Plan previo a tocar nada, elaborado solo con mi lista de comprobación (`lista-comprobacion.md`). Las referencias **L1…L24** son los puntos de esa lista; entre paréntesis va la norma que los respalda.

## Lo que le digo a Elena (resumen)

1. **Protegemos** lo que está encendido y a la vista (portátil, móvil de empresa, sesiones abiertas) y a las personas que pueden alterarlo, antes de abrir ningún aparato.
2. **Lo que se pierde si esperamos** no es solo la memoria del portátil: el cortafuegos sobrescribe sus registros cada ~7 días, la cámara del pasillo graba en un aparato ajeno con retención desconocida, la copia de seguridad más antigua se pisa cada noche y la cuenta de Marta en la nube puede cambiar desde fuera.
3. **Necesitamos de otros**: Bahía Sistemas (registros, copias, claves BitLocker, nube), la administración de la finca (grabaciones) y, para el móvil personal de Marta, su consentimiento. Sin esas tres peticiones, parte de la prueba desaparece o no podemos usarla.

> **Aviso sobre las fechas del caso.** El relato dice «jueves 14», pero si hoy es lunes 20, el jueves anterior es el 16. No lo asumo: pido conservar **toda la ventana desde el 6 de marzo** (hace dos semanas se presentó el render) y confirmaré con Javier la fecha exacta. *(RFC §3.2: «cuestionar qué más puede ser evidencia»; L10)*

---

## 1. Las fuentes de evidencia

*(L9 a L14: inventario de lo visible, lo oculto, lo compartido, lo remoto, el teletrabajo y los propietarios.)*

| ID | Fuente | Dónde está / quién la controla | Qué puede aportar | Punto |
| :-- | :-- | :-- | :-- | :-- |
| **A. En la mesa de Marta** | | | | |
| F1 | Portátil Dell (encendido, bloqueado, BitLocker) | Empresa. Sesiones de VPN, OneDrive y correo abiertas | Memoria viva, procesos y conexiones, disco cifrado, historial de USB y de ficheros | L8, L9 |
| F2 | Dock USB-C, monitores, teclado y ratón | Empresa. El dock alimenta el portátil | Qué se conectó y por dónde; es también la **alimentación** del portátil | L7, L8 |
| F3 | Disco externo negro de 2 TB | Empresa (a confirmar) | Posible copia de proyectos | L9, L14 |
| F4 | iPhone de empresa con funda del estudio | Empresa; Marta lo usa para WhatsApp con clientes | Conversaciones con clientes, fotos, ficheros | L9, L21 |
| F5 | Móvil personal asomando del bolso | **De Marta** (personal) | Comunicación con Lucía; Marta dice que «no hay nada del trabajo», lo cual no puedo comprobar | L9, L14 |
| **B. En la oficina, fuera de su mesa** | | | | |
| F6 | Equipo compartido de la entrada con sesión de Outlook web de **otra compañera** | Empresa; sesión de una tercera persona | Origen de la sesión y uso; documentos escaneados | L11, L14 |
| F7 | Impresora multifunción (escanea al correo de quien la usa y guarda historial) | Empresa; administrada por Bahía | Qué se escaneó o imprimió, cuándo y por quién | L11, L15 |
| F8 | Pendrive de Javier, en su cajón (se lo prestó a Marta esa semana y se lo devolvió) | De Javier | Posible vía de copia | L10, L14 |
| **C. No están a la vista** | | | | |
| F9 | **Pendrive propio de Marta** («no le funcionaba»): paradero desconocido | Desconocido | Posible vía de copia, ya usado y apartado | L10 |
| F10 | Equipos y red de casa de Marta (teletrabaja los viernes con el mismo portátil y VPN) | **Marta** | Restos de ficheros, sesiones, dispositivos | L13, L14 |
| F11 | Cámara domo del pasillo y su **grabador en conserjería** | **Comunidad / administración de la finca** | Quién entró y salió y cuándo, p. ej. la tarde del 14 | L11, L14, L15 |
| **D. Infraestructura local («lo de informática»)** | | | | |
| F12 | Servidor de ficheros del cuartito | Empresa; administrado por Bahía | Accesos y modificaciones del render y sus proyectos | L12 |
| F13 | NAS con copias nocturnas (se conservan las últimas 14) | Empresa; administrado por Bahía | Estado de los ficheros día a día; la copia más antigua es la línea base | L12, L15 |
| F14 | Cortafuegos: registro de conexiones (~1 semana) y VPN | Empresa; administrado por Bahía | Tráfico saliente del portátil, sesiones VPN, conexiones fuera de horario | L12, L13, L15 |
| F15 | Router, switch y Wi-Fi: tablas ARP, concesiones DHCP y asociaciones | Empresa; Bahía | Qué equipo tenía qué IP y cuándo | L12 |
| **E. Nube y terceros** | | | | |
| F16 | Microsoft 365: OneDrive (versiones, papelera, registros de acceso, descargas y comparticiones), correo de Marta (envíos, reglas de reenvío), registros de inicio de sesión | Empresa; administrador en Bahía o Elena | Si se descargó o compartió el render, desde qué dispositivo y cuándo | L12, L13, L15 |
| F17 | Portal de Microsoft con las **claves de recuperación de BitLocker** | Empresa; Bahía | Acceso al disco cifrado si el portátil se apaga | L12, L19 |
| F18 | **Bahía Sistemas** (acceso remoto y de administración, VPN, mantenimiento) | Tercero | Sus acciones también son evidencia y pueden alterar lo demás | L5, L22 |
| F19 | Copia del iPhone en iCloud y mensajes de WhatsApp | Empresa (a confirmar) | Respaldo de conversaciones | L12, L14 |
| **F. Personas** | | | | |
| F20 | Marta, Javier, la compañera de la sesión abierta, Elena y el técnico de Bahía | — | Qué vieron y hicieron, fechas y claves de acceso | L4 |

**Lo que se deduce del relato y no se ve a primera vista:** el pendrive que falta (F9), el teletrabajo en casa (F10), la nube (F16), los registros de red (F14, F15), el grabador de conserjería (F11), la sesión de otra persona (F6) y el hecho de que **Bahía puede ser a la vez ayuda y riesgo** (F18).

---

## 2. La prioridad

*(Criterio: L16, L17 y L18. Se ordena por **lo que antes se pierde**, no solo por RAM: RFC §2.1, NIST §3.1.2.)*

| Orden | Fuente | Se pierde por… | Plazo | Por qué va aquí |
| :-- | :-- | :-- | :-- | :-- |
| **1** | **Control de personas y comunicaciones** (Marta, F5, F1–F4) | Acción humana: borrar, apagar, enviar | **Minutos** | Es lo que más rápido destruye prueba y no cuesta nada: separar a Marta de sus dispositivos y comunicaciones. *(L3 · ENFSI §8.2)* |
| **2** | **F1 Portátil Dell: memoria viva y estado** | Apagado, suspensión prolongada, batería o intervención de Marta | **Minutos / horas** | Es lo más volátil de la escena y lleva cifrado. *(L16, L19 · RFC §2.1, §2.2; ENFSI §9.1)* |
| **3** | **F4 iPhone de empresa** | Borrado remoto, sincronización, bloqueo | **Minutos / horas** | Dispositivo de comunicación activo. *(L21 · ENFSI §8.2, §9.2)* |
| **4** | **F6 sesión de Outlook compartida** | Caducidad de la sesión, cierre por otra persona | **Horas** | Estado en pantalla que se pierde con cualquier cierre. *(L7, L16 · NIST §3.1.2)* |
| **5** | **F14, F15 Cortafuegos, VPN, ARP y DHCP** | **Sobrescritura continua (~7 días)** | **Horas / 1 día** | Se pierde solo, aunque no hagamos nada. Con ~7 días de retención ya se están perdiendo registros anteriores al 13 de marzo, y el 14 está en el límite. *(L15, L16 · NIST §3.1.2: aunque no sean volátiles, los datos como los ficheros de registro «se sobrescriben» y pueden ser dinámicos; RFC §2.1: registros remotos)* |
| **6** | **F11 Grabaciones de la cámara** | **Grabación en bucle** en un aparato ajeno | **Desconocido (potencialmente días)** | No sé cuánto conserva ni quién puede borrarlo; el esfuerzo de conseguirlo es alto, así que se pide ya. *(L15, L17 · NIST §3.1.2)* |
| **7** | **F16 Microsoft 365 y F17 clave BitLocker** | Registros de inicio de sesión y auditoría de **Entra ID** (**7 días** con la edición gratuita, **30** con P1/P2); borrados o cambios hechos por Marta desde fuera; baja de cuenta o licencia por la excedencia (1 de abril) | **Horas / días** | Los registros de **Entra ID** caducan pronto y los de **auditoría de Microsoft 365** duran más (**180 días** por defecto; hasta 1 año con licencias E5), así que lo urgente es el inicio de sesión. Si el inquilino usa la edición gratuita, el día 14 también está en el límite. Marta puede además alterar su buzón y su OneDrive desde el móvil o desde casa (lo que borre va a la papelera de OneDrive, que conserva **93 días**, pero las versiones antiguas recortadas por los límites de versiones no pasan por ella). Sin la clave de BitLocker localizada, apagar el portátil podría ser irreversible. *(L15, L16, L19 · NIST §3.1.2; ENFSI §9.1: cifrado en vivo)* |
| **8** | **F13 NAS** | **Rotación nocturna**: cada noche se pisa la copia más antigua | **Esta noche** | Se conservan 14 copias (≈ desde el 6 de marzo): las **más antiguas** (la fecha de presentación del render, que sirve de línea base) son las próximas en caer. *(L15, L16 · RFC §2.1: medios de archivo; NIST §3.1.2)* |
| **9** | **F7 Impresora** | Retención desconocida («no sé cuánto») | **Desconocido** | Historial acotado en tamaño. *(L15 · NIST §3.1.2)* |
| **10** | **F8 pendrive de Javier, F3 disco externo, F9 pendrive de Marta** | Reutilización, formateo, pérdida | **Días** | Estables si se aseguran físicamente. *(L9, L10 · NIST §3.1.1)* |
| **11** | **F12 servidor, disco del portátil, F19** | — | Estables | Se adquieren después, sobre copia, en orden. *(L24 · RFC §2, §3.2)* |
| **12** | **F5 móvil personal, F10 casa** | — | — | No puedo actuar sin consentimiento o autoridad. Ver apartado 4. *(L23)* |

**Ejecución:** las tareas 1 a 4 las hago yo, **en el sitio y paso a paso en cada sistema**. A la vez lanzo por teléfono las peticiones 5 a 8 a terceros, que me cuestan poco a mí pero tardan en ejecutarse. La RFC permite repartir el trabajo en paralelo **entre dispositivos distintos**, pero no dentro de un mismo sistema *(L18 · RFC §2)*. El orden no sigue solo la RAM: el cortafuegos puede perder datos *antes* que la RAM porque la RAM está protegida mientras Marta esté apartada y el portátil siga encendido y alimentado.

---

## 3. Las medidas inmediatas

### Respuesta a Marta (esperando una respuesta)

- Con Elena presente y con tono cordial: **durante la intervención no puede usar el portátil, el móvil de empresa ni ninguna cuenta del estudio**, y se le pide que se aleje de la mesa. *(L3 · ENFSI §8.2)*
- **Puede irse a casa si quiere**: no tengo autoridad para retenerla. Se va **sin llevarse nada de la empresa** (portátil, iPhone, disco externo y accesorios se quedan donde están). Se anota la hora de salida y lo que dice, con sus palabras, y que declara que su móvil personal no contiene nada del trabajo. *(L4, L23 · RFC §3.2)*
- Si Elena lo decide, con asesoramiento laboral y legal: **bloqueo temporal de sus accesos remotos** (ver F16), sin borrar ni restablecer nada. *(L20, L23 · RFC §2: quitar vías externas de cambio)*

### Medidas por fuente

| Fuente | Qué hago ahora | Qué NO hago | Punto |
| :-- | :-- | :-- | :-- |
| **F1 Portátil** | Lo dejo **encendido, bloqueado y conectado al dock** (alimentado). Fotografío pantalla, hora, cables y dock. Anoto la hora local y su diferencia con UTC. Un custodio lo vigila. Pido que Bahía **confirme que hay una clave de recuperación de BitLocker guardada para este portátil** (en Entra ID, *Dispositivos > BitLocker keys*) y que anote su identificador; que **coincida** con la clave realmente en uso solo podré comprobarlo con credenciales de administración (por ejemplo con `manage-bde -protectors -get C:`). Pido credenciales de administración **a través de Bahía** para, más adelante, volcar la RAM con herramientas desde medio de solo lectura. | No lo apago, no lo reinicio, no tecleo ni lo desbloqueo, no lo muevo, **no desconecto el dock** (le quita la alimentación). | L2, L7, L8, L19 · RFC §2, §2.2, §3.2, §5; NIST §3.1.2; ENFSI §9.1 |
| **F1 Aislamiento de red** | En vez de cortar cables, pido a Bahía que **bloquee el dispositivo y la cuenta en el cortafuegos y en la nube**, sin enviar órdenes remotas de borrado ni bloqueo. | No cortar la red a ciegas (**posible «deadman»**) ni dejar que Bahía lance acciones remotas sobre el portátil. | L20 · RFC §2, §2.2; NIST §3.1.3 |
| **F2 Dock y accesorios** | Fotografío conexiones y anoto modelos y números de serie. | No desconecto nada. | L7 · ENFSI §8.2 |
| **F3 Disco externo** | Lo fotografío y etiqueto *in situ*; anoto serie y puerto. | No lo desconecto del dock ni lo conecto a otro equipo. | L7, L24 · ENFSI §8.2; RFC §2 |
| **F4 iPhone de empresa** | Fotografío. Lo aíslo de la red (**modo avión desde el Centro de control**, que por defecto se puede abrir con el móvil bloqueado salvo que se haya desactivado en *Ajustes > Face ID y código*; si no se puede, **bolsa Faraday con powerbank o cargador dentro**). Pido a Elena el propietario del Apple ID y a Bahía que **no ejecuten borrado remoto**. | No lo apago, no lo conecto a un ordenador, no uso la bolsa sin alimentación (la batería se agota). | L20, L21 · ENFSI §8.2, §9.2 |
| **F5 Móvil personal** | Fotografío el bolso tal como está. Pido a Marta, con Elena presente, **consentimiento por escrito** para sellarlo temporalmente. Si no acepta, lo anoto y respeto su decisión. | No lo toco, no registro el bolso. | L23 · RFC §2.3; NIST §3.1.1 |
| **F6 Equipo compartido** | Fotografío la pantalla con la hora; anoto qué cuenta es y qué muestra. Pido a la compañera que **no cierre la sesión ni lo use** y le explico qué voy a hacer. Pido a Bahía los **registros de inicio de sesión** de su cuenta. | No la cierro, no leo su correo, no actúo con su sesión. | L7, L11, L23 · NIST §3.1.2; RFC §2.3 |
| **F7 Impresora** | Fotografío el panel y anoto modelo e IP. Pido a Bahía que **exporte el historial de trabajos y de escaneo al correo** con su fecha. | No la apago ni la desconecto; no borro historial. | L11, L15, L22 · NIST §3.1.1; RFC §2.2 |
| **F8 Pendrive de Javier** | Le pido que **no lo use ni lo conecte**; lo recojo, lo **etiqueto y lo guardo en bolsa** con firma de Javier y hora. Anoto su declaración (fecha exacta de la tarde y del préstamo). | No lo conecto a ningún equipo. | L4, L24 · NIST §3.1.2; ENFSI §8.2; RFC §3.2 |
| **F9 Pendrive de Marta** | Le pregunto dónde está y busco en las zonas del estudio (mesa y cajones del estudio, no en el bolso). Pido a Bahía si hay **registro de USB conectados** en gestión de equipos. | No registro sus objetos personales. | L10, L23 · NIST §3.1.1; RFC §3.2 |
| **F10 Casa** | Pregunto a Elena si hay más material del estudio en casa de Marta. Pido que se conserve el **registro de VPN** de los viernes. | No actúo fuera de la oficina. | L13, L23 · NIST §3.1.1 |
| **F11 Cámara** | **Elena llama ya a la administración de la finca** y les escribe: que **dejen de sobrescribir** o exporten las grabaciones desde el 6 de marzo (en especial la tarde del 14 y del 16, y el día de hoy), con su retención y quién puede acceder al grabador. | No entro en conserjería ni manipulo el grabador. | L11, L14, L15, L22 · NIST §3.1.1 |
| **F12 Servidor** | Pido a Bahía que **no lo apague ni lo cambie** y que conserve sus registros. Pido los **permisos y fechas de modificación** de las carpetas del render. | **No activo auditoría nueva** sin documentarlo (alteraría evidencia). | L12, L22 · NIST §3.1.1 (nota 12) |
| **F13 NAS** | Pido que **suspendan la rotación** o copien las 14 copias existentes a otro soporte **antes de la tarea nocturna**, con hash. | No restauro nada sobre el NAS. | L15, L22, L24 · NIST §3.1.2; RFC §3.2 |
| **F14, F15 Red y cortafuegos** | Pido a Bahía que **exporte ya** los registros de conexión y VPN, ARP y DHCP desde la fecha más antigua disponible (formato original, con hash), y **amplíe temporalmente la retención**. | No reiniciar ni actualizar el cortafuegos. | L15, L22, L24 · NIST §3.1.2; RFC §2.1, §3.2 |
| **F16, F17 Nube** | Pido a Bahía o a Elena (administrador) **por escrito**, en este orden: **1)** **exportar ya** (CSV o JSON) los registros de **inicio de sesión y auditoría de Entra ID** de Marta, que son los que antes caducan (7 o 30 días según la edición); **2)** **exportar** la **auditoría de Microsoft 365** (OneDrive y correo: descargas, comparticiones, reglas de reenvío) desde el 6 de marzo o la fecha más antigua disponible; **3)** **conservar** el buzón (retención legal o *Litigation Hold*, que exige Exchange Online Plan 2, o Plan 1 con Archiving) y el OneDrive de Marta (política de retención); si la licencia no lo permite, hacer una **copia exportada** de ambos y decírmelo; **4)** si Elena lo decide, **deshabilitar la cuenta y revocar sus sesiones** (en ese orden), sabiendo que los accesos ya concedidos pueden seguir hasta ~1 hora; **5)** **no borrar ni dar de baja** la cuenta, el buzón ni la licencia por la excedencia; **6)** localizar la **clave BitLocker** (viendo la clave queda un registro de auditoría), **sin rotarla** (ni con la política de rotación tras uso ni con la acción de rotación de Intune). | No se restablecen contraseñas ni se eliminan cuentas o dispositivos. | L15, L19, L22 · NIST §3.1.1, §3.1.2; ENFSI §9.1, §9.2 |
| **F18 Bahía** | Se le pide todo **por escrito**, con detalle y plazos, y se le trata como **tercero de confianza**: actúa bajo mi supervisión (pantalla compartida), **registra cada acción** (quién, qué, cuándo) y **congela cambios** (actualizaciones, borrados, licencias). | No se le deja actuar sin registro. | L5, L22, L24 · ENFSI §9.2; RFC §3.2, §4.1 |
| **F19 iCloud y WhatsApp** | Pregunto a Elena quién es propietario de la cuenta y pido que **no se cierre sesión ni se borren copias**. | No inicio sesión. | L12, L14 · NIST §3.1.1 |
| **F20 Personas** | Anoto quién estaba, qué hacía y qué dice cada uno (Javier, Marta, la compañera, Elena y el técnico). | No interrogo. | L4 · RFC §3.2 |
| **Todas** | Cadena de custodia: etiqueta, hora, custodio y bolsa. Trabajo solo sobre copias verificadas con hash. | No recojo contenido ajeno al caso. | L2, L24 · RFC §2, §4.1; NIST §3.1.2 |

---

## 4. Los límites

*(L23: qué no puedo tocar, o todavía no, por qué y qué hago en su lugar.)*

| No puedo tocar… | Por qué | Qué hago en su lugar | Punto |
| :-- | :-- | :-- | :-- |
| **Móvil personal y bolso de Marta; su casa y equipos personales** | Son propiedad privada. La autorización de Elena cubre **activos de la empresa**, no pertenencias de Marta. | Pido consentimiento por escrito. Si lo rechaza, queda anotado y, si procede, lo decide un asesor legal o una autoridad. Mientras tanto, el móvil queda a la vista y fotografiado. | L1, L14, L23 · RFC §2.3, §2.4; NIST §3.1.1 |
| **Retener a Marta** | No tengo autoridad para ello. | Elena le indica que no use sistemas de la empresa y que no se lleve material del estudio. | L3, L23 · ENFSI §8.2 |
| **Grabador de conserjería** | Es de la comunidad, no de Almadraba. | Petición formal de Elena por escrito; si hay negativa, requerimiento por vía legal. | L11, L14, L23 · NIST §3.1.1, §3.1.2 |
| **La sesión de otra compañera** | Es una cuenta ajena: puede haber datos personales de terceros y no debo actuar como ella. | Su consentimiento y que Bahía extraiga los registros de acceso. | L14, L23 · RFC §2.3; NIST §3.1.2 |
| **Contenido del portátil bloqueado** | No tengo credenciales y **no se las pido a Marta** (podría borrar). | Credenciales de administración o clave BitLocker vía Bahía. Si no llegan, solo documento y mantengo el equipo vivo y alimentado. | L19, L23 · RFC §2.2; ENFSI §9.2 |
| **Servidor, NAS, cortafuegos, portal Microsoft, impresora** | No tengo credenciales y dependo de Bahía. | Peticiones por escrito y supervisadas, con registro de acciones. | L5, L22, L23 · ENFSI §9.2; NIST §3.1.1 |
| **Apagar, reiniciar o desenchufar el portátil o el dock** | Perdería memoria viva y la clave de cifrado en uso, y la alimentación. | Mantenerlo encendido y alimentado hasta poder adquirir. | L19, L20 · RFC §2.2; ENFSI §8.2, §9.2 |
| **Registros de terceros (proveedor de internet; Microsoft como empresa)** | Los de un proveedor de internet suelen requerir orden judicial (NIST §3.1.1), y lo que Microsoft guarde y no sea visible para el administrador del inquilino tampoco lo puedo pedir yo. | Solo lo que el administrador de Almadraba pueda exportar de su propio inquilino; el resto, vía legal. | L23 · NIST §3.1.1, §3.1.2 |
| **Mantener todo vivo indefinidamente** | La batería y la operativa del estudio tienen límite. | Fijo con Elena una **ventana corta** para adquirir RAM y disco, y valoro el coste para la actividad. | L20 · NIST §3.1.3; ENFSI §8.2 |

---

## 5. De dónde sale cada decisión

| Decisión del plan | Punto de la lista | Norma y apartado |
| :-- | :-- | :-- |
| Autorización de Elena y límite en lo personal | L1, L23 | RFC 3227 §2.3, §2.4 · NIST §3.1.1 · ENFSI §8.2 |
| Custodio, cuaderno, hora local y UTC | L2 | RFC 3227 §2, §3.2 · NIST §3.1.2 |
| Apartar a Marta y su móvil de los equipos | L3 | ENFSI §8.2 · NIST §3.1.3 |
| Declaraciones de Marta, Javier y la compañera | L4 | RFC 3227 §3.2 · NIST §3.1.3 |
| Identificar a Bahía, pedirle acciones por escrito y supervisarlo | L5, L22 | NIST §3.1.1 · ENFSI §9.2 · RFC 3227 §3.2 |
| Fotografías y croquis antes de tocar | L7 | ENFSI §8.2 · NIST §3.1.2 |
| Estado del portátil y del dock (alimentación y red) | L8 | ENFSI §8.2, §9.2 · RFC 3227 §3.2 |
| Inventario de la mesa, de lo oculto y de lo compartido | L9, L10, L11 | NIST §3.1.1 · RFC 3227 §3.2 · ENFSI §8.2, §9.2 |
| Servidor, NAS, red, nube, VPN y casa | L12, L13 | NIST §3.1.1 · RFC 3227 §2.1 · ENFSI §9.2 |
| Propietario de cada fuente y petición formal a la finca | L14 | NIST §3.1.1 · RFC 3227 §2.3 |
| Prioridad por caducidad (cortafuegos, cámara, copias, nube) | L15, L16, L17 | NIST §3.1.2 · RFC 3227 §2.1 |
| Orden: control de personas y RAM antes que el resto | L3, L16 | ENFSI §8.2 · RFC 3227 §2.1 |
| Paralelo entre fuentes, paso a paso en el portátil | L18 | RFC 3227 §2 |
| No apagar el portátil; localizar la clave BitLocker | L19 | RFC 3227 §2.2 · ENFSI §9.1, §9.2 |
| No cortar cables ni dock; bloquear en red y nube | L20 | RFC 3227 §2, §2.2 · NIST §3.1.3 · ENFSI §8.2 |
| Modo avión o Faraday con alimentación para el iPhone | L21 | ENFSI §8.2, §9.2 |
| Consentimiento y alternativas para lo que no puedo tocar | L23 | RFC 3227 §2.3, §2.4 · NIST §3.1.1, §3.1.2 · ENFSI §8.2 |
| Etiquetado, hash, copias y cadena de custodia | L24 | RFC 3227 §2, §3.2, §4.1 · NIST §3.1.2 · ENFSI §8.2 |
