# Image Color Palette Extractor

Aplikacja webowa z nowoczesnym interfejsem, zbudowana w Pythonie (Flask). Automatycznie analizuje przesłane przez użytkownika zdjęcie i wyodrębnia z niego 10 dominujących kolorów, korzystając z algorytmu uczenia maszynowego.

## Funkcje
- **Machine Learning (K-Means):** Wykorzystanie zaawansowanego algorytmu klastrowania (`scikit-learn`) do znalezienia rzeczywistej palety barw obrazu.
- **Przetwarzanie obrazu:** Automatyczna konwersja i skalowanie plików graficznych za pomocą `Pillow` i `NumPy`.
- **Interaktywny interfejs (UI):** Responsywny design inspirowany platformą "Flat UI Colors".
- **Kopiowanie do schowka:** Integracja z JavaScript pozwalająca na skopiowanie kodu HEX jednym kliknięciem (z powiadomieniem Toast).

## Technologie
- Python 3.x
- Flask (Backend)
- scikit-learn (K-Means clustering)
- NumPy & Pillow (Analiza obrazu)
- HTML5 / CSS3 / JavaScript (Frontend)

## Instalacja i uruchomienie

1. Sklonuj repozytorium na swoj dysk:

   ```git clone https://github.com/DamianG4/image-color-extractor.git```

2. Wejdz do folderu projektu:

   ```cd image-color-extractor```

3. Zainstaluj wymagane biblioteki:

   ```pip install -r requirements.txt```

4. Uruchom serwer developerski:

   ```python main.py```

5. Otwórz przeglądarkę i przejdź pod adres:
   
   [http://127.0.0.1:5000](http://127.0.0.1:5000)
   
