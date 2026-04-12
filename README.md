# Conquer Your Tasks (2026) by Wojtek Kociuba, 100241
Projekt natywnej aplikacji chmurowej realizowany w architekturze 3-warstwowej.
 
## Deklaracja Architektury (Mapowanie Azure)

Ten projekt został zaplanowany z myślą o usługach PaaS (Platform as a Service) w chmurze Azure.
 
| Warstwa | Komponent Lokalny | Usługa Azure |

| :--- | :--- | :--- |

| **Presentation** | React 19 (Vite) | Azure Static Web Apps |

| **Application** | API (.NET 9 / Node 24) | Azure App Service |

| **Data** | SQL Server (Dev) | Azure SQL Database (Serverless) |
 
 ## Status Projektu
* [x] **Artefakt 1:** Architektura i struktura folderów.
* [x] **Artefakt 2:** Środowisko wielokontenerowe uruchomione lokalnie (Docker Compose).
* [x] **Artefakt 3:** Działająca warstwa prezentacji.
* [x] **Artefakt 4:** Działająca warstwa logiki backendu
* [x] **Artefakt 5:** System gotowy na chmurę
* [x] **Artefakt 6:** Backend i frontend działający z Azure.
* [x] **Artefakt 7:** Bezpieczeństwo i skalowane skonfigurowane 1/2.

## Adres Aplikacji: https://cloud-task-manafer-frontend-c8f5d7cwa8a0gchf.polandcentral-01.azurewebsites.net

> **Informacja:** Ten plik będzie ewoluował. W kolejnych etapach dodamy tutaj sekcje 'Quick Start', opis zmiennych środowiskowych oraz instrukcję wdrożenia (CI/CD).
 
