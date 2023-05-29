# Dokumentacja aplikacji do rysowania na Canvas

Aplikacja do rysowania na Canvas to oparta na HTML aplikacja, która umożliwia użytkownikom rysowanie i manipulację kształtami na elemencie canvas. Zapewnia różne narzędzia i funkcje do tworzenia linii, elips, prostokątów i wielokątów.

## Użycie

Aby korzystać z aplikacji do rysowania na Canvas, postępuj zgodnie z poniższymi krokami:

1. Otwórz plik HTML zawierający aplikację canvas w przeglądarce internetowej.

2. Na canvasie zobaczysz zestaw przycisków i pól wprowadzania do różnych działań i ustawień.

3. **Rysowanie linii**: Kliknij przycisk "Rysuj linie", aby włączyć tryb rysowania linii. Kliknij i przeciągnij na canvasie, aby utworzyć odcinek linii.

4. **Przenoszenie punktów**: Kliknij przycisk "Przesuń punkty", aby włączyć tryb przenoszenia punktów. Kliknij i przeciągnij na istniejącym kształcie, aby przesunąć jego punkty końcowe.

5. **Gumka**: Kliknij przycisk "Gumka", aby włączyć tryb gumki. Kliknij na kształt, aby go usunąć z canvasa.

6. **Rysowanie elips**: Kliknij przycisk "Elipsa", aby włączyć tryb rysowania elips. Kliknij i przeciągnij na canvasie, aby utworzyć elipsę.

7. **Rysowanie prostokątów**: Kliknij przycisk "Prostokąt", aby włączyć tryb rysowania prostokątów. Kliknij i przeciągnij na canvasie, aby utworzyć prostokąt.

8. **Rysowanie wielokątów**: Kliknij przycisk "Wielokąt", aby włączyć tryb rysowania wielokątów. Kliknij na canvasie, aby zdefiniować wierzchołki wielokąta. W tym przykładzie wielokąt jest traktowany jako trójkąt.

9. **Grubość linii**: Użyj suwaka "lineWidth", aby dostosować grubość linii kształtów.

10. **Wybór koloru HSV**: Użyj suwaków "Odcień", "Nasycenie" i "Wartość", aby wybrać kolor w formacie HSV. Kolor obramowania kształtów zostanie zaktualizowany zgodnie z wybranymi wartościami HSV.

## Wyjaśnienie kodu

Przedstawiony kod tworzy interaktywną aplikację do rysowania na canvas. Oto krótkie wyjaśnienie kluczowych komponentów kodu:

- Struktura HTML składa się z elementu canvas oraz przycisków i pól wprowadzania dla różnych działań i ustawień.

- Kod JavaScript obsługuje interakcje użytkownika i operacje związane z rysowaniem na canvas. Śledzi kształty, indeks wybranego kształtu, przenoszenie punktów oraz różne flagi dla różnych działań.

- Zdefiniowane są obsługiwane zdarzenia dla akcji myszy, takich jak kliknięcie, przesunięcie i puszczenie. Canvas jest odświeżany na podstawie interakcji użytkownika i ustawień.

- Skrypt zawiera funkcje pomocnicze do konwersji koloru z HSV na RGB oraz aktualizacji koloru obramowania kształtów na podstawie wartości HSV.
