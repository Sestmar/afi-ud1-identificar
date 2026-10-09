# Lista de comprobación: identificar antes de tocar

Herramienta de trabajo para la escena. **M** = mirar · **P** = preguntar · **D** = decidir.
Cada punto indica la norma y el apartado de los que sale (**RFC** = RFC 3227 · **NIST** = SP 800-86 · **ENFSI** = ENFSI-BPM-FIT-01).

## 1. Al llegar

- [ ] **L1 · P — Autorización y alcance.** ¿Quién autoriza, por escrito, y sobre qué activos? ¿Qué es de la empresa, qué es de terceros y qué es personal? *(RFC §2.3, §2.4 · NIST §3.1.1 · ENFSI §8.2)*
- [ ] **L2 · D — Custodio y cuaderno de notas.** Una sola persona fotografía, etiqueta y anota cada acción (qué, quién, dónde, hora). Anotar la hora local y su diferencia con UTC. *(RFC §2, §3.2 · NIST §3.1.2)*
- [ ] **L3 · D — Separar a las personas de los equipos y de sus comunicaciones.** Sospechoso y testigos lejos de los dispositivos y de cualquier aparato que pueda interactuar con ellos. Controlar quién entra y sale. *(ENFSI §8.2 · NIST §3.1.3)*
- [ ] **L4 · P — Personas.** ¿Quién usa cada equipo y quién tiene acceso, contraseñas o sesiones? Anotar quién estaba, qué hacía y qué dice, con sus palabras. *(RFC §3.2 · NIST §3.1.3)*
- [ ] **L5 · P — Quién administra la informática.** ¿Hay proveedor externo? ¿Qué gestiona (red, copias, nube, VPN, portátiles) y cómo se le localiza ya? *(NIST §3.1.1 · ENFSI §9.2)*
- [ ] **L6 · M — Material propio y preparación.** ¿Llevo cámara, bolsas y etiquetas, bolsas Faraday con alimentación, herramientas en medio de solo lectura, formularios de custodia y un plan para memoria viva, cifrado vivo y reinicio remoto? *(RFC §5 · NIST §3.1.2 · ENFSI §9.1)*

## 2. Antes de tocar nada

- [ ] **L7 · M — Fotografiar y croquizar.** Puesto, cables, dock, pantallas (con la hora visible), salvapantallas, dispositivos y su posición. Anotar lo que muestre cada pantalla sin tocarla. *(ENFSI §8.2 · NIST §3.1.2)*
- [ ] **L8 · M — Estado de cada dispositivo.** ¿Encendido, bloqueado, en suspensión? ¿Cómo se alimenta? ¿Qué conexiones de red tiene (cable, Wi-Fi, radio)? ¿Se ve cifrado? *(ENFSI §8.2, §9.2 · RFC §3.2)*
- [ ] **L9 · M — Inventario de lo visible.** Portátiles, docks, discos, memorias USB, móviles de empresa y personales, bolsos y cajones: todo medio que pueda contener datos. *(NIST §3.1.1 · ENFSI §8.2)*
- [ ] **L10 · P — Inventario de lo que no está a la vista.** Memorias o discos prestados, devueltos, «rotos» o que están en casa; equipos fuera de la oficina. Preguntarse «¿qué más puede ser evidencia?». *(NIST §3.1.1 · RFC §3.2)*
- [ ] **L11 · M — Fuentes compartidas y ajenas dentro de la escena.** Equipos y sesiones compartidas, impresoras y escáneres, cámaras: ¿de quién son y dónde guardan lo que registran? *(NIST §3.1.1 · ENFSI §9.2)*
- [ ] **L12 · P — Servidores, copias, red y nube.** ¿Dónde están, qué guardan, con qué configuración de red y quién los controla? *(NIST §3.1.1 · RFC §2.1 · ENFSI §9.2)*
- [ ] **L13 · P — Trabajo remoto.** ¿Se usa el equipo fuera de la oficina? ¿VPN, equipos o cuentas en casa? *(NIST §3.1.1 · ENFSI §9.2)*
- [ ] **L14 · P — Propietario de cada fuente.** Para cada una, ¿de quién es y quién puede dar acceso o autorizarlo? *(NIST §3.1.1 · RFC §2.3)*
- [ ] **L15 · P — ¿Qué caduca y cuándo?** Retención de registros, grabaciones, copias, sesiones e historiales. *(NIST §3.1.2 · RFC §2.1)*

## 3. Al decidir qué se adquiere y en qué orden

- [ ] **L16 · D — Orden según lo que antes se pierde.** Volatilidad clásica (RAM, estado de red), **y también** lo que se sobrescribe, rota o caduca. Para cada sistema, su orden de volatilidad. *(RFC §2.1, §3.2 · NIST §3.1.2)*
- [ ] **L17 · D — Valor y esfuerzo.** Estimar el valor probable de cada fuente y el esfuerzo de obtenerla: lo que depende de terceros se pide primero. Buscar donde es más probable que haya prueba. *(NIST §3.1.2 · ENFSI §8.2)*
- [ ] **L18 · D — Paralelo entre fuentes, paso a paso en cada sistema.** Lanzar las peticiones a terceros mientras se trabaja en un equipo; en un mismo sistema, un paso cada vez. *(RFC §2)*
- [ ] **L19 · D — Qué no se apaga.** Antes de apagar o reiniciar, ¿se pierden memoria viva, claves de cifrado o datos? Si apagar destruye los datos relevantes, no se apaga. *(RFC §2.2 · ENFSI §9.1, §9.2)*
- [ ] **L20 · D — Aislar sin destruir.** Cortar vías externas de cambio sin provocar un borrado («deadman») ni agotar la batería; sopesar el coste para la actividad. *(RFC §2, §2.2 · NIST §3.1.3 · ENFSI §8.2)*
- [ ] **L21 · D — Móviles y dispositivos de comunicación.** Aislarlos de la red manteniéndolos alimentados, sin apagarlos ni conectarlos a un ordenador. *(ENFSI §8.2, §9.2)*
- [ ] **L22 · D — Pedir a terceros, por escrito y con detalle.** Qué conservar, desde cuándo, en qué formato y con qué verificación; si extrae un tercero de confianza, supervisarlo y documentar cada acción. *(NIST §3.1.1 · ENFSI §9.2 · RFC §3.2)*
- [ ] **L23 · D — Qué no puedo tocar, o todavía no.** Propiedad ajena, datos personales, falta de credenciales o de autorización. Decidir la alternativa: consentimiento, petición formal, asesor legal o fuerzas de seguridad, fuente alternativa. *(RFC §2.3, §2.4 · NIST §3.1.1, §3.1.2 · ENFSI §8.2)*
- [ ] **L24 · D — Custodia y registro.** Etiquetar, cadena de custodia, copias con verificación (hash) y trabajo solo sobre copias; no recoger de más lo ajeno al caso. Dejar anotado qué queda pendiente. *(RFC §2, §3.2, §4.1 · NIST §3.1.2 · ENFSI §8.2)*
