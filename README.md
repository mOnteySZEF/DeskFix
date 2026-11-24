# DeskFix (System zgłoszeń awarii)

Aplikacja webowa do zgłaszania i obsługi usterek technicznych (np. w salach komputerowych). Uczeń lub pracownik zgłasza problem, a technik przyjmuje zgłoszenie, zmienia jego status i w razie potrzeby eskaluje dalej.

## Cel projektu
Uporządkowanie procesu zgłaszania awarii w jednym miejscu, skrócenie czasu reakcji na usterki oraz ułatwienie pracy technikom dzięki przejrzystemu podglądowi aktualnych zadań.

## Główne funkcje
- **Zgłaszanie usterek** przez uczniów i pracowników (przypisanie do sali i konkretnego sprzętu).
- **Obsługa zgłoszeń** przez techników (przyjmowanie, zmiana statusu, eskalacja).
- **Priorytety i SLA** do określania pilności zgłoszeń i czasu reakcji.
- **Dashboard** z podglądem liczby otwartych zgłoszeń.
- **Tablica Kanban** z obsługą drag & drop do wygodnego zarządzania statusami.

## Stack technologiczny
Stack deweloperski będzie się zmieniał i rozszerzał wraz z rozwojem aplikacji. Na start wykorzystujemy:

- **React** – główna warstwa frontendowa aplikacji.
- **MariaDB** – użytkownicy, sale, sprzęt, zgłoszenia, statusy.
- **MongoDB** – komentarze w wątku zgłoszenia, metadane załączników, log zmian statusu.
- **jQuery UI** – obsługa drag & drop na tablicy Kanban.



## Plany na rozwój
- Powiadomienia o zmianie statusu zgłoszenia lub nowym komentarzu.
- Proste statystyki i raporty (np. najczęstsze awarie i obciążenie techników).
- Podział na role i uprawnienia (uczeń, pracownik, technik, admin).
- Dodawanie zdjęć i załączników bezpośrednio przy zgłoszeniu usterki.
- Przepisanie tablicy Kanban w pełni na Reacta wraz z rozwojem projektu.
