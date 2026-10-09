# Daily job-search workflow

## Scope

Use the current Europe/Amsterdam date. Search the seven core countries every day:

- Netherlands
- Switzerland
- Belgium
- Luxembourg
- Norway
- Denmark
- Sweden

Add the weekday rotation:

| Day | Additional countries |
|---|---|
| Monday | United Kingdom and Ireland |
| Tuesday | Germany and Austria |
| Wednesday | France and Italy |
| Thursday | Portugal and Spain |
| Friday | Poland and Romania |
| Saturday | United Kingdom, Germany and promising offshore leads |
| Sunday | Priority revalidation and broader company/agency discovery |

Follow useful European leads without replacing the seven-country baseline.

## Search order

For every country:

1. Search `rope access jobs <country>` in plain English.
2. Search `IRATA jobs <country>` separately in plain English.
3. Search useful local terms and geography.
4. Check known productive employers, specialist agencies and portals.
5. Check rigging, scaffolding, mechanical, industrial, shutdown, offshore and wind variants.
6. Check hidden blade, LPS and composite requirements.
7. Open the actual advert and verify employer, title, locality, scope, requirements, status and application route.

Translations do not replace the two English searches. Treat blocked or unclear sources as limitations, not empty markets.

## Candidate fit

Use [the public search profile](search-profile.md). Do not infer Level 2, driving licence, offshore experience, coatings experience, languages, tickets, location or work permission. Keep useful stretch roles, but state the missing requirements clearly.

## Verification and deduplication

Compare the full current [job index](../data/job-index.md) using canonical URL/job ID plus employer, role, locality, scope and campaign. Mirrors, translations and reposts of one campaign are one job. Separate live adverts from expired posts, generic pools and unclear hiring. Never fabricate findings or requirements.

## Simple publication rule

Each completed run produces exactly one dated public job list:

- Path: `daily/YYYY-MM-DD.md`
- Content: newly verified jobs only, grouped by country
- Each job: role, employer, direct advert link, locality/scope, fit and the shortest useful caveat
- No separate research report, receipt log, query log, metrics section or final-receipt commit
- Do not update `research/`; it is a historical archive
- Do not update a dated manifest after every run
- If the same-date daily file already exists, merge into that file rather than creating a duplicate
- If a completed run finds no new verified jobs, publish one short dated file saying so and name the countries searched

Update `data/job-index.md` quietly for verified new stable IDs and evidenced status changes. Preserve all historical IDs. Validate changed files after writing, but do not publish validation receipts or commit hashes in the daily report or user-facing summary.

## Safety

GitHub is the sole operational destination. Do not write to Notion. Do not publish names, contact details, CV material, private history, application data, private notes or internal archive links. Do not apply, contact employers, purchase anything or change repository permissions.
