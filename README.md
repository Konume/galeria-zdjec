# Galeria Zdjęć

## Opis

Projekt "Galeria Zdjęć" to aplikacja umożliwiająca przechowywanie, przeglądanie i zarządzanie kolekcją zdjęć. Celem aplikacji jest stworzenie prostego i intuicyjnego systemu do organizowania zdjęć, które mogą być przesyłane, sortowane, filtrowane i wyświetlane w różnych formatach.

## Funkcjonalności

- Przesyłanie zdjęć do aplikacji.
- Wyświetlanie zdjęć w formie galerii z miniaturami.
- Sortowanie i filtrowanie zdjęć według daty, tagów, rozdzielczości i innych kryteriów.
- Dodawanie i edytowanie opisów oraz tagów zdjęć.
- Możliwość usuwania zdjęć z kolekcji.

## Wymagania

- Java 11+
- Maven (do zarządzania zależnościami)
- Serwer aplikacji (np. Apache Tomcat lub Spring Boot)
- Relacyjna baza danych (np. MySQL, PostgreSQL, H2)

## Instalacja

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/Konume/galeria-zdjec.git
   cd galeria-zdjec
   ```

2. Skonfiguruj bazę danych:
   - Utwórz bazę danych o nazwie `galeria`.
   - Wprowadź odpowiednie dane logowania w pliku `application.properties`.

3. Zbuduj projekt za pomocą Mavena:
   ```bash
   mvn clean install
   ```

4. Uruchom aplikację:
   ```bash
   mvn spring-boot:run
   ```

## Użycie

1. Otwórz aplikację w przeglądarce pod adresem [http://localhost:8080](http://localhost:8080).
2. Przesyłaj zdjęcia za pomocą dostępnego interfejsu.
3. Używaj opcji sortowania, filtrowania oraz zarządzania zdjęciami, aby dostosować galerię do swoich potrzeb.

## Dokumentacja

Szczegółowe informacje na temat API, struktury bazy danych oraz diagramów UML znajdują się w katalogu `docs` w repozytorium.

## Wkład

Zachęcamy do zgłaszania sugestii oraz błędów poprzez system zgłoszeń (Issues). Pull requesty są mile widziane!

## Licencja

Projekt "Galeria Zdjęć" jest licencjonowany na warunkach licencji MIT. Szczegóły znajdują się w pliku [LICENSE](LICENSE).

---

Dziękujemy za zainteresowanie projektem i zapraszamy do jego rozwijania oraz korzystania!
