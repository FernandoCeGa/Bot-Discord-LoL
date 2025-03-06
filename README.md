# 🤖 Bot de Discord para League of Legends


## 📌 Descripción  
Este bot de Discord, desarrollado en **Python**, permite a los usuarios obtener estadísticas de **League of Legends** en tiempo real. Facilita la consulta de información sobre invocadores, campeones y noticias del juego, optimizando la experiencia de las comunidades en Discord.  

## 🚀 Características  
✔️ **Consulta de estadísticas de invocadores** por nombre de usuario.  
✔️ **Información de campeones**: habilidades, roles y estadísticas.  
✔️ **Noticias y actualizaciones** sobre el juego en tiempo real.  

## 🛠️ Tecnologías Utilizadas  
- **Python** 🐍  
- **discord.py** para la integración con Discord.  
- **Riot Games API** para obtener datos del juego.  

## 🔧 Requisitos Previos  
1️⃣ Tener instalado **Python 3.8+**.  
2️⃣ Contar con tokens de **Discord** y **Riot Games API**.  

## ⚡ Instalación  
1. **Clona el repositorio**:  
   ```bash
   git clone https://github.com/FernandoCeGa/Bot-Discord-LoL.git
   cd Bot-Discord-LoL
   ```
2. **Crea y activa un entorno virtual**:  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```
3. **Instala las dependencias**:  
   ```bash
   pip install -r requirements.txt
   ```
4. **Configura las credenciales**:  
   - Renombra el archivo `.env.example` a `.env`.  
   - Agrega los tokens de Discord y Riot Games en el `.env`.  

5. **Inicia el bot**:  
   ```bash
   python bot.py
   ```

## 🎮 Uso  
📌 **Comandos principales:**  
- `!estadisticas [nombre_invocador]` → Muestra estadísticas del jugador.  
- `!campeon [nombre_campeon]` → Información detallada de un campeón.  
- `!noticias` → Últimas noticias y parches de League of Legends.  

## 🤝 Contribuciones  
¡Las contribuciones son bienvenidas! 🚀  

1. **Haz un fork del repositorio** en [GitHub](https://github.com/FernandoCeGa/Bot-Discord-LoL/fork).  
2. **Crea una nueva rama** para tu funcionalidad:  
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. **Realiza cambios y haz commit**:  
   ```bash
   git commit -m "Añadir nueva funcionalidad"
   ```
4. **Sube los cambios al repositorio**:  
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. **Abre una Pull Request** en [este enlace](https://github.com/FernandoCeGa/Bot-Discord-LoL/pulls).  

## 📜 Licencia  
Este proyecto está bajo la **Licencia MIT**.

## 📩 Contacto  
Desarrollado por **Fernando CeGa**.  
✉️ **Correo:** [fcerecedogi@uanl.edu.mx](mailto:fcerecedogi@uanl.edu.mx)  
🔗 **GitHub:** [github.com/FernandoCeGa](https://github.com/FernandoCeGa)

