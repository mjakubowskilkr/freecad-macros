# 💠 Pattern Cut Generator for FreeCAD

![Version](https://img.shields.io/badge/version-v0.9.1-blue.svg)
![FreeCAD](https://img.shields.io/badge/FreeCAD-1.0%2B-green.svg)
![Language](https://img.shields.io/badge/language-Python-yellow.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Mac-lightgrey.svg)

🌍 **[English Version](#-english-version)** | 🇵🇱 **[Wersja Polska](#-wersja-polska)**

---

## 🇬🇧 English Version

> **Pattern Cut Generator** is a highly optimized FreeCAD macro designed to generate complex patterned cutouts on flat surfaces. Built for performance and usability, it bypasses the heavy calculations of the FreeCAD Sketcher by utilizing direct Constructive Solid Geometry (CSG) boolean operations.

### ✨ Features

* 🛑 **5 Pattern Types**: Hexagons (honeycomb), Circles, Diamonds, Slotted (horizontal/vertical), and Triangles.
* 🚀 **Extreme Performance**: Uses `Part.Compound` and bulk `common` boolean operations to process hundreds of cutouts without melting your CPU.
* 👁️ **Real-time 3D Preview**: Instantly see the pattern overlay on your selected face before generating the final cut.
* 🌐 **Bilingual UI**: Fully translated graphic interface (English and Polish) with dynamic switching and online flag icons.
* 💾 **Persistent Settings**: Automatically saves and loads your last used parameters (size, gap, border, depth) using FreeCAD's user parameter registry.
* 🛡️ **Rock-solid Stability**: Safe memory handling and background timer termination ensure FreeCAD remains perfectly stable (no `Access Violation` errors) after the macro is closed.

### 📥 Installation

1. Download the `PaterrnCutGenerator.FCMacro` file from this repository.
2. Place it in your FreeCAD Macro directory. Typical locations:
   * **Windows**: `%APPDATA%\FreeCAD\Macro\`
   * **Linux**: `~/.local/share/FreeCAD/Macro/`
   * **macOS**: `~/Library/Preferences/FreeCAD/Macro/`
3. Open FreeCAD, go to `Macro -> Macros...`, select the file, and click **Execute**.

### 🛠️ Usage

1. Select a **flat face** in the 3D view.
2. Run the macro.
3. Click the **Get selected face** button.
4. Adjust the parameters: *Shape, Size, Gap, Border, and Depth*.
5. Click **GENERATE CUT** and wait for the progress bar to finish.

---
> ☕ **Enjoying this macro?**
> If this tool has saved you hours of FreeCAD struggles and computing time, consider buying me a coffee! It fuels my coding sessions and helps me create more free tools for the community.
> 
> [![Support me on Suppi](https://img.shields.io/badge/Buy_me_a_coffee-suppi.pl-FF5E5B?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://suppi.pl/mjlkr)

## 🇵🇱 Wersja Polska

> **Generator Wycięć Wzorów** to wysoce zoptymalizowane makro do programu FreeCAD, służące do generowania złożonych wzorów na płaskich powierzchniach. Zaprojektowane z myślą o wydajności i komforcie użytkownika, omija ciężkie obliczenia środowiska Szkicownika (Sketcher), wykorzystując bezpośrednie operacje logiczne CSG na bryłach.

### ✨ Główne cechy

* 🛑 **5 typów wzorów**: Heksagony (plaster miodu), Okręgi, Romby, Fasolki (poziome/pionowe) oraz Trójkąty.
* 🚀 **Wysoka wydajność**: Wykorzystuje obiekty `Part.Compound` oraz zbiorcze operacje logiczne (`common`), aby przetwarzać setki otworów bez zawieszania procesora.
* 👁️ **Podgląd 3D na żywo**: Pozwala natychmiast zobaczyć nakładkę wzoru na wybranej ścianie przed wygenerowaniem ostatecznego cięcia.
* 🌐 **Dwujęzyczny interfejs**: W pełni przetłumaczony interfejs graficzny (Polski i Angielski) z dynamicznym przełączaniem i ikonami flag.
* 💾 **Zapisywanie ustawień**: Automatycznie zapisuje i wczytuje ostatnio używane parametry (rozmiar, odstęp, ramka, głębokość) w rejestrze ustawień FreeCAD.
* 🛡️ **Pancerna stabilność**: Bezpieczne zarządzanie pamięcią i ubijanie timerów w tle gwarantuje, że FreeCAD pozostaje stabilny (brak błędów `Access Violation`) po zamknięciu makra.

### 📥 Instalacja

1. Pobierz plik `PaterrnCutGenerator.FCMacro` z tego repozytorium.
2. Umieść go w swoim folderze Makr FreeCAD. Typowe lokalizacje to:
   * **Windows**: `%APPDATA%\FreeCAD\Macro\`
   * **Linux**: `~/.local/share/FreeCAD/Macro/`
   * **macOS**: `~/Library/Preferences/FreeCAD/Macro/`
3. Otwórz FreeCAD, przejdź do górnego menu `Makro -> Makra...`, wybierz plik z listy i kliknij **Wykonaj**.

### 🛠️ Jak używać

1. Zaznacz **płaską ścianę** modelu w widoku 3D.
2. Uruchom makro.
3. Kliknij przycisk **Pobierz zaznaczoną ścianę**.
4. Dostosuj parametry według uznania: *Kształt, Rozmiar, Odstęp, Ramkę i Głębokość*.
5. Kliknij **GENERUJ WYCIĘCIE** i poczekaj na wypełnienie paska postępu.

---
> ☕ **Podoba Ci się to, co robię?**
> Jeśli to makro okazało się przydatne i zaoszczędziło Ci mnóstwo czasu (i nerwów) podczas projektowania, możesz postawić mi wirtualną kawę! To świetne paliwo, które napędza mnie do tworzenia kolejnych narzędzi i aktualizacji.
> 
> [![Wesprzyj mnie na Suppi](https://img.shields.io/badge/Postaw_mi_kawę-suppi.pl-FF5E5B?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://suppi.pl/mjlkr)

*Created with passion for the FreeCAD community.*
