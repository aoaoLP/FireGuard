# FireGuard
ML system for detection FIRE SMOKE or SAFE status on picture
🤖 FireHome - Inteligentny Bot Telegram (Wykrywanie Pożarów)
Projekt aplikacji wykorzystującej sztuczną inteligencję (Computer Vision) do automatycznego wykrywania zagrożeń pożarowych na podstawie zdjęć przesyłanych przez użytkownika w czasie rzeczywistym.

🛠️ Jak to działa?
Komunikacja: Użytkownik przesyła zdjęcie za pośrednictwem komunikatora Telegram.

Analiza AI: Autorski skrypt (Python + OpenCV) przetwarza obraz i przekazuje go do sieci neuronowej opartej na architekturze MobileNetV2 (TensorFlow/Keras).

Wynik: Model w ułamku sekundy klasyfikuje obraz do jednej z trzech kategorii: BEZPIECZNIE, DYM lub OGIEŃ i odsyła informację zwrotną wraz z procentową pewnością wyniku.

🧰 Użyte Technologie
Python

TensorFlow / Keras (Uczenie głębokie)

OpenCV (Przetwarzanie obrazu)

pyTelegramBotAPI / Telebot (Obsługa bota)
