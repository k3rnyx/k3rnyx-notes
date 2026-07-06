# Instalación y configuración inicial de Kali Linux

## Objetivo

Documentar el proceso de instalación y configuración básica de Kali Linux como entorno de laboratorio para investigación en seguridad informática.

---

# Requisitos

- VirtualBox o VMware
- Imagen ISO oficial de Kali Linux
- Mínimo 4 GB de RAM
- 2 CPU
- 40 GB de almacenamiento

---

# Descarga

Sitio oficial:

https://www.kali.org/

---

# Creación de la máquina virtual

Configuración recomendada:

| Recurso | Valor |
|---------|-------|
| RAM | 4096 MB |
| CPU | 2 |
| Disco | 40 GB |
| Red | NAT |

---

# Instalación

Seguir el asistente de instalación.

Configurar:

- Idioma
- Zona horaria
- Usuario
- Contraseña

---

# Actualización del sistema

```bash
sudo apt update
sudo apt full-upgrade -y
```

---

# Instalación de herramientas útiles

```bash
sudo apt install -y \
git \
curl \
wget \
vim \
build-essential
```

---

# Verificar versión

```bash
cat /etc/os-release
```

---

# Buenas prácticas

- Mantener el sistema actualizado.
- No trabajar como root.
- Utilizar snapshots.
- Documentar los cambios realizados.

---

# Conclusión

Con esta configuración se obtiene un entorno base preparado para laboratorios de seguridad y desarrollo.

---

**Research. Build. Secure.**

— K3rNyx