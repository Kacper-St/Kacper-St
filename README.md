# Cześć, jestem Kacper 👋

Studiuję **inżynierię oprogramowania** i rozwijam się w technologiach związanych z **Javą**. Obecnie buduję własne projekty backendowe i szukam możliwości postawienia swoich pierwszych kroków w branży IT.

---

## 🔧 Stack Techniczny

- **Backend:** Java 21, Spring Boot 4.x, Spring Security, Spring Data JPA, Spring Mail, Spring Retry
- **Bazy Danych:** PostgreSQL, PostGIS, Hibernate, Flyway, MinIO (S3), SQL
- **Narzędzia & DevOps:** Docker, Git, Maven, Postman, MapStruct, Lombok

---

## 🚀 Nad czym pracuję

### [Wolfship – System Kurierski (Backend)](https://github.com/Kacper-St/Wolfship)
Kompleksowy system klasy Enterprise obsługujący pełny cykl życia przesyłki. To mój główny projekt, w którym zaimplementowałem:

* **Architektura Modularnego Monolitu:** Pełna separacja 7 modułów komunikujących się asynchronicznie poprzez **Spring Events**, co pozwala na łatwą migrację do mikroserwisów.
* **Zaawansowana Logistyka:** Algorytm wyznaczania tras oparty o **Dijkstrę** na grafie 10 hubów z rozpoznawaniem stref geograficznych (ponad 380 powiatów) przy użyciu **PostGIS**.
* **Automatyzacja & Procesy:** * Generowanie etykiet PDF z kodami QR i pełny flow powiadomień mailowych.
    * System automatycznego przypisywania kurierów strefowych do odbioru i doręczenia.
    * Geokodowanie adresów z wykorzystaniem **Nominatim**.
* **Infrastructure as Code:** Pełna konteneryzacja środowiska (PostgreSQL, MinIO, pgAdmin) za pomocą **Docker**.
