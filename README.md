# OWASP Juice Shop — Actividad Final Momento 3
## Seguridad Informática — Universidad Cooperativa de Colombia

---

## Datos del Equipo

| Campo | Detalle |
|---|---|
| **Programa** | Ingeniería de Software |
| **Asignatura** | Seguridad Informática |
| **Docente** | Mg. Gustavo Sánchez Rodríguez |
| **Integrante 1** | [Nelson Barrera] — Código: [835109] |
| **Integrante 2** | [Jhon Fredy Moran] — Código: [826720] |
| **Repositorio base** | https://github.com/guswill24/juice-shop |

---

## ¿Qué es este repositorio?

Este repositorio es un fork del proyecto **OWASP Juice Shop**, una aplicación web deliberadamente insegura diseñada para practicar técnicas de auditoría y seguridad ofensiva. El fork fue realizado como parte de la Actividad Final del curso de Seguridad Informática.

Se realizaron modificaciones al frontend para mostrar los datos personales de los integrantes de la bina, y se documentaron **45 retos resueltos** distribuidos entre los niveles 1 y 6.

---

## Cómo ejecutar el proyecto localmente

### Requisitos previos

- Node.js v18 o superior
- npm v8 o superior
- Git

### Pasos de instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/[tu-usuario]/juice-shop.git

# 2. Entrar al directorio
cd juice-shop

# 3. Instalar dependencias
npm install

# 4. Iniciar la aplicación
npm start

# 5. Abrir en el navegador
http://localhost:3000
```

### Verificar que funciona

- Página principal: http://localhost:3000
- Score Board: http://localhost:3000/#/score-board

---

## Modificaciones realizadas

Se modificó el componente principal del frontend para mostrar los datos personales de los integrantes de la bina directamente en la interfaz de la aplicación.

**Archivo modificado:** `frontend/src/app/app.component.html` (o el archivo correspondiente según la versión)

**Datos agregados:**
- Nombre completo de cada integrante
- Código estudiantil
- Programa: Ingeniería de Software
- Asignatura: Seguridad Informática

---

## Retos resueltos

Se resolvieron y documentaron **45 retos** en total, distribuidos así:

| Nivel | Estrellas | Cantidad de retos |
|---|---|---|
| Nivel 1 | 1 estrella | 14 retos |
| Nivel 2 | 2 estrellas | 15 retos |
| Nivel 3 | 3 estrellas | 4 retos |
| Nivel 4 | 4 estrellas | 4 retos |
| Nivel 5 | 5 estrellas | 4 retos |
| Nivel 6 | 6 estrellas | 4 retos |
| **Total** | | **45 retos** |

La documentación completa de cada reto (descripción, técnica, herramientas, pasos y análisis) se encuentra en el informe Word entregado junto a este repositorio.

### Lista de retos resueltos

**Nivel 1:** Score Board, Privacy Policy, DOM XSS, Bonus Payload, Bully Chatbot, Confidential Document, Exposed Metrics, Missing Encoding, Repetitive Registration, Error Handling, Mass Dispel, Outdated Allowlist, Web3 Sandbox, Zero Stars

**Nivel 2:** Login MC SafeSearch, Login Admin, Password Strength, Reflected XSS, Admin Section, View Basket, Deprecated Interface, Empty User Registration, Five-Star Feedback, NFT Takeover, Visual Geo Stalking, Meta Geo Stalking, Exposed Credentials, Weird Crypto, Password Hash Leak, Security Policy

**Nivel 3:** Login Bender, Login Amy, Privacy Policy Inspection, Forged Review

**Nivel 4:** Vulnerable Library, Easter Egg, Nested Easter Egg, Poison Null Byte

**Nivel 5:** Unsigned JWT, Change Bender's Password, Email Leak, Extra Language

**Nivel 6:** Arbitrary File Write, Forged Coupon, Premium Paywall, SSRF

---

## Herramientas utilizadas

- **Burp Suite** — Interceptación y modificación de peticiones HTTP
- **OWASP Juice Shop** — Aplicación objetivo de las pruebas
- **Navegador web con DevTools** — Análisis de código fuente JavaScript
- **jwt.io** — Análisis y falsificación de tokens JWT
- **metadata2go.com** — Extracción de metadatos EXIF de imágenes
- **Python 3 + PyCryptodome** — Descifrado AES y creación de ZIPs maliciosos
- **CyberChef** — Decodificación y análisis criptográfico

---

## Vulnerabilidades OWASP cubiertas

- A01:2021 — Broken Access Control
- A02:2021 — Cryptographic Failures
- A03:2021 — Injection (SQL Injection, XSS)
- A04:2021 — Insecure Design
- A05:2021 — Security Misconfiguration
- A06:2021 — Vulnerable and Outdated Components
- A07:2021 — Identification and Authentication Failures
- A10:2021 — Server-Side Request Forgery (SSRF)

---

## Advertencia

> Este repositorio es exclusivamente con fines académicos. Las técnicas documentadas fueron aplicadas únicamente sobre el entorno controlado de OWASP Juice Shop en localhost. Su uso fuera de entornos autorizados es ilegal y va en contra de la ética profesional.
