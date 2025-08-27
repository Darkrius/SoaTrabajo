# Monorepo - Plataforma de Microservicios


## 🌿 Estrategia de Ramas

- **master** → Rama estable, siempre desplegable.  
- **develop** → Rama de integración, donde se combinan las features antes de pasar a `main`.  
- **feature/** → Ramas para nuevas funcionalidades. Ejemplo:
  - `feature/auth-login`
---

## ✅ Convenciones de Commits (Conventional Commits)


- `feat:` → Nueva funcionalidad  
- `fix:` → Corrección de bug  
- `docs:` → Cambios en la documentación  
- `style:` → Cambios de formato (espacios, comas, etc.)  
- `refactor:` → Refactorización de código sin cambiar funcionalidad  
- `test:` → Añadir o modificar pruebas  
- `chore:` → Cambios en el build, dependencias o configuraciones  

Ejemplo:

feat(auth): agregar endpoint de login con JWT
fix(user): corregir validación de correo en registro



## 🔐 Protección de Ramas

- `main` → protegido, **no se permite push directo**.  
- `develop` → protegido, cambios solo vía **Pull Request**.  
- `feature/*` → libres para cada desarrollador.  
