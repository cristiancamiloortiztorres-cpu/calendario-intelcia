# 📅 Calendario de Permisos Intelcia

Sistema colaborativo de gestión de permisos, vacaciones y días off para Intelcia Distribution.

## ✨ Características

- ✅ Calendario visual interactivo
- ✅ Gestión de permisos (Aceptado/Rechazado/Tentativo)
- ✅ Panel de alertas para permisos pendientes
- ✅ Estadísticas por mes
- ✅ Filtros por equipo
- ✅ Responsive (funciona en móvil)
- ✅ Paleta de colores Intelcia
- ✅ Datos guardados localmente

---

## 🚀 Cómo Acceder

Una vez publicado en Vercel, el calendario estará disponible en:

```
https://calendario-intelcia.vercel.app
```

### Acceso para Líderes

Todos los líderes pueden acceder directamente con este link. No requiere login.

**Usuarios con acceso:**
- Camilo Ortiz (Jefe de Operaciones)
- Jenny Katherine (Gerente)
- Arbey Alexander Rodriguez (Coordinador Bizrisk)
- Laura Camila Diaz (Coordinadora CPV/PG)
- Jefferson David Salcedo (Coordinador M2A)

---

## 🔧 Instalación Local (Opcional)

Si quieres probar antes de publicar:

1. Descarga `calendario-permisos-intelcia.html`
2. Abre el archivo en tu navegador
3. ¡Listo! Funciona sin internet

---

## 📝 Cómo Usar

### Para Crear un Permiso
1. Abre el calendario
2. Haz clic en una fecha
3. Completa el formulario
4. Haz clic en "Guardar Permiso"

### Para Editar
1. Haz clic en un permiso en el calendario
2. Haz clic en "Editar"
3. Modifica los datos
4. Guarda

### Para Filtrar por Equipo
1. En el panel lateral, selecciona el equipo
2. El calendario se actualiza automáticamente

---

## 📊 Datos

Los datos se guardan en **localStorage del navegador**:
- Cada navegador/dispositivo tiene sus propios datos
- Si limpias el historial, se pierden los datos
- Los datos NO se sincronizan entre dispositivos

**Nota:** Para una versión con sincronización en tiempo real, necesitaríamos integrar una base de datos (Firebase, etc.)

---

## 🎨 Colores

**Por Tipo de Permiso:**
- 🔵 **Vacaciones** = Azul Cyan
- 🟠 **Día Off** = Naranja
- 🟣 **Cita Médica** = Púrpura
- 🟢 **Terapia** = Menta
- 🔴 **Calamidad** = Rosa
- 🟡 **Otro** = Amarillo

**Por Estado:**
- ✅ **Verde** = Aceptado
- ❌ **Rojo** = Rechazado
- ⏳ **Amarillo** = Tentativo

---

## 📧 Formato de Solicitud (Para Empleados)

Los empleados deben enviar correos así:

```
ASUNTO: SOLICITUD PERMISO - [NOMBRE COMPLETO] - [MOTIVO]

CUERPO:
Fecha(s) solicitada(s): DD/MM/YYYY o DD/MM/YYYY al DD/MM/YYYY

Día completo / Parcial
Si es PARCIAL especifica: De HH:MM Hasta HH:MM

Motivo: [Cita médica / Terapia / Vacaciones / Calamidad doméstica / Otro]

Observaciones (opcional): [Aquí puedes escribir notas]
```

Ver `comunicado-nuevo-proceso-permisos.html` para detalles completos.

---

## 🔐 Seguridad & Privacidad

- ✅ Sin servidor (datos privados en cada navegador)
- ✅ Sin almacenamiento externo de datos personales
- ✅ Link público pero sin autenticación
- ⚠️ Para mayor seguridad, considera agregar autenticación OAuth con Google

---

## 🛠️ Próximos Pasos (Opcionales)

1. **Integración Gmail** - Detectar correos automáticamente
2. **Firebase** - Sincronizar datos entre dispositivos
3. **Autenticación** - Solo @intelcia.com pueden acceder
4. **Notificaciones** - Alertas por email
5. **Dashboard** - Reportes avanzados

---

## 📞 Soporte

Para cambios o ajustes, contacta a:
**Camilo Ortiz** - camilo.ortiz@intelcia.com

---

**Versión:** 1.0  
**Última actualización:** Agosto 2026  
**Estado:** ✅ Funcional