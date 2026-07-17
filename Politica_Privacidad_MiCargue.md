# Política de Privacidad de MiCargue

**Última actualización:** 17 de Julio de 2026

En **MiCargue**, respetamos su privacidad y estamos plenamente comprometidos a proteger los datos personales de nuestros usuarios. Esta Política de Privacidad cumple con las regulaciones y requerimientos de la **Google Play Store** y describe detalladamente cómo recopilamos, utilizamos, almacenamos, protegemos y eliminamos su información cuando utiliza nuestra aplicación móvil (Android/iOS) y plataforma web.

> [!IMPORTANT]
> Al descargar, acceder o utilizar MiCargue, usted acepta las prácticas de manejo de información descritas en esta Política de Privacidad. Si no está de acuerdo con alguna parte de esta política, le pedimos abstenerse de utilizar la aplicación.

---

## 1. Información que Recopilamos

Para brindar los servicios logísticos, de escaneo de guías y administración de rutas, recopilamos los siguientes tipos de información:

### A. Información Personal y de Registro (Proporcionada por el Usuario o Empresa)
- **Datos de identificación de cuenta:** Nombre completo, dirección de correo electrónico (`email`), teléfono de contacto y contraseña encriptada.
- **Datos empresariales y logísticos:** Nombre de la empresa (`companyName`), número de licencia de software y listado de rutas asignadas.

### B. Permisos del Dispositivo e Información Recopilada Automáticamente
Para el correcto funcionamiento de la aplicación móvil en Google Play, solicitamos los siguientes permisos específicos:

