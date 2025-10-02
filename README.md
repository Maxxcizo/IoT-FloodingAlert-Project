🌊 Proyecto IoT de Alerta de Inundaciones
Un proyecto robusto de IoT para la detección y alerta de inundaciones en túneles o zonas críticas.Simula sensores, almacena datos en MongoDB y los visualiza en un sitio web en GitHub Pages.

✨ Funcionalidades

🛠️ Simulación de sensores de humedad y nivel de agua.
📊 Almacenamiento de datos en MongoDB.
🚨 Generación de alertas ante riesgos de inundación.
🌐 Visualización de datos y estado del sistema en un sitio web en GitHub Pages.
🔧 Código modular y escalable para futuros sensores o funcionalidades.


📂 Estructura del Proyecto
IoT-FloodingAlert-Project/
│
├── README.md                # Documentación del proyecto
├── docs/                    # Sitio web para GitHub Pages
│   └── index.html           # Página principal
├── src/                     # Código fuente
│   └── main.py              # Script de simulación de sensores
├── requirements.txt         # Dependencias de Python
└── .gitignore               # Archivos a ignorar (ej. venv)


🛠️ Instalación

Clona el repositorio:
git clone https://github.com/Maxxcizo/IoT-FloodingAlert-Project.git
cd IoT-FloodingAlert-Project


Crea un entorno virtual (recomendado):
python3 -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate


Instala las dependencias:
pip install -r requirements.txt




🚀 Uso
Ejecuta la simulación de sensores:
python src/main.py

El script simula datos de sensores, los almacena en MongoDB y emite alertas si se detectan riesgos de inundación según los umbrales configurados.

🌐 Sitio Web en GitHub Pages
El proyecto incluye un sitio web hospedado en GitHub Pages en:🔗 https://Maxxcizo.github.io/IoT-FloodingAlert-Project/
Ubicado en docs/index.html, muestra:

Descripción del proyecto
Datos de sensores en tiempo real
Alertas de inundación


🤝 Contribuciones
¡Agradecemos tus contribuciones! Para colaborar:

Haz un fork del repositorio.
Crea una nueva rama:git checkout -b feature/tu-funcionalidad


Realiza tus cambios y haz commit:git commit -m "Descripción de tu funcionalidad"


Sube los cambios a tu fork y crea un Pull Request.


📜 Licencia
Este proyecto está licenciado bajo la Licencia MIT.