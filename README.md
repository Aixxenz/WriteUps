# Pentest - WriteUps

Bienvenido a mi repositorio de documentación y apuntes de máquinas vulneradas. Aquí guardo el registro de mi aprendizaje, comandos clave, vectores de ataque y metodologías utilizadas.

---

## 📊 Resumen de Progreso

| Plataforma | Muy Facil (Very Easy) | Fácil (Easy) | Media (Medium) | Difícil (Hard) | Insano (Insane) | Total Completadas |
| :---: | :---: | :--: | :---: | :---: | :---: | :--: |
| **Hack The Box** | 🔵 6 | 🟢 0 | 🟡 0 | 🔴 0 | 🟣 0 | **6** |

---

## 🎯 Lista de Máquinas Resueltas

| # | Máquina | S.O. | Dificultad | IP | Vector de Ataque / Conceptos Clave | Writeup |
| :-: | :--- | :-: | :-: | :-: | :--- | :-: |
| 01 | **Meow** | 🐧 Linux | 🔵 Very Easy | `10.10.10.3` | VSFTPD 2.3.4 / Samba RCE (CVE-2007-2447) | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Meow/README.md) |
| 02 | **Fawn** | 🐧 Linux | 🔵 Very Easy | `10.10.10.240` | Request Baskets SSRF / Maltrail RCE | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Fawn/README.md) |
| 03 | **Redeemer** | 🐧 Linux | 🔵 Very Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Redeemer/README.md) |
| 04 | **Appointment** | 🐧 Linux | 🔵 Very Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Appointment/README.md) |
| 05 | **Dancing** | 🪟 Windows | 🔵 Very Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Dancing/README.md) |
| 06 | **Responder** | 🪟 Windows | 🔵 Very Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Responder/README.md) |
---

## 🛠️ Herramientas & Comandos Frecuentes

### 🔍 Reconocimiento & Escaneo
* **Nmap (Escaneo rápido):**
  ```bash
  nmap -p- --open -sS --min-rate 5000 -n -pn <IP>
