# Twoje IP

Prosta strona dla GitHub Pages. Po otwarciu pobiera publiczny adres IP
odwiedzającego z usługi `api64.ipify.org` i wyświetla go na białym tle.

Usługa ipify otrzymuje żądanie potrzebne do ustalenia adresu IP. Strona nie ma
własnego backendu ani nie zapisuje adresu na serwerze projektu.

Workflow z `.github/workflows/pages.yml` publikuje zawartość katalogu `site`
po każdym pushu na gałąź `main`. W ustawieniach repozytorium w sekcji **Pages**
źródło publikacji powinno być ustawione na **GitHub Actions**.
