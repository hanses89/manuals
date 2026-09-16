# manuals.hanses.no

Brukarmanualar for appane, opne for alle – i motsetnad til
[docs.hanses.no](https://docs.hanses.no), som er intern og teknisk.

Sidene blir **synka hit frå prosjekta**. Rediger dei i prosjektet, ikkje her:

| Side | Kjelde |
|---|---|
| `docs/bagtag.md` | `hanses89/bagtag.kvamdgs.no` → `docs/brukarmanual.md` |

Kvart prosjekt har ein `sync-manual.yml` som dyttar fila hit ved push til
`main`. Nye sider må leggjast inn i `nav:` i `mkdocs.yml` for hand.

Deploy: push til `main` → GitHub Pages (`mkdocs gh-deploy`).
