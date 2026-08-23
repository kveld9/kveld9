<h1 align="center">Kveld</h1>
<p align="center"><b>Building for Android & Linux | Systems, Privacy & Self-Hosting</b></p>

<p align="center">
  <a href="https://codeberg.org/kveld9"><img src="https://img.shields.io/badge/Codeberg-kveld9-2185d0?style=flat-square&logo=codeberg&logoColor=white" /></a>
  <a href="https://github.com/kveld9"><img src="https://img.shields.io/badge/GitHub-kveld9-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

### 💁 Sobre mí

* 🎓 **Estudios:** Actualmente cursando la carrera de Licenciatura en Sistemas en la Universidad Nacional de Lanús (UNLa).
* ⚙️ **Enfoque técnico:** Desarrollo Android nativo, ingeniería inversa de bytecode/binarios ARM64, optimizaciones a nivel kernel/OS y scripting en C/Bash.
* 🛡️ **Filosofía:** 100% FOSS, arquitectura offline-first, mitigación profunda de telemetría y soberanía de datos mediante self-hosting.

---

### 🛠️ Stack & Herramientas

#### Lenguajes & Core
<img src="https://skillicons.dev/icons?i=c,bash" />

#### 📚 Aprendiendo activamente
<img src="https://skillicons.dev/icons?i=kotlin" />

#### Desarrollo Android & Herramientas
<img src="https://skillicons.dev/icons?i=androidstudio,gradle" />

#### Sistemas Operativos & Entornos
<img src="https://skillicons.dev/icons?i=arch,ubuntu,debian,linux" />

#### Servidores, Red & Entorno
<img src="https://skillicons.dev/icons?i=docker,cloudflare,git,github,vscode" />

---

### 🚀 Proyectos Principales

#### 🔮 [kveld-morphe-patches](https://github.com/kveld9/kveld-morphe-patches) — Modular Android Bytecode & Native Patch Suite
Suite modular de parches en Kotlin para el framework **Morphe**, enfocada en reversing, debloating estricto y desbloqueo de funciones:
* **Gboard Lite:** 
  * *Privacidad & Debloat:* Supresión de Google Primes, WorkManager, Phenotype, MDD background sync, telemetría de Tenor y forzado de Incognito Mode.
  * *UI & Features:* Inyección de tema nativo Pure Black AMOLED, trackpad de cursor 2D libre en la barra espaciadora y menú rediseñado Panel V2.
  * *Bypass:* Neutralización de validación interna de firma APK.
* **Brave Browser:**
  * *Defensa en profundidad contra telemetría:* Supresión en 4 capas (recursos XML, intercepción Smali/Bytecode, DNS a `0.0.0.0` y **parcheo binario ARM64 en `libchrome.so`** mediante branches/NOPs).
  * *Origin & Rendimiento:* Mocking de licencias/tokens a nivel local y neutralización de tareas de fondo en `JobScheduler` (Job ID 105).

#### 📱 [FCMetrix](https://github.com/kveld9/FCMetrix) — Calculadora de GRL Offline & FOSS para Android
* **Arquitectura & UI:** Desarrollada en Kotlin con Jetpack Compose (Material 3), soporte para Material You y arquitectura reactiva (`Coroutines`, `Flow`, `ViewModel`).
* **Rendimiento & Persistencia:** Precompilación con **Baseline Profiles** para inicio instantáneo, persistencia local con **Room Database** y almacenamiento reactivo con **DataStore**.
* **Privacidad estricta:** 100% local/offline, cero analíticas, cero rastreadores y sin permisos innecesarios.

---

### 🖥️ Infraestructura & Servidor Casero

Servidor Debian dedicado a aislamiento de servicios, privacidad de red y sincronización continua:

* 🐳 **Contenedores:** Orquestación y despliegue modular con `Docker` y `Docker Compose`.
* 🛡️ **Filtrado DNS:** Control y bloqueo de rastreadores a nivel LAN mediante `AdGuard Home` / `Pi-hole`.
* 🔄 **Sincronización P2P:** Sincronización continua de archivos y respaldos distribuidos con `Syncthing`.
* 🌐 **Red & Automatización:** Túneles/registros automáticos con `Cloudflare` y tareas de mantenimiento programadas en `Bash`.

---

### 📦 Otras Herramientas & Contribuciones

* 🐧 **[Void Linux XBPS Templates](https://codeberg.org/kveld9):** Mantenimiento de plantillas `xbps-src` para compilar y empaquetar binarios en Void Linux (*Zen Browser, Brave, Waterfox, Betterbird, Zed, etc.*).
* 🛡️ **[PiSolid](https://github.com/kveld9/PiSolid):** Listas curadas de bloqueo de dominios para Pi-hole y AdGuard Home orientadas a frenar telemetría agresiva, malware y trackers.
* ⚙️ **[thatKernel](https://github.com/kveld9/thatKernel) / [anniVib](https://github.com/kveld9/anniVib):** Módulos Magisk/KernelSU para silenciar logs/eventos del kernel y manipular parámetros del framework.
* 🧹 **[hyperos-debloat](https://github.com/kveld9/hyperos-debloat):** Scripting avanzado para debloating profundo y erradicación de telemetría en ROMs Xiaomi/HyperOS.
