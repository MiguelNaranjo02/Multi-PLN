🧠 NLP Suite con Python: Texto ↔ Voz y Traducción
- Miguel Angel Naranjo Joya - 20201020037
- Handersson Felipe Pacheco Espitia - 20202020053
- Juan David Martínez Monroy - 20201020043
- Laura Andrea Riobueno Rincón - 20201020040

Este proyecto implementa una suite de herramientas en Python para el procesamiento de lenguaje natural, aprovechando modelos de redes neuronales y transformadores. El script analiza y transforma texto y voz a través de tareas como:

✅ Texto a Texto: Resumen, traducción y generación automática.

🎙 Texto a Voz: Conversión de texto en voz realista.

📝 Voz a Texto: Transcripción de audios a texto.

📂 Contenido del repositorio
TextoVoz.ipynb: Notebook principal con la implementación y pruebas de las funcionalidades.

requirements.txt: Lista de dependencias para reproducir el entorno.

README.md: Documentación del proyecto.

🚀 Funcionalidades
1. Texto a Texto
Usa modelos como T5 y GPT-2 para:

Resumir textos extensos.

Traducir entre inglés y español.

Generar contenido coherente a partir de un prompt.

2. Texto a Voz (TTS)
Utiliza pyttsx3 para sintetizar texto a voz localmente (sin necesidad de conexión a internet).

3. Voz a Texto (STT)
Emplea SpeechRecognition para transcribir archivos .wav a texto mediante motores como Google Speech API.

🛠 Instalación
1. Clona este repositorio:
- git clone https://github.com/MiguelNaranjo02/Multi-PLN
- cd nlp-texto-voz
  
2. pip install -r requirements.txt

🧪 Ejecución
Abre el notebook en Jupyter:

- jupyter notebook TextoVoz.ipynb

Cada sección del notebook puede ejecutarse de forma independiente y muestra ejemplos prácticos de uso.

📋 Requisitos
- Python 3.8+
- Conexión a internet para las funciones que usan modelos preentrenados en la nube (como HuggingFace).
- Micrófono y parlantes (para pruebas con voz).

📚 Tecnologías utilizadas
- HuggingFace Transformers
- PyTorch
- Pyttsx3
- SpeechRecognition
- Transformers: t5-small, gpt2, facebook/m2m100_418M
