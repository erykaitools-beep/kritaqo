# Pierwszy test na Windows

Wersja do testów: **0.8.18-alpha.2**, Windows 10/11 x64. Nie trzeba znać programowania. Interfejs aplikacji i instalator są teraz domyślnie po angielsku; rozmawiać z modelami możesz nadal po polsku.

## Instalacja i pierwsza odpowiedź

1. [Pobierz instalator](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.18-alpha.2). Wybierz plik EXE; archiwum „Source code” zawiera dokumenty tego repozytorium.
2. Uruchom instalator na własnym komputerze. Przy pierwszej instalacji pozostaw włączone przygotowanie dostawców. Pobieranie wymaga internetu i może potrwać kilka minut.
3. Otwórz Kritaqo przez ikonę na pulpicie albo w menu Start. Program używa zainstalowanego Edge lub Chrome do wyświetlenia osobnego okna.
4. W **Accounts** połącz jedno obsługiwane konto albo własny klucz API. Jedno działające połączenie wystarczy. Hasło wpisuj na stronie logowania dostawcy.
5. Wybierz mastera i kliknij **Save selection**. Wyślij: „Odpowiedz wyłącznie: DZIAŁA”.
6. Zamknij okno i otwórz aplikację ponownie z ikony. Sprawdź, czy rozmowa i wybrany master są zachowane.

Do pracy na tym komputerze nie potrzebujesz Tailscale. Za użycie API płacisz dostawcy modelu; dostęp do API jest osobny od abonamentu jego czatu. Błąd konta nie uruchamia automatycznie płatnego API.

## Dodatkowe próby

- Utwórz projekt, napisz wiadomość i znajdź projekt po ponownym otwarciu aplikacji.
- Zaproś zespół. Sprawdź odpowiedzi planisty i recenzenta oraz wspólną odpowiedź końcową.
- Rozpocznij dłuższe zadanie, zatrzymaj je i wyślij: „Odpowiedz wyłącznie: DZIAŁA”. Sprawdź, czy nowa odpowiedź dotyczy nowej wiadomości.
- Jeśli masz już sparowane dwa komputery, sprawdź wspólną listę projektów. Zapytaj: „Wymień komputery i projekty, które widzisz. Podaj źródło i stan połączenia. Nie otwieraj plików”.
- Wyłącz drugi komputer i sprawdź, czy ostatnio widziane projekty nadal są pokazane jako niedostępne.

Trzy role mogą wykonać trzy osobno rozliczane zapytania do dostawców. Zacznij od krótkiego zadania. Próby zdalne są opcjonalne: obecnie wymagają Tailscale, świadomego sparowania instalacji i włączonego komputera źródłowego.

## Jak przekazać opinię

[Zgłoś błąd lub opinię testera](https://github.com/erykaitools-beep/kritaqo/issues/new/choose) albo napisz na **founder@kritaqo.com**.

Podaj wersję aplikacji, wersję Windows, co kliknąłeś, czego oczekiwałeś i co się wydarzyło. Przy błędzie modelu przyda się kod błędu. Sama lista modeli nie potwierdza dostępu do odpowiedzi.

W **Accounts → Testing help → Prepare report** możesz przygotować raport diagnostyczny. Przejrzyj go przed udostępnieniem; aplikacja nie wysyła go automatycznie.

Nie dołączaj haseł, kluczy API, kodów logowania, plików autoryzacji, całego folderu danych ani zrzutów prywatnych rozmów. Wrażliwe sprawy bezpieczeństwa zgłaszaj e-mailem według [SECURITY.md](../SECURITY.md).

## Aktualizacje i dane

W tej rundzie aktualizujesz aplikację, pobierając kolejny EXE i uruchamiając instalator. Automatyczny kanał aktualizacji nadal wymaga prywatnej sieci testowej.

Program jest w `%LOCALAPPDATA%\\Programs\\kritaqo`, dane w `%LOCALAPPDATA%\\kritaqo`. Odinstalowanie zachowuje dane. Nie przekazuj tego folderu innym testerom.

Instalator nie ma jeszcze certyfikatu wydawcy Windows. Sprawdzenie podpisu wydania lub sumy pliku nie jest audytem bezpieczeństwa. [Obecne ograniczenia](../ROADMAP.md) · [Autor, konta i dane](https://kritaqo.com/#trust).
