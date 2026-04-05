# 🛠️ Kit de Herramientas Básicas - Sección: Herramienta Libre

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=40&pause=1000&color=02AAB0&center=true&vCenter=true&width=650&lines=Ophcrack;Recuperación+de+Contraseñas)](https://git.io/typing-svg)

<img src="https://img.shields.io/badge/Licencia-Open_Source-green?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="Licencia Open Source" />
<img src="https://img.shields.io/badge/Plataformas-Windows_|_Linux_|_macOS-blue?style=for-the-badge&logo=linux" alt="Plataformas Soportadas" />
<img src="https://img.shields.io/badge/Estado-Activo-success?style=for-the-badge" alt="Estado Activo" />

</div>

## 🔑 Recuperación y Auditoría de Contraseñas: Ophcrack

> 💡 **Herramienta Libre Seleccionada:** *Ophcrack* es un salvavidas para cualquier administrador de sistemas. Permite auditar y recuperar contraseñas de cuentas de usuario perdidas sin necesidad de tener acceso previo al sistema operativo.

---

### 📄 Descripción del Programa

**Ophcrack** es una herramienta gratuita y de código abierto basada en Windows y Linux que se utiliza para la recuperación de contraseñas de inicio de sesión. Funciona empleando un método criptográfico avanzado conocido como **Tablas Rainbow** (Rainbow Tables), que reduce drásticamente el tiempo necesario para descifrar los hashes de las contraseñas en comparación con los ataques tradicionales de fuerza bruta.

Para un administrador, la forma más útil de usar Ophcrack es a través de su versión **LiveCD**. Al igual que vimos en el apartado anterior, esta imagen ISO se puede cargar en un USB (¡usando Ventoy, por ejemplo!). Al arrancar el equipo desde este USB, Ophcrack monta automáticamente el disco duro del equipo, extrae el archivo SAM (donde Windows guarda las contraseñas) y comienza a descifrarlas de forma automática y visual.

#### ✨ Características Principales

| Característica | Descripción |
| :--- | :--- |
| 🌈 **Tablas Rainbow** | Uso de tablas precalculadas (LM y NTLM) que permiten recuperar contraseñas alfanuméricas en cuestión de minutos o segundos. |
| 💿 **Formato LiveCD** | Entorno autónomo basado en Linux. No requiere instalación en el disco duro afectado ni conocimientos de línea de comandos. |
| 🖥️ **Interfaz Gráfica (GUI)** | Muestra en tiempo real los usuarios detectados, los hashes extraídos y las contraseñas que se van descubriendo. |
| 🔍 **Modo Automático** | Al iniciar desde el LiveCD, el proceso de búsqueda del archivo SAM y el ataque a los hashes comienza sin intervención del usuario. |
| 📊 **Auditoría de Seguridad** | Más allá del rescate, sirve para que los administradores comprueben la fortaleza de las contraseñas de su red. |

---

### ⚙️ ¿Cómo funciona? (Flujo de Trabajo)

1. **Preparación del Medio:** Descargas la ISO de *Ophcrack LiveCD* correspondiente (hay versiones optimizadas para distintas versiones de Windows) y la copias en tu USB booteable.
2. **Arranque (Boot):** Inserte el USB en el equipo bloqueado, enciendes el PC y accedes al Boot Menu de la BIOS/UEFI para arrancar desde el USB.
3. **Ejecución y Extracción:** El sistema LiveCD carga una interfaz gráfica básica. Automáticamente montará la partición de Windows, buscará el archivo SAM y empezará a aplicar las tablas Rainbow para revelar las contraseñas en texto plano.

---

### ⬇️ Enlaces de Descarga y Recursos

Descarga la herramienta y las tablas Rainbow adicionales desde sus fuentes oficiales:

* 🌐 **Sitio Web Oficial:** [Ophcrack - Página Principal](https://ophcrack.sourceforge.io/)
* 📥 **Área de Descargas (LiveCD):** [Descargar ISOs](https://ophcrack.sourceforge.io/download.php?type=livecd)
* 📚 **Tablas Rainbow Extras:** [Rainbow Tables gratuitas](https://ophcrack.sourceforge.io/tables.php)
* 📖 **Documentación:** [FAQ y Manual de uso](https://ophcrack.sourceforge.io/faq.php)

---

### 🎥 Video Explicativo y Demostración Práctica

En el siguiente video tutorial, realizaremos una simulación de recuperación de una cuenta de administrador utilizando el LiveCD de Ophcrack:

<details>
<summary><b>Contenido del tutorial 👈</b></summary>

1. **Escenario:** Presentación de un equipo con Windows en el que hemos "olvidado" la contraseña de acceso.
2. **Arranque:** Inicio del sistema mediante el LiveCD de Ophcrack (cargado previamente en un USB).
3. **Recuperación en Vivo:** Demostración de cómo la interfaz gráfica captura los usuarios y, mediante las tablas Rainbow, extrae la contraseña en texto claro en pocos minutos.
</details>

<div align="center">

[![Ver Tutorial](https://img.shields.io/badge/▶_TUTORIAL-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/TU_ENLACE_AQUI)

</div>

---
