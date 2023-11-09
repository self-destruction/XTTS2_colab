# XTTS v2 Ru (Текст в речь)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/self-destruction/XTTS2_colab/blob/main/XTTS_v2_RU.ipynb)  
Синтез речи по тексту. За основу взят репозиторий [TTS](https://github.com/coqui-ai/TTS) и модель [поддерживающая русский язык](https://huggingface.co/coqui/XTTS-v2). Синтез речи запускается в Google Colab не используя Gradio-интерфейс. Речь генерируется на основе файла-референса, который необходимо предварительно загрузить. Далее произойдёт очистка файла от шумов и пауз, и генерация.
