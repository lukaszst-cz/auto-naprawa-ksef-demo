# Auto Naprawa KSeF Demo

Demonstracyjna strona warsztatu samochodowego wraz z panelem obsługi dokumentów i faktur. Projekt pokazuje połączenie czytelnej prezentacji usług z prostym widokiem operacyjnym.

## W środku

- responsywna strona startowa,
- portal klienta i panel faktur,
- ekran studium przypadku,
- grafiki oraz dane demonstracyjne.

## Jak zobaczyć projekt

Otwórz `index.html` w przeglądarce.

## Działająca prezentacja

[Otwórz Auto Naprawa KSeF Demo](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/)

## Szybki podgląd

- [Strona warsztatu](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/)
- [Portal klienta](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/portal/?role=client)
- [Panel kierownika](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/portal/?role=manager)
- [Faktury i symulacja KSeF](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/portal/faktury.html)
- [Case study / zakres wdrożenia](https://lukaszst-cz.github.io/auto-naprawa-ksef-demo/case-study.html)

Projekt jest częścią głównego [portfolio operacyjnego](https://github.com/lukaszst-cz/operations-office-portfolio).


## Zakres symulacji KSeF

Moduł faktur pokazuje przebieg od zamkniętego zlecenia do walidacji i przykładowego UPO, ale pozostaje wyłącznie demonstracją interfejsu i procesu.

- nie łączy się z API Ministerstwa Finansów;
- nie generuje produkcyjnego XML FA(3);
- nie przechowuje certyfikatów ani danych uwierzytelniających;
- przykładowy numer KSeF/UPO nie jest prawdziwym identyfikatorem;
- przed wdrożeniem wymagane są aktualna walidacja struktury FA(3), bezpieczny backend i testy integracyjne z właściwym środowiskiem KSeF.

Nazewnictwo KSeF 2.0 / FA(3) odpowiada aktualnemu modelowi systemu używanemu od 2026 r.

## Powiązany projekt

WorkshopFlow 360 pokazuje pełny proces operacyjny warsztatu — od rezerwacji i diagnozy do wydania auta.

https://github.com/lukaszst-cz/workshopflow-360


## Kontrola jakości

GitHub Actions sprawdza składnię JavaScript oraz wszystkie lokalne odsyłacze i assety HTML przed publikacją strony.

---

## ☕ Wsparcie / Support

Jeśli ten projekt Ci się podoba lub jest dla Ciebie przydatny, możesz dobrowolnie wesprzeć jego dalszy rozwój.  
If you like this project or find it useful, you can support its further development.

**[☕ Postaw Naleśnikowi++ kawę / Buy Me a Coffee](https://buymeacoffee.com/nalesnik_plus_plus)**

