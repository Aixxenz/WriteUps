<h1 align=center> Pentest - WriteUps </h1> 

Bienvenido a mi repositorio de documentación, apuntes y writeups de ciberseguridad. Aquí mantengo un registro detallado de mi aprendizaje, entornos prácticos resueltos **(Hack The Box y EC-Council)**, comandos clave, vectores de ataque y metodologías aplicadas.

---

<h1 align=center> Resumen de Progreso </h1>

## [HTB] Hack The Box

| Muy Fácil (Very Easy) | Fácil (Easy) | Media (Medium) | Difícil (Hard) | Insano (Insane) | Total Completadas |
| :---: | :--: | :---: | :---: | :---: | :--: |
| 🔵 3 | 🟢 0 | 🟡 0 | 🔴 0 | 🟣 0 | **6** |

## [ECC] EC-COUNCIL
| Categoria | Beginner | Intermediate | Advanced | Total Completadas |
| :---: | :---: | :---: | :--: | :--: |
| **EC-COUNCIL (Practice Labs)** | 🟢 0  | 🟡 0  | 🔴 0  | **0** |
| **EC-COUNCIL (CTFs)** | 🟢 0 | 🟡 0  | 🔴 0  | **0** |

---
<h1 align=center> Entornos resueltos </h1>

### EC-Council — CTF Challenges

| # | Desafío | Flags | Dificultad | Conceptos / Herramientas Clave | Writeup |
| :-: | :--- | :-: | :-: | :--- | :-: |
| 01 |  |  |  |   |  |


---
## EC-Council — Practice Labs
| # | Laboratorio / Tema | Ejercicios | Dificultad | Categoría | Writeup |
| :-: | :--- | :-: | :-: | :--- | :-: |
| 01 | | |  | | |

---
## Hack The Box

| # | Máquina | S.O. | Dificultad | IP | Vector de Ataque / Conceptos Clave | Writeup |
| :-: | :--- | :-: | :-: | :-: | :--- | :-: |
| 01 | **Meow** | Linux | 🔵 Very Easy | `10.129.247.95` | `Telnet / Null Authentication / Misconfiguration` | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Meow/README.md) |
| 02 | **Fawn** | Linux | 🔵 Very Easy | `10.129.5.231` | `FTP / Anonymous Login / Misconfiguration` | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Fawn/README.md) |
| 03 | **Redeemer** | Linux | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Redeemer/README.md) |
| 04 | **Appointment** | Linux | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Linux/Appointment/README.md) |
| 05 | **Dancing** | Windows | 🔵 Very Easy | `10.129.9.58` | `SMB / Anonymous/Guest Acces / Misconfiguration` | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Dancing/README.md) |
| 06 | **Responder** | Windows | 🔵 Very Easy | `10.10.10.40` |  | [Ver Apuntes](HackTheBox/VeryEasy/Windows/Responder/README.md) |
---

## Herramientas & Comandos Frecuentes

### Reconocimiento & Escaneo
* **Nmap (Reconocimiento):**
  ```bash
  nmap -sS -sV -Pn -p- --open <IP>
---
