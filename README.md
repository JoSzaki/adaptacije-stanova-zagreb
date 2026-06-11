# adaptacije-stanova-zagreb

Goran Ključarić – KLJUČ adaptacije – Zagreb – adaptacije stanova.  
Live: **adaptacije-stanova-zagreb.com** · Hosting: Vercel · Repo: `JoSzaki/adaptacije-stanova-zagreb`

---

## Kontakt form – kako radi

Forma koristi **[FormSubmit.co](https://formsubmit.co)** – besplatna usluga, nema registracije, nema backenda.

```html
<form action="https://formsubmit.co/info@superprofik.com" method="POST">
```

Svaki poslan upit stiže na **info@superprofik.com** kao običan email.

### Skrivena polja (konfiguracija)

| Polje | Vrijednost | Što radi |
|-------|-----------|----------|
| `_subject` | `Novi upit – adaptacije-stanova-zagreb.com` | Naslov emaila |
| `_captcha` | `false` | Isključuje captcha |
| `_template` | `table` | Email dolazi kao lijepa tablica |
| `_next` | `https://www.adaptacije-stanova-zagreb.com/?poslan=1` | Redirect nakon slanja |

### Aktivacija (samo prvi put)

1. Netko pošalje prvi upit kroz formu
2. FormSubmit šalje **aktivacijski email** na `info@superprofik.com`
3. Klikni "Confirm" u tom emailu
4. Od tog trenutka svi upiti stižu normalno

> Ako aktivacijski email ne stigne – provjeri spam folder.

---

## Stranice

- `index.html` – glavni one-pager (verzija 2 promovirana u root)
- `version1/` – čisti profesionalni (tamnoplavi) stil s tabličnim cjenikom
- `version2/` – arhivska verzija

## Kontakt

Goran Ključarić · +385 99 528 3280
