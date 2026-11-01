# PotitoEconomyProbe 0.1 — código fuente experimental

**No es un .jar instalable**. Compilar con Gradle + Java 21 (`gradle build`) y API Paper 1.21.1; no ha sido compilado ni probado en Arclight. El acceso a clases Fabric desde Bukkit podría fallar. No registra economía Vault ni altera saldos.

**Atención:** el método `getServer` y la búsqueda de firma del método ofuscado son hipótesis para validar en el entorno Arclight; pueden requerir ajustes según el mapeo y cargadores de clases. No usar en producción sin probar en copia del servidor.

Tras compilar e instalar en servidor de prueba: `/potitoeco estado`, `/potitoeco saldo` (OP). Si falla, enviar el error completo de consola. No instalar en producción todavía.
