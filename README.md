# SOC
SOC – moje laboratorium cyberbezpieczeństwa. Tu eksperymentuję z analizą logów, alertami bezpieczeństwa i reakcją na incydenty, ucząc się krok po kroku, jak chronić systemy przed zagrożeniami. Projekty w tym repozytorium pokazują, że bezpieczeństwo IT to nie tylko praca, ale pasja i ciekawość świata za ekranem.
-----------------------------------------------------------------------------------------------------------------------

### **Analiza połączenia SSH**  
Celem projektu było prześledzenie procesu łączenia się zdalnego z Windows do Linux w środowisku VM, z uwzględnieniem bezpieczeństwa.
W projekcie:
- testy połączeń SSH (błędne i poprawne logowanie)
- analiza logów SSH i UFW
- konfiguracja firewall’a z polityką default deny
- diagnoza problemów sieciowych i uwierzytelnienia

Projekt pokazuje: monitorowanie logów, identyfikacja incydentów, konfiguracja zabezpieczeń i diagnostyka problemów w środowisku Linux.

-----------------------------------------------------------------------------------------------------------------------

### **Analiza incydentu phishingowego – symulacja SOC**
Badanie ataków phishingowych w środowisku symulacyjnym (TryHackMe, LetsDefend).
W projekcie:
- Identyfikacja i dokumentacja podejrzanych wiadomości e-mail
- Analiza linków i załączników w bezpiecznym sandboxie
- Ocena interakcji użytkownika i potencjalnego zagrożenia
- Analiza logów sieciowych i endpointowych
- Dokumentacja wszystkich kroków i wniosków

Projekt pokazuje: monitorowanie zagrożeń, triage incydentów, stosowanie narzędzi OSINT i analizę logów w celu ochrony użytkowników oraz infrastruktury.

-----------------------------------------------------------------------------------------------------------------------

### **Raport - analiza logów SIEM** 
   --> Analiza podejrzanego połączenia sieciowego

Raport przedstawia analizę incydentu bezpieczeństwa wykrytego w systemie SIEM na podstawie logów Sysmon. 
Analiza obejmuje identyfikację podejrzanego połączenia sieciowego wewnątrz LAN, analizę procesu podszywającego się pod legalne oprogramowanie oraz wykrycie mechanizmu persistence w postaci zaplanowanego zadania systemowego.

Projekt pokazuje: analizę logów w SIEM (Splunk), korelację zdarzeń sieciowych i procesowych oraz wykrywanie mechanizmów persistence.

-----------------------------------------------------------------------------------------------------------------------

### **Analiza ataku brute-force (WordPress)**
Projekt dotyczy analizy ataku typu brute-force na aplikację WordPress na podstawie logów serwera WWW w systemie SIEM (Splunk). Analiza obejmowała:
- identyfikację nadmiernej liczby żądań
- rozdzielenie dwóch niezależnych źródeł ataku
- ocenę metod HTTP i nagłówków User-Agent
- zidentyfikowanie użycia narzędzi automatycznych -> WPScan i Hydra

Projekt pokazuje: analizę ataków brute-force, korelację logów WWW, redukcję szumu analitycznego i podejmowanie decyzji SOC L1.

-----------------------------------------------------------------------------------------------------------------------

