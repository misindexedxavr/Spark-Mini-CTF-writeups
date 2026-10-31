# 01. Newest Trace

**Flag:** `Spark{rey_jordan}`

## Objective

Find the public handle mentioned in the report and the country associated with it.

## Source

[SecurityWeek: Alleged ShinyHunters Leader Arrested in Jordan](https://www.securityweek.com/alleged-shinyhunters-leader-arrested-in-jordan/)

## Solution

The article headline names Jordan. Its opening section refers to the subject by the public handle **Rey**.

The challenge asks for the handle and country only. No private identity details are needed.

## Flag construction

- Public handle: `rey`
- Country: `jordan`

Combine both values in lowercase with an underscore.

**Flag:** `Spark{rey_jordan}`

## Notes

The article uses qualified language such as "alleged" and "reportedly". This writeup does not treat those statements as a conviction or proof of every allegation.
