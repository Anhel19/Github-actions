# Github Actions - Pipeline CI/CD

Este es un proyecto de ejemplo para demostrar un pipeline completo de CI/CD usando GitHub Actions.

## 📋 Descripción

- **CI.yml**: Se ejecuta en PRs hacia `develop` - valida cambios y actualiza README
- **CD.yml**: Se ejecuta en pushes a `main` - bumpa versión y valida producción

## 🚀 Setup

1. Clonar el repositorio
2. Crear rama `develop`
3. Configurar secrets (DEV_TOKEN, PROD_TOKEN)
4. Registrar self-hosted runner

## 📝 Versión

AppVersion-0
