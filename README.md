# Born2beroot

**Born2beroot** es un proyecto que introduce los fundamentos de la administración de sistemas y la configuración de servidores. Su objetivo principal es instalar y configurar una máquina virtual con **Debian (sin entorno gráfico)**, aplicando buenas prácticas de seguridad y gestión de usuarios.  

---

## 📌 Objetivos del proyecto  

- Instalar y configurar una máquina virtual utilizando **Oracle VirtualBox**.  
- Implementar **sudo** y definir políticas de permisos y seguridad.  
- Gestionar **usuarios y grupos**, aplicando reglas de acceso y seguridad.  
- Configurar un **firewall** con **UFW (Uncomplicated Firewall)**.  
- Establecer reglas de contraseñas y restricciones de acceso.  
- Implementar un servicio de **monitorización del sistema**.  
- Automatizar tareas con **crontab**.  
- Aplicar **normas de seguridad del estándar UEFI**.  

---

## 🛠️ Tecnologías y herramientas utilizadas  

| Tecnología | Uso en el proyecto |
|------------|-------------------|
| **Debian** | Sistema operativo principal |
| **VirtualBox** | Virtualización de la máquina |
| **Bash** | Automatización y configuración del sistema |
| **SSH** | Acceso remoto seguro |
| **UFW** | Configuración de firewall |
| **Sudo** | Gestión de permisos y privilegios |
| **Crontab** | Programación de tareas automatizadas |
| **Hostnamectl** | Configuración de nombre de host y virtualización |

---

## 📖 Configuración y funcionalidades clave  

### 🔹 Instalación del sistema operativo  
El proyecto requiere la instalación de **Debian** sin entorno gráfico, asegurando una configuración mínima para un servidor seguro y eficiente.  

### 🔹 Gestión de usuarios y privilegios  
- Creación de un usuario con permisos restringidos.  
- Configuración de **sudo** para permitir privilegios administrativos.  
- Aplicación de reglas de seguridad, como **expiración de contraseñas** y políticas de acceso.  

### 🔹 Seguridad y firewall  
- Configuración de **UFW** para gestionar el acceso a la red.  
- Desactivación de accesos no seguros y limitación de servicios expuestos.  

### 🔹 Monitorización del sistema  
- Implementación de scripts para registrar **uso de CPU, RAM y disco**.  
- Configuración de **cron jobs** para reportes automáticos.  

### 🔹 Normas UEFI y particionado del disco  
- Uso de particiones adecuadas para garantizar compatibilidad y seguridad.  

---

## 🚀 Habilidades desarrolladas  

✅ Administración de servidores Linux.  
✅ Configuración de usuarios, permisos y seguridad.  
✅ Implementación de reglas de firewall con UFW.  
✅ Automatización de tareas y scripts en Bash.  
✅ Monitorización y optimización de sistemas.  
