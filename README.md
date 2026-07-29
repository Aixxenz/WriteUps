# Pentest - WriteUps

Bienvenido a mi repositorio de documentación y apuntes de máquinas vulneradas en **Hack The Box**. Aquí guardo el registro de mi aprendizaje, comandos clave, vectores de ataque y metodologías utilizadas.

---

## 📊 Resumen de Progreso

| Plataforma | Fácil (Easy) | Media (Medium) | Difícil (Hard) | Total Completadas |
| :---: | :---: | :---: | :---: | :---: |
| **Hack The Box** | 🟢 1 | 🟡 0 | 🔴 0 | **1** |

---

## 🎯 Lista de Máquinas Resueltas

| # | Máquina | S.O. | Dificultad | IP | Vector de Ataque / Conceptos Clave | Writeup |
| :-: | :--- | :-: | :-: | :-: | :--- | :-: |
| 01 | **Lame** | 🐧 Linux | 🟢 Easy | `10.10.10.3` | VSFTPD 2.3.4 / Samba RCE (CVE-2007-2447) | [Ver Apuntes](./Hack-The-Box/Easy/Lame/README.md) |
| 02 | **Sau** | 🐧 Linux | 🟢 Easy | `10.10.10.240` | Request Baskets SSRF / Maltrail RCE | [Ver Apuntes](./Hack-The-Box/Easy/Sau/README.md) |
| 03 | **Blue** | 🪟 Windows | 🟢 Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](./Hack-The-Box/Easy/Blue/README.md) |

---

## 🛠️ Herramientas & Comandos Frecuentes

### 🔍 Reconocimiento & Escaneo
* **Nmap (Escaneo rápido):**
  ```bash
  nmap -p- --open -sS --min-rate 5000 -n -pn <IP>
