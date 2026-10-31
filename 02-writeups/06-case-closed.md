# 06. Case Closed

**Flag:** `Spark{ica_group}`

## Objective

Find the original name used by Hellcat.

## Source

[KELA: Hellcat Hacking Group Unmasked: Investigating Rey and Pryx](https://www.kelacyber.com/blog/hellcat-hacking-group-unmasked-rey-and-pryx/)

## Solution

In the opening section of the original KELA report, the article states that Hellcat was originally known as **ICA Group**.

The revised challenge asks only for the earlier group name. The date calculation has been removed, so there is no need to compare publication dates or use the Schneider Electric claim date.

## Flag construction

- Original group name: `ICA Group`
- Lowercase and replace the space with an underscore: `ica_group`

**Flag:** `Spark{ica_group}`

## Notes

Use the KELA report only. The InfoStealers article was needed for the previous date-calculation version, but it is no longer required.
