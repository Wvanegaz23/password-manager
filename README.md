# 🔐 Gestor de Contraseñas en Python

![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

Un gestor de contraseñas educativo construido en Python que implementa cifrado robusto y mejores prácticas de seguridad.

## ⚠️ Disclaimer

**Este proyecto es con fines educativos únicamente.** Para uso en producción, utiliza gestores de contraseñas establecidos y auditados como Bitwarden, 1Password o KeePass.

## ✨ Características

- 🔒 Cifrado AES-128 mediante Fernet
- 🔑 Derivación de clave con PBKDF2-HMAC (100,000 iteraciones)
- 🎲 Generador de contraseñas seguras
- 💾 Almacenamiento local cifrado
- 🛡️ Salt único por bóveda
- 👁️ Entrada de contraseñas oculta

## 🎯 Objetivo del Proyecto

Este proyecto fue desarrollado para aprender y demostrar:
- Implementación de criptografía en Python
- Manejo seguro de datos sensibles
- Buenas prácticas en desarrollo de software de seguridad
- Arquitectura de aplicaciones CLI

## 🚀 Instalación

\`\`\`bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/password-manager.git
cd password-manager

# Instalar dependencias
pip install -r requirements.txt
\`\`\`

## 💻 Uso

\`\`\`bash
python password_manager.py
\`\`\`

### Ejemplo de uso:

\`\`\`
1. Crear nueva bóveda
2. Añadir contraseña para "GitHub"
3. Generar contraseña segura automáticamente
\`\`\`

## 🔐 Seguridad

### Implementado:
- ✅ Cifrado simétrico con Fernet (AES-128-CBC)
- ✅ PBKDF2-HMAC para derivación de clave
- ✅ Salt criptográficamente seguro
- ✅ Contraseñas nunca almacenadas en texto plano

### Limitaciones (por diseño educativo):
- ⚠️ No ha sido auditado profesionalmente
- ⚠️ Sin sincronización multi-dispositivo
- ⚠️ Sin autenticación de dos factores
- ⚠️ Almacenamiento local únicamente

## 🛠️ Tecnologías

- Python 3.8+
- cryptography
- secrets (módulo estándar)
- json (módulo estándar)

## 📚 Aprendizajes

Durante este proyecto aprendí sobre:
- Implementación práctica de algoritmos criptográficos
- Key Derivation Functions (KDF)
- Manejo seguro de contraseñas en memoria
- Diseño de interfaces CLI amigables

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema de seguridad, por favor repórtalo de manera responsable.

## 📄 Licencia

MIT License - ver [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Tu Nombre**
- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- ORCID: [0009-0000-1485-200X](https://orcid.org/0009-0000-1485-200X)

## 🙏 Agradecimientos

- Documentación de [cryptography](https://cryptography.io/)
- Inspirado en gestores como Bitwarden y KeePass

---

⭐ Si este proyecto te ayudó a aprender, considera darle una estrella
