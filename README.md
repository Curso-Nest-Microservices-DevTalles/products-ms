# 🛍️ Products Microservice

Un microservicio para la gestión de productos construido con NestJS, Prisma y SQLite.

## 📋 Características

- ✅ CRUD completo de productos
- ✅ Paginación avanzada
- ✅ Validación de datos con class-validator
- ✅ Soft delete (eliminación lógica)
- ✅ Arquitectura de microservicios
- ✅ Base de datos SQLite con Prisma ORM
- ✅ Logging estructurado
- ✅ Manejo robusto de errores

## 🚀 Tecnologías

- **Framework**: NestJS
- **ORM**: Prisma
- **Base de datos**: SQLite
- **Validación**: class-validator & class-transformer
- **Microservicios**: NestJS Microservices

```

## 🛠️ Instalación y Configuración

### Prerrequisitos

- Node.js (v18 o superior)
- SQLite
- npm o yarn

### 1. Clonar el repositorio

```bash
git clone https://github.com/Curso-Nest-Microservices-DevTalles/products-ms.git
cd products-ms
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Configurar variables de entorno

Crear un archivo `.env` basado en `env.template`:

```bash
cp env.template .env
```

Configurar las variables en `.env`:

```env
# Database
DATABASE_URL="postgresql://username:password@localhost:5432/products_db"

# Application
PORT=3000
```