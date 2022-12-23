# Aplikacja do wyświetlania kursów walut

Aplikacja powinna wyświetlać kilka par walut z aktualnym kursem (aktualizowanym w czasie rzeczywistym), można wejść w daną parę walut, żeby zobaczyć wykres pokazujący zmiany na walucie z okresu 7 lub 14 dni (do zmiany na ekranie przez użytkownika) 

## Zasoby

[https://twelvedata.com/](https://twelvedata.com/) - API zapewniające dostęp do aktualnych kursów walut

[https://firebase.google.com/](https://firebase.google.com/) - Baza danych, Logowanie etc.

## Ekrany

- Logowanie / Rejestracja (dowolna sposób telefon/login/email etc)
- Dashboard z dodanymi przez użytkownika parami walut oraz komunikatem “Hello {imię}”
    - Użytkownik może z tego ekranu dodać nową parę walut do swojego dashboarda
    - Każda dodana przez użytkownika para walut pokazuje się na dashboardzie wraz z kursem aktualizowanym w czasie rzeczywistym
    - Po kliknięciu na dodaną wcześniej parę walut użytkownik przechodzi do ekranu Szczegółów
- Szczegóły Pary - ekran wyświetlający aktualny kurs pary walut oraz historyczny wykres zmian.
    - Użytkownik może wybrać okres (7 lub 14 dni), z którego pobierane są dane do wykresu

## Wymagania

- State Management: Riverpod
- Baza danych i autentykacja: Firebase
- Aplikacja w dowolny sposób przechowuje sesję użytkownika, żeby nie musiał się logować ponownie po zamknięciu i odpaleniu aplikacji
- Fajnie by było zobaczyć jakieś testy jednostkowe,golden,widget (opcjonalnie)
