# 🌐 UF5 — Acceso a través de la Red

![Unidad Formativa 5](../../PRESENTACION/imgs/UNIDADFORMATIVA5.png)

> **Unidad Formativa 5** · Módulo 1: Linux para el Usuario · IFCT114PO

---

> [!WARNING]
> ## ⚠️ Aviso Importante — Equipos del Curso (FQDN / DNS)
>
> Los equipos de prácticas del curso son accesibles mediante los siguientes **nombres de dominio (FQDN)**. Ten en cuenta que el acceso puede estar **limitado por directivas de seguridad**.
>
> | 🖥️ Hostname | 🌐 FQDN | 🔢 Dirección IP |
> |------------|---------|----------------|
> | Rocky Linux 10 | `rockyifct114po.chickenkiller.com` | `35.225.175.215` |
> | Debian | `debianifct114po.chickenkiller.com` | `35.193.198.73` |
>
> ### 🔍 Comprobación de la resolución DNS
>
> Verifica que los nombres se resuelven correctamente ejecutando el siguiente comando:
>
> ```bash
> ping -c 2 rockyifct114po.chickenkiller.com; ping -c 2 debianifct114po.chickenkiller.com
> ```

---

## 📖 Descripción

En el mundo moderno, el acceso remoto a sistemas Linux es el pan de cada día. Esta unidad enseña a **conectarse de forma segura** a servidores remotos usando el protocolo **SSH** (Secure Shell), transferir ficheros de manera cifrada con **SCP** y **SFTP**, y gestionar conexiones sin contraseña mediante claves criptográficas. Son habilidades esenciales para cualquier administrador de sistemas o desarrollador que trabaje con servidores.

---

## 🗂️ Índice de Ficheros

| 📁 Fichero | Tipo | Descripción |
|-----------|------|-------------|
| 📄 `00-Acceso a través de la red.pdf` | Teoría | SSH, SCP, SFTP, claves públicas/privadas y configuración |
| 📝 `Ejercicios01.odt` | Práctica | Ejercicios editables de la unidad |
| 📝 `Ejercicios01.pdf` | Práctica | Ejercicios en formato PDF |

---

## 🎯 Objetivos de la Unidad

- ✅ Conectarse a sistemas remotos mediante SSH
- ✅ Transferir ficheros de forma segura con SCP y SFTP
- ✅ Generar y gestionar pares de claves SSH (pública/privada)
- ✅ Configurar acceso sin contraseña mediante claves autorizadas
- ✅ Configurar opciones básicas del servidor SSH

---

## 💡 Conceptos Clave

> 🔑 **SSH** · 📤 **SCP** · 🔐 **Criptografía asimétrica** · 🗝️ **Claves RSA/ED25519** · 🌍 **Acceso remoto seguro**

---

[⬆️ Volver al Módulo 1](../README.md) · [🏠 Inicio](../../README.md)
