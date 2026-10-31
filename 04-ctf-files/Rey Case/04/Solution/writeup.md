# 04. One Banner, Three Names

**Flag:** `Spark{scattered_lapsus_hunters}`

## Objective

Find the full name of the Telegram group described in a November 2025 article.

## Source

[KrebsOnSecurity: Meet Rey, the Admin of 'Scattered Lapsus$ Hunters'](https://krebsonsecurity.com/2025/11/meet-rey-the-admin-of-scattered-lapsus-hunters/)

## Solution

The article title gives the collective's name: **Scattered LAPSUS$ Hunters**.

The opening section explains that the name combines three threat-actor brands:

- Scattered Spider
- LAPSUS$
- ShinyHunters

The revised challenge asks only for the group's name. The administrator-count requirement was removed, so no counting is needed.

## Flag construction

Convert the name to lowercase, replace spaces with underscores, and remove the `$` symbol.

`Scattered LAPSUS$ Hunters` becomes `scattered_lapsus_hunters`.

**Flag:** `Spark{scattered_lapsus_hunters}`

## Notes

Only the public collective name is needed. Additional personal details in the article are outside the scope of this challenge and are not reproduced here.
