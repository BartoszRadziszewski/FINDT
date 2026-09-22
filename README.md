# FIN DT – Academic Research Hub

[![GitHub Pages](https://img.shields.io/badge/Live_Demo-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://bartoszradziszewski.github.io/FINDT/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

**FIN DT – Academic Research Hub** to autonomiczny, interaktywny dashboard badawczy (Single-Page Application zapisany w jednym pliku HTML), funkcjonujący jako spersonalizowane repozytorium zasobów naukowych.

Projekt zawiera wyselekcjonowaną i dynamicznie filtrowaną bazę narzędzi analitycznych, bibliotek sztucznej inteligencji, silników symulacyjnych oraz akademickich baz literaturowych.

🔗 **Wersja online (Live Demo):** [https://bartoszradziszewski.github.io/FINDT/](https://bartoszradziszewski.github.io/FINDT/)

---

## 🎯 Cel badawczy

Głównym celem projektu jest operacyjne wsparcie procesu badawczego rozprawy doktorskiej poprzez centralizację technologii i źródeł niezbędnych do pracy w interdyscyplinarnym obszarze łączącym:

* **DSRM** (*Design Science Research Methodology*) – usystematyzowane podejście badawcze stosowane w naukach o systemach informacyjnych, inżynierii i zarządzaniu (według frameworku Peffers et al., 2007).
* **BPM** (*Business Process Management*) – zaawansowane modelowanie, analiza i optymalizacja procesów biznesowych (z uwzględnieniem koncepcji Dynamic BPM Szelągowskiego oraz Process Mining van der Aalsta).
* **DT** (*Digital Twin*) – projektowanie i ewaluacja cyfrowych bliźniaków procesów organizacyjnych (FlexSim, Discrete Event Simulation).
* **AI Agents & Reinforcement Learning** – wieloagentowe systemy decyzyjne (CrewAI, Ray/RLlib, Gymnasium, Stable-Baselines3, PettingZoo).
* **FIN / FINC** (*Finance and Controlling*) – modelowanie rentowności, wirtualny P&L i ocena zwrotu z inwestycji (Power BI, python/statsmodels).
* **BPNAF** (*Business Process Nature Assessment Framework*) – wielowymiarowa ocena natury, ustrukturyzowania i podatności procesów na automatyzację kognitywną.

## 🌐 Wyszukiwanie, Identyfikatory Naukowców i Publikacji (Multi-Resolver)

Dashboard został wyposażony w zintegrowany **Akademicki Multi-Resolver** oraz wyszukiwarkę tokenową obsługującą kluczowe międzynarodowe standardy identyfikacji badaczy oraz publikacji naukowych:

### 1. Globalne wyszukiwarki akademickie i profile naukowców:
* **Google Scholar & Citations:** Pełnotekstowe przeszukiwanie publikacji, monografii, dysertacji i cytowań w Google Scholar oraz natychmiastowe otwieranie profili cytowań i wskaźników bibliometrycznych badaczy (h-indeks, i10-indeks, np. profil prof. Wila van der Aalsta `aSZZ5xYAAAAJ`, prof. Marka Szelągowskiego `Y992cM4AAAAJ`).
* **ORCID** (*Open Researcher and Contributor ID*): Trwały, unikalny 16-cyfrowy identyfikator cyfrowy badacza (np. `0000-0002-3860-2975` dla Marka Szelągowskiego, `0000-0002-0955-6940` dla Wila van der Aalsta, `0000-0002-8692-0691` dla Kena Peffersa).
* **Scopus Author ID** (*Elsevier*): Numeryczny unikatowy identyfikator profilu autora w bazie Scopus (np. `57193739775`, `55353163300`, `7004452140`), powiązany z h-indeksem i cytowaniami w Elsevier.
* **ResearcherID** (*Web of Science / Clarivate*): Unikalny identyfikator autora w bazie Web of Science Core Collection (np. `AAH-4279-2021`, `A-3804-2008`, `B-5291-2013`, `H-3129-2011`).

### 2. Międzynarodowa numeracja publikacji naukowych:
* **DOI System** (*Digital Object Identifier*): Oficjalny cyfrowy identyfikator artykułów, rozdziałów i zbiorów danych (np. `10.17705/1jais.00140`, `10.1093/nar/gkw365`) z bezpośrednim rozwiązywaniem przez `doi.org` i CrossRef.
* **Portal ISSN** (*International Standard Serial Number*): 8-cyfrowy standard numeracji czasopism naukowych i wydawnictw ciągłych (np. `1463-7154` dla *Business Process Management Journal*, `1536-9323` dla *JAIS*).
* **ISBN Search** (*International Standard Book Number*): Międzynarodowy standard numeracji książek i monografii naukowych (np. `978-3-540-28895-4`).
* **arXiv.org:** Identyfikator preprintów i e-printów otwartej nauki (np. `2005.05719`, `1712.05889`, `1606.01540`).

### 3. Funkcje Multi-Resolvera:
* **⚡ Inteligentne dopasowanie (Smart Resolver):** Automatycznie rozpoznaje po wyrażeniu regularnym, czy wklejony ciąg to Google Scholar Citations, ORCID, Scopus Author ID, ResearcherID, DOI, ISSN, ISBN czy arXiv, i natychmiast otwiera właściwy rejestr. W przypadku wpisania ogólnej frazy badawczej automatycznie kieruje zapytanie do Google Scholar.
* **Lokalne filtrowanie tokenowe:** Wpisanie dowolnego identyfikatora, nazwiska lub imienia w panelu bocznym natychmiast filtruje wewnętrzną bazę 26 wyselekcjonowanych zasobów.
* **Interaktywne odznaki:** Każda karta prezentuje klikalne odznaki referencyjne (Google Scholar, ORCID, Scopus ID, ResearcherID, DOI, ISSN, ISBN, arXiv).

---

## 🔬 Struktura kategoryzacji (Filtry)

Dashboard umożliwia wielowymiarowe filtrowanie źródeł w oparciu o:

1. **Typ zasobu:**
   * Przegląd literatury / Baza bibliograficzna (Scopus, Web of Science, IEEE Xplore, arXiv, BPMJ, OMG)
   * Silniki symulacyjne / Biblioteki AI (FlexSim, Gymnasium, Stable-Baselines3, Ray/RLlib, CrewAI, PM4Py, ProM, Python, PettingZoo)
   * Narzędzia DSRM / Walidacja empiryczna (Rayyan, VOSviewer, Power BI, Connected Papers, Litmaps, Peffers Framework, Qualtrics, Miro)
   * Repozytoria event logów / Benchmarki (4TU.ResearchData / BPI Challenges, Kaggle)

2. **Faza badawcza (FIN DT):**
   * *Faza I: SLR (PRISMA 2020)* – systematyczny przegląd literatury i identyfikacja luk badawczych (L1–L8).
   * *Faza II: Case Studies / Symulacje (TRL 4-5)* – kalibracja modeli procesowych i trening agentów decyzyjnych.
   * *Faza III: Artefakt 3D-BPNAF (DSRM)* – konstrukcja i ewaluacja artefaktu badawczego.
   * *Faza IV: Walidacja ekspercka (Delphi)* – zewnętrzna ocena modelu i procedur w panelach eksperckich.

3. **Wymiar projektu:**
   * *Dynamic BPM & BPNAF*
   * *AI Agents & Reinforcement Learning*
   * *Digital Twins & FlexSim/PowerBI*
   * *Dynamic Capabilities (Teece)*

4. **Model dostępu:**
   * *Open Access* / *Open Source* / *Freemium* / *Wymaga licencji akademickiej* / *Komercyjne*

---

## 🚀 Uruchomienie lokalne

Plik nie wymaga żadnych zależności, kompilatorów ani serwerów Node.js/Python:

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/BartoszRadziszewski/FINDT.git
   ```
2. Otwórz plik `index.html` w dowolnej przeglądarce internetowej (Chrome, Edge, Firefox, Safari).

---

## 👤 Autor

**Bartosz Radziszewski**  
GitHub: [@BartoszRadziszewski](https://github.com/BartoszRadziszewski)  
Projekt: FIN DT – Academic Research Hub
