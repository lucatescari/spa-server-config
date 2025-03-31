# SPA Server Config

Konfigurationsbeispiele für Apache und Nginx, um Angular Single Page Applications (SPA) korrekt zu betreiben.

## Warum dieses Repo?

Angular-SPAs benötigen spezielle Rewrite-Regeln, damit clientseitige Routen auch beim Neuladen oder direktem Aufruf im Browser korrekt funktionieren. Dieses Repo enthält Konfigurationsbeispiele für:

- Apache (`.htaccess`)
- Nginx (`angular.conf`)

## Struktur
- ```apache/.htaccess``` → Für Apache-Server
- ```nginx/angular.conf``` → Beispielkonfiguration für Nginx-Server

## Hinweis
Diese Konfigurationen funktionieren für alle modernen Frontend-Frameworks, die als SPA laufen, z. B. Angular, React, Vue etc.