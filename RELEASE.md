# Fala: release checklist

Stan na 24.10.2026. Strona gotowa lokalnie (landing, privacy, support), `fit-audit` → ALL SCENES FIT, `phone-audit` → ALL PHONE LAYOUTS FIT.

## Do potwierdzenia z aplikacją
- [ ] Cennik: Free (pudełkowy, dłuższy wydech, Dziś, łąka, Pierwszy tydzień, tryb nocny, widżety, przypomnienia) i **Fala Premium** miesięcznie/rocznie. Strona nie podaje kwot.
- [ ] Privacy: po podpięciu **RevenueCat** dopisać sekcję jak w Ringbox (RevenueCat Privacy Policy, anonimowy identyfikator) i zmienić datę.
- [ ] Paywall obiecuje „Dźwięki natury w tle” — strona ich nie wymienia. Usunąć z paywalla albo dodać funkcję.
- [ ] Aplikacja: `ProfileView.privacyURL` → `https://bashubb.com/fala/privacy/`, `helpURL` → `mailto:bashubb.dev@gmail.com` (strona podaje ten adres).

## Na stronie
- [ ] Repo `bashubb/fala` (tworzy właściciel), push, Pages: main /docs.
- [ ] Link do App Store: podmień `https://apps.apple.com/us/search?term=Fala%20breathing` we wszystkich `data-store-link`.
- [ ] `<html data-store="soon">` → `"live"` w `index.html`.
- [ ] Baner Safari: `<meta name="apple-itunes-app" content="app-id=XXXXXXXXXX">`.
- [ ] Film pionowy (opcjonalnie) → sekcja `film-intro` na telefonach.
- [ ] Podbić `?v=` przy zmianach CSS/JS, sprawdzić na żywo.

## bashubb.com (repo `Bashubb`)
- [ ] Karta Fala w **Coming soon**, JSON-LD, `sitemap.xml`.

## App Store Connect
- [ ] Privacy Policy URL: `https://bashubb.com/fala/privacy/`
- [ ] Support URL: `https://bashubb.com/fala/support/`
- [ ] Marketing URL: `https://bashubb.com/fala/`
