# 03. Group to Victim

**Flag:** `Spark{schneider_electric_lumma}`

## Objective

Identify the organization named as a Hellcat victim and the infostealer linked to an employee machine.

## Source

[InfoStealers: Schneider Electric Hacked and Blackmailed Following Lumma Infostealer Infection](https://www.infostealers.com/article/schneider-electric-hacked-and-blackmailed-due-to-lumma-infostealer-infection/)

## Solution

The headline identifies **Schneider Electric**.

The section titled **The Infostealer Connection** states that Hudson Rock researchers identified a Schneider Electric employee machine infected with **Lumma Infostealer**.

The challenge asks for the stealer found on the employee machine. It specifically says to ignore stealers linked to the operators' own devices, so the answer comes from this employee-device finding.

## Flag construction

- Victim: `schneider_electric`
- Infostealer: `lumma`

Combine the values in the requested order.

**Flag:** `Spark{schneider_electric_lumma}`

## Notes

The article reports a link between the infected employee machine and the incident. This writeup attributes that finding to the researchers and does not claim that every detail of the intrusion is independently established by this article.
