# Comparativa de las tres normas

Apartados leídos: **RFC 3227** §2 y §3 · **NIST SP 800-86** §3.1 · **ENFSI-BPM-FIT-01** §8.2, §9.1 y §9.2.

| | **RFC 3227** | **NIST SP 800-86** | **ENFSI-BPM-FIT-01** |
| :--- | :--- | :--- | :--- |
| **Qué entiende por identificar** | Primer paso de la recogida: listar los sistemas implicados y seguir preguntándose «qué más puede ser evidencia», incluidas las personas presentes (§3.2). | Primer paso de todo el proceso forense: reconocer fuentes en el espacio físico y **en otros lugares y de otros propietarios** (§3.1.1). | Primera actividad en la escena, incluidas **configuraciones de dispositivos y de red** (§9.2); búsqueda sistemática y registrada con fotos y croquis (§8.2). |
| **Fuentes de evidencia que menciona** | Registros y caché, tabla de rutas, ARP, procesos, memoria, ficheros temporales, disco, **registros remotos**, topología de red y medios de archivo (§2.1). | Equipos, servidores, almacenamiento en red, **medios externos y móviles**, registros de red y de aplicaciones, **registros de terceros**, equipos personales y **teletrabajo** (§3.1.1). | Dispositivos y red (§9.2), **memoria y cifrado en vivo**, reinicio remoto (§9.1), equipos con radiofrecuencia (§8.2) y **administrador como tercero de confianza** (§9.2). |
| **Criterio para decidir qué se protege primero** | **Orden de volatilidad**: de lo más volátil (registros, caché, memoria) a lo menos (disco, medios de archivo) (§2.1). | **Valor probable, volatilidad y esfuerzo**; incluye los registros que se sobrescriben (§3.1.2). | **Probabilidad de contener prueba** según lo alegado (§8.2) y **no apagar si apagar destruye los datos** (§9.2). |

## En qué coinciden

- **Preservar antes que analizar:** alterar lo mínimo y documentarlo todo, con notas, fotografías y cadena de custodia (RFC §2, §3.2; NIST §3.1.2; ENFSI §8.2).
- **Lo volátil va primero:** orden de volatilidad en la RFC, factor *volatilidad* en NIST y memoria y cifrado en vivo en ENFSI (§9.1).
- **No apagar a ciegas:** lo dicen la RFC (§2.2) y ENFSI (§9.2). NIST lo trata como una decisión de contención que hay que sopesar (§3.1.3).

## En qué se diferencian

- **La RFC mira dentro del equipo vivo.** Solo ella avisa de que desconectar la red puede activar interruptores «deadman» que borran pruebas (§2.2), y de la diferencia entre el reloj del sistema y UTC (§2).
- **NIST mira hacia fuera.** Es la única que obliga a preguntarse de quién es cada fuente, y la que añade valor y esfuerzo al criterio de prioridad. Sin ella, el inventario se quedaría en lo que hay sobre la mesa.
- **ENFSI mira la escena física.** Aporta separar a las personas de los equipos y de sus comunicaciones, y controlar la batería al aislar por radiofrecuencia (§8.2).
- **Tensión sobre aislar un equipo:** NIST propone desconectar cables (§3.1.3), la RFC avisa de que eso puede borrar pruebas (§2.2) y ENFSI de que puede agotar la batería (§8.2). Con una sola norma se aplicaría la medida sin ver su riesgo.
- **Qué se protege primero** depende del enfoque: volatilidad en la RFC, valor, volatilidad y esfuerzo en NIST, y probabilidad de contener prueba en ENFSI. Leídas juntas, recuerdan que **no solo la RAM caduca**: también los registros que se sobrescriben, las copias que rotan y las grabaciones que se borran.