- **Cámara (`CAMERA`):** Requerimos acceso a la cámara **estrictamente y en tiempo real para la lectura y escaneo óptico de códigos de barras** (códigos QR, EAN-13, PDF417, Code 128) de los paquetes y guías en las planillas de cargue (`PAMI`, `Mensajero`, `Apoyo`). **No** tomamos fotografías personales, **no** grabamos video en segundo plano ni almacenamos o enviamos archivos de imagen de la cámara a servidores externos.
- **Datos de Ubicación (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`):** Si el servicio o la empresa habilita el registro georreferenciado, recopilamos coordenadas GPS de forma temporal y exclusiva durante las jornadas de cargue para vincular la ubicación exacta del escaneo con la guía de despacho. No rastreamos la ubicación en segundo plano cuando el usuario cierra sesión o termina su jornada.
- **Autenticación Biométrica (`USE_BIOMETRIC` / `USE_FINGERPRINT`):** Si el usuario activa el inicio de sesión rápido (Huella Dactilar o Reconocimiento Facial), la validación la realiza de manera 100% local el hardware y el sistema operativo (Android Keystore / iOS Keychain). **MiCargue nunca recolecta, transmite, ni almacena datos biométricos** en sus servidores ni bases de datos en la nube.
- **Almacenamiento Local Seguro:** Guardamos el token de sesión (`JWT`) y un historial local temporal de escaneos offline utilizando *SecureStore / AsyncStorage* en el dispositivo, para permitir la sincronización cuando se recupere la conexión a Internet.

---

## 2. Cómo y Para Qué Utilizamos su Información

Usamos sus datos únicamente para la operativa y seguridad del sistema logístico:
1. **Autenticación y Sesión:** Validar el acceso de conductores y administradores a sus respectivas cuentas de empresa.
2. **Operación del Escáner:** Registrar qué usuario (conductor/operario) escanea cada paquete en tiempo real para generar auditorías de cargue y planillas confiables.
3. **Sincronización Offline:** Guardar temporalmente las lecturas cuando no hay señal móvil para sincronizarlas con el backend en la nube en cuanto haya internet disponible.
4. **Soporte Técnico:** Atender consultas, reportes de fallos y solicitudes de asistencia mediante canales oficiales (Correo electrónico y WhatsApp).

---

## 3. Compartir y Divulgación de Datos (No Venta de Datos)

> [!NOTE]
> **MiCargue NO vende, NO alquila y NO comercializa información personal, datos de ubicación ni registros logísticos a terceros.**

Solo podemos compartir datos bajo los siguientes supuestos estrictos:
- **Con el Administrador de su Empresa:** Los registros de escaneo, códigos de guías y usuario que los escaneó se reflejan en el panel de control del administrador (`MasterAdmin` / Ajustes de Empresa) al que usted pertenece.
- **Servicios de Infraestructura Cloud:** Los datos se almacenan en servidores seguros (Backend en la nube y bases de datos relacionales seguras) que actúan únicamente como procesadores bajo estrictas normas de confidencialidad.
- **Requerimientos Legales:** Si una autoridad judicial o gubernamental competente exige legalmente la información en el marco de una investigación legal formal.

---

## 4. Seguridad de los Datos (Cifrado y Protección)

- **Cifrado en Tránsito (`HTTPS / TLS 1.3`):** Toda la comunicación y transmisión de datos entre la aplicación móvil MiCargue en el dispositivo Android/iOS y nuestros servidores se realiza mediante protocolos seguros cifrados (`SSL/TLS`).
- **Cifrado en Reposo:** Las contraseñas se almacenan mediante algoritmos de hash seguros (`BCrypt`) y los tokens locales se resguardan en el almacenamiento seguro del sistema operativo.

---

## 5. Eliminación de Cuenta y de Datos Personales (Requisito Obligatorio Google Play)

De conformidad con las políticas de **Seguridad de Datos de Google Play**, los usuarios tienen derecho a solicitar en cualquier momento la **eliminación total de su cuenta y de todos sus datos personales** asociados en MiCargue.

### A. Cómo solicitar la eliminación de cuenta:
1. **Directamente en la aplicación o por correo electrónico:** Puede enviar una solicitud de eliminación de cuenta y datos al correo oficial de soporte técnico: **`jairogil4523@gmail.com`** con el asunto **"Solicitud de Eliminación de Cuenta MiCargue"** especificando el correo electrónico de su cuenta.
2. **Tiempo de procesamiento:** La solicitud se procesará y completará en un plazo máximo de **3 a 5 días hábiles**.

### B. Qué datos se eliminan:
Al procesar la eliminación de su cuenta, se borrarán de manera definitiva de nuestras bases de datos activas:
- Su nombre completo, correo electrónico, número de teléfono y credenciales de acceso (`password hash`).
- Su vinculación como conductor o usuario del sistema.
- Los tokens locales y sesiones activas.

*(Nota: Los registros históricos anónimos de códigos de barras escaneados e identificadores logísticos que ya formen parte de cierres de planillas auditados por la empresa podrán mantenerse únicamente por fines contables y de auditoría de la compañía, sin estar vinculados a su información personal identificable).*

---

## 6. Retención de Información

Conservamos su información mientras su cuenta o licencia de empresa se encuentre activa para prestarle el servicio logístico. Si una licencia expira o si un usuario solicita su baja, eliminamos o anonimizamos los datos personales de acuerdo con las normativas legales vigentes.

---

## 7. Permisos de Menores

MiCargue es una herramienta empresarial de logística y transporte para conductores profesionales y personal administrativo. La aplicación no está dirigida, ni recopila deliberadamente datos personales de menores de 18 años.

---

## 8. Cambios a esta Política de Privacidad

Nos reservamos el derecho de modificar esta Política de Privacidad cuando sea necesario para adaptarnos a nuevas directrices de Google Play o mejoras operativas. Notificaremos cualquier actualización importante dentro de la aplicación o actualizando la fecha al inicio de este documento.

---

## 9. Contacto y Soporte Oficial

Si tiene preguntas sobre esta Política de Privacidad, los permisos de la aplicación o la gestión de sus datos, contáctenos de inmediato en:
- **Responsable:** Equipo de Soporte Técnico y Seguridad MiCargue
- **Correo Electrónico:** `jairogil4523@gmail.com`
- **Teléfono / WhatsApp:** `+57 320 532 7740`
- **Plataforma:** `MiCargue`
