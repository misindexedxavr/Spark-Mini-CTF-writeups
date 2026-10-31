# 05. Alias Archaeology

**Flag:** `Spark{hikki_chan_rey}`

## Objective

Return to the KELA report and find the alias used immediately before Rey.

## Source

[KELA: Hellcat Hacking Group Unmasked: Investigating Rey and Pryx](https://www.kelacyber.com/blog/hellcat-hacking-group-unmasked-rey-and-pryx/)

## Solution

In the section titled **Who is Rey/Hikki-Chan?**, KELA states that Rey was previously known as **Hikki-Chan**.

The challenge asks for the previous handle followed by the current handle.

## Flag construction

- Previous alias: `hikki-chan`
- Current alias: `rey`

Replace the hyphen in the previous alias with an underscore and join both values.

**Flag:** `Spark{hikki_chan_rey}`

## Notes

The challenge asks for the handle immediately before Rey. Do not continue into older aliases mentioned elsewhere in the report.
