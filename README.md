# Rey Case: OSINT Challenge Writeups

Writeups for the six-part Rey OSINT chain created for engineers spark Mini CTF.

The chain follows public reporting around the aliases Rey and Pryx, the Hellcat ransomware group, and the later name Scattered LAPSUS$ Hunters. It documents the intended solve path, the sources used, and how each flag is constructed.

## Rules and scope

- Use public security news and threat-intelligence reports only.
- Do not visit leak sites or search for stolen credentials.
- Do not collect, publish, or submit personal details about private individuals.
- Treat allegations and reported claims as allegations. Detention is not a conviction.
- Flags contain only a public alias, group name, tool name, or country.

## Challenges

| # | Challenge | Flag |
|---|---|---|
| 01 | [Newest Trace](02-writeups/01-newest-trace.md) | `Spark{rey_jordan}` |
| 02 | [The Co-Founder](02-writeups/02-the-co-founder.md) | `Spark{hellcat_pryx}` |
| 03 | [Group to Victim](02-writeups/03-group-to-victim.md) | `Spark{schneider_electric_lumma}` |
| 04 | [One Banner, Three Names](02-writeups/04-one-banner-three-names.md) | `Spark{scattered_lapsus_hunters}` |
| 05 | [Alias Archaeology](02-writeups/05-alias-archaeology.md) | `Spark{hikki_chan_rey}` |
| 06 | [Case Closed](02-writeups/06-case-closed.md) | `Spark{ica_group}` |

## Investigation flow

```text
Newest Trace
    |
    v
The Co-Founder
    |
    v
Group to Victim
    |
    v
One Banner, Three Names
    |
    v
Alias Archaeology
    |
    v
Case Closed
```

The first challenge gives the public alias Rey and the country Jordan. KELA's report then connects Rey to Hellcat and Pryx. The next challenges use public reporting to identify a victim and infostealer, the later collective name, Rey's previous alias, and Hellcat's original name.

## Repository layout

```text
.
├── README.md
├── 01-investigation/
│   ├── methodology.md
│   ├── timeline.md
│   └── chain-overview.md
├── 02-writeups/
│   └── six challenge writeups
├── 03-evidence/
│   ├── sources.md
│   └── evidence-log.md
└── 04-ctf-files/
    └── Rey Case/
        ├── 01/ ... 06/
        └── challenge.yml and Solution/writeup.md
```

## Revisions reflected here

These writeups use the revised challenge versions, not the outdated values in the original uploaded YAML:

- Challenge 04 asks only for the collective name. The administrator count was removed.
- Challenge 04 uses `Spark{group_name}` as its format.
- Challenge 06 asks only for Hellcat's original name. The date calculation was removed.
- Challenge 06 uses the KELA report only.
- The final Challenge 06 flag is `Spark{ica_group}`.

## Disclaimer

This is an educational OSINT challenge writeup based on public reporting. It is not an independent attribution report. It does not validate every claim made by the cited sources and intentionally excludes personal identifying information about private individuals.
