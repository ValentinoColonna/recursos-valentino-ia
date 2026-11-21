# WIFI · El mensaje para que Claude revise tu wifi · Valentino IA

**Qué necesitás:**
- Claude Code, que viene con cualquier plan pago de Claude;
- una Mac. El pedido está probado en Mac; en Windows no.

**Qué hace:** no cambia nada sin preguntarte. Usa solo comandos que no piden contraseña de administrador.

Abrí Claude Code, completá tus megas y pegá esto:

```
Sos técnico de redes. Quiero saber por qué el wifi de esta Mac anda más lento de lo que pago (mi plan es de __ megas). Usá solo comandos que no pidan contraseña de administrador (nada de sudo, ni airport, ni wdutil).
1. Corré networkQuality -s y decime la bajada, la subida y la capacidad de respuesta.
2. Con system_profiler SPAirPortDataType, fijate si estoy en 2,4 o en 5 GHz, en qué canal y con qué señal.
3. Con nettop -P -L 2 -d, decime qué apps están usando la red ahora.
4. Con el mismo system_profiler, contá cuántas redes vecinas hay en mi canal. Los nombres pueden salir ocultos, no hacen falta.
No cambies nada sin preguntarme. Al final, dame las tres causas más probables, ordenadas, y qué hago con cada una.
```

Si la causa es la empresa, llamala con estos números en la mano.

*Valentino IA*
