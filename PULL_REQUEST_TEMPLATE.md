<!-- 🎯 Título del PR — formato obligatorio:
     [EQUIPO-1234] Descripción breve en inglés
     Ejemplo: [WAL-1234] Add CBU alias validation on extraction
-->

## 🎫 Jira
<!-- https://jira-iol.atlassian.net/browse/EQUIPO-XXXX -->

## 📋 Qué hace este cambio
<!-- Descripción breve del cambio y su motivación -->

## 🧪 Cómo probarlo
<!-- Pasos para reproducir y validar el comportamiento en HOMO -->

## 📸 Evidencia de pruebas
<!-- Obligatorio. Demostrá que validaste el comportamiento antes de abrir este PR.
     Ejemplos aceptados:
     - cURL con request y response
     - Captura de pantalla del comportamiento en HOMO
     - Output de tests automatizados
     - Log relevante que confirme el flujo correcto
-->

## ✅ Checklist
- [ ] Build compila correctamente
- [ ] Validado en ambiente bajo desde el branch antes de abrir este PR
- [ ] Evidencia de pruebas adjunta en este PR
- [ ] OpenAPI actualizado y verificable en Scalar / Swagger en HOMO (si el cambio impacta endpoints)
- [ ] Tests agregados o actualizados (si aplica)
- [ ] README y `/docs` actualizados si el cambio afecta funcionalidad, configuración o arquitectura (si aplica)

## 📡 Observabilidad
- [ ] Sin debug logs — logs de negocio y error con el nivel correcto (si aplica)
- [ ] Métricas agregadas o actualizadas (si aplica)
- [ ] Healthcheck actualizado si se agregó una nueva dependencia (si aplica)

## 🚀 Consideraciones de deploy
- [ ] Requiere migración o cambio en base de datos
- [ ] Requiere actualizar variables de entorno
- [ ] Requiere coordinación con otros equipos
