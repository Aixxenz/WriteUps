# Pentest - WriteUps

Bienvenido a mi repositorio de documentación, apuntes y writeups de ciberseguridad. Aquí mantengo un registro detallado de mi aprendizaje, entornos prácticos resueltos **(Hack The Box y EC-Council)**, comandos clave, vectores de ataque y metodologías aplicadas.

---

## 📊 Resumen de Progreso

| Plataforma | Muy Fácil (Very Easy) | Fácil (Easy) | Media (Medium) | Difícil (Hard) | Insano (Insane) | Total Completadas |
| :---: | :---: | :--: | :---: | :---: | :---: | :--: |
| **Hack The Box** | 🔵 6 | 🟢 0 | 🟡 0 | 🔴 0 | 🟣 0 | **6** |
| **EC-COUNCIL (Practice Labs)** | N/A | 🟢 0 **(Beginner)** | 🟡 0 **(Intermediate)** | 🔴 0 **(Advanced)** | N/A | **0** |
| **EC-COUNCIL (CTFs)** | N/A | 🟢 0 **(Beginner)** | 🟡 0 **(Intermediate)** | 🔴 0 **(Advanced)** | N/A | **0** |

---
### 🚩 EC-Council — CTF Challenges

| # | Desafío | Flags | Dificultad | Conceptos / Herramientas Clave | Writeup |
| :-: | :--- | :-: | :-: | :--- | :-: |
| 01 | Powah | 7 Flags | 🟢 Beginner | RDP Enum / PrivEsc / PowerShell | [Ver Apuntes](./EC-Council/CTFs/Beginner/Powah.md) |
| 02 | ChromeCracker | 6 Flags | 🔴 Advanced |  | [Ver Apuntes](./EC-Council/CTFs/Advanced/ChromeCracker.md) |

---
## 🔬 EC-Council — Practice Labs
| # | Laboratorio / Tema | Ejercicios | Dificultad | Categoría | Writeup |
| :-: | :--- | :-: | :-: | :--- | :-: |
| 01 | Intro to Supervised ML for Cyber Analytics | 2 Labs | 🟡 Intermediate | Artificial Intelligence | [Ver Apuntes](./EC-Council/Practice_Labs/Intermediate/ML_Cyber_Analytics.md) |
| 02 | Exploiting Vulnerabilities in Google Gruyere | 4 Labs | 🔴 Advanced |  | [Ver Apuntes](./EC-Council/Practice_Labs/Advanced/Google_Gruyere.md) |
| 03 | Advanced AI Red Teaming with PyRIT | 1 Lab | 🔴 Advanced |  | [Ver Apuntes](./EC-Council/Practice_Labs/Advanced/AI_Red_Teaming.md) |
---
## 🎯 Máquinas Resueltas - Hack The Box

| # | Máquina | S.O. | Dificultad | IP | Vector de Ataque / Conceptos Clave | Writeup |
| :-: | :--- | :-: | :-: | :-: | :--- | :-: |
| 01 | **Meow** | 🐧 Linux | 🔵 Very Easy | `10.10.10.3` |  | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Meow/README.md) |
| 02 | **Fawn** | 🐧 Linux | 🔵 Very Easy | `10.10.10.240` |  | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Fawn/README.md) |
| 03 | **Redeemer** | 🐧 Linux | 🔵 Very Easy | `10.10.10.40` | EternalBlue (MS17-010) / Metasploit | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Redeemer/README.md) |
| 04 | **Appointment** | 🐧 Linux | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Appointment/README.md) |
| 05 | **Dancing** | 🪟 Windows | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Dancing/README.md) |
| 06 | **Responder** | 🪟 Windows | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Responder/README.md) |
---

## 🛠️ Herramientas & Comandos Frecuentes

### 🔍 Reconocimiento & Escaneo
* **Nmap (Reconocimiento):**
  ```bash
  nmap -sS -sV -Pn -p- --open <IP>
