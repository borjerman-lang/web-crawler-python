# Web Crawler Python

Preprost Python web crawler, ki obiskuje spletne strani, izlušči naslov (`title`) in besedilo strani ter izpiše rezultate v terminal.

## Kaj naredi

- sprejme URL kot vhod
- naredi HTTP zahtevo
- prenese HTML vsebino
- uporablja BeautifulSoup za razčlenjevanje HTML
- izlušči naslov strani in primerno besedilo
- izpiše rezultat v terminal

## Predpogoji

- Python 3.10+
- internetna povezava

## Namestitev

1. Odpri PowerShell ali terminal.
2. Pojdi v mapo projekta:

```powershell
cd C:\Users\jerma\web-crawler-python
```

3. Ustvari virtualno okolje:

```powershell
python -m venv .venv
```

4. Aktiviraj virtualno okolje:

```powershell
.\.venv\Scripts\Activate.ps1
```

Če se pojavi napaka zaradi omejitve izvajanja skriptov, uporabi:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\.venv\Scripts\Activate.ps1
```

5. Namesti odvisnosti:

```powershell
python -m pip install -r requirements.txt
```

## Zagon

```powershell
python crawler.py https://example.com
```

Ali:

```powershell
python crawler.py
```

Potem vnesi URL, npr.:

```text
https://example.com
```

## Primer izhoda

```text
Najdeno 1 strani.
URL: https://example.com
Title: Example Domain
Text: Example Domain This domain is for use in documentation examples without needing permission.
```

## Opomba

Ta projekt je namenjen učenju in osnovnem pregledu HTML vsebine. Uporabljaj ga le za dovoljene in zakonite namene.

## Licenca

Ta projekt je brez posebne licence in je namenjen za osebno uporabo in učenje.
