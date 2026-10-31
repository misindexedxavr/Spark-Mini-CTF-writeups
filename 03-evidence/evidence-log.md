# Evidence Log

| Challenge | Evidence | Interpretation | Output |
|---|---|---|---|
| 01 | SecurityWeek headline and article body | Public alias Rey; country Jordan. | `rey_jordan` |
| 02 | KELA report title | Group Hellcat; co-founder alias Pryx. | `hellcat_pryx` |
| 03 | InfoStealers headline and "The Infostealer Connection" section | Victim Schneider Electric; employee-device stealer Lumma. | `schneider_electric_lumma` |
| 04 | KrebsOnSecurity headline and opening section | Collective named Scattered LAPSUS$ Hunters. | `scattered_lapsus_hunters` |
| 05 | KELA section "Who is Rey/Hikki-Chan?" | Rey was previously known as Hikki-Chan. | `hikki_chan_rey` |
| 06 | KELA original report introduction | Hellcat was originally known as ICA Group. | `ica_group` |

## Normalization

- Use lowercase.
- Replace spaces and hyphens with underscores where required.
- Remove the `$` symbol from the collective name.
- Do not add information that the challenge does not request.
