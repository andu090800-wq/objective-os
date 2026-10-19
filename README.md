# Objective OS — MVP 1

Aplicație PWA în română, dark mode, cu 28 de obiective preîncărcate, indicatori numerici, obiceiuri, calendar 24/48 și export/import JSON.

## Testare pe calculator

1. Dezarhivează fișierul.
2. Instalează Python 3 dacă nu este deja instalat.
3. Deschide un terminal în folderul `objective-os`.
4. Rulează `python3 -m http.server 8000` (pe Windows poate fi `py -m http.server 8000`).
5. Accesează `http://localhost:8000`.

## iPhone

Pentru instalare pe iPhone, publică folderul pe un serviciu de găzduire statică cu HTTPS (de exemplu Netlify Drop sau GitHub Pages). Deschide adresa în Safari, apoi Share > Add to Home Screen.

## Limitări MVP

- Datele sunt stocate numai local în browser, fără sincronizare. Exportă copii de siguranță regulat.
- Indicatorii inițiali pentru tracțiuni și alergare sunt estimativi și trebuie ajustați la nivelul real.
- Progresul general este o medie neponderată; nu reflectă importanța obiectivelor.
- Obiceiurile zilnice sunt bifabile, dar încă nu actualizează automat indicatorii cumulativi ai obiectivelor.
- SMART/DUMB detaliat, etape personalizabile, istoric numeric și grafice avansate urmează în versiuni viitoare.
