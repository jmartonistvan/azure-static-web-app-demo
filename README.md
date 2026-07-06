# APS ACC Demo Static Site

Ez egy egyszerű statikus demóoldal Azure Static Web Apps-hoz.

## Fájlok
- `index.html`
- `staticwebapp.config.json`

## Azure Static Web Apps beállítás
- Framework: `No Framework`
- App location: `/`
- API location: üres
- Output location: üres

## Bejelentkezés és védett tartalom
- A weboldal minden tartalma csak hitelesített felhasználók számára érhető el.
- A Microsoft Entra ID bejelentkezést az Azure Static Web Apps `.auth/login/aad` útvonalon kezdeményezi.
- A főoldalon megjelenik a bejelentkezett felhasználó neve, ha sikeres a belépés.
