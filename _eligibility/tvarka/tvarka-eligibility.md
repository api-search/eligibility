---
api_specs:
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-atk-api-tvarka-atk-api-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK QES Signing API (paid Tier Addendum) API
  slug: tvarka-atk-api-tvarka-atk-qes-signing-api-paid-tier-addendum-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: tvarka-sign-api-openapi.yml
  format: yaml
  label: Tvarka Sign API
  slug: tvarka-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-sign-api-openapi.yml
- filename: tvarka-auth-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Auth API
  slug: tvarka-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-auth-api-openapi.yml
- filename: tvarka-batches-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Batches API
  slug: tvarka-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-batches-api-openapi.yml
- filename: tvarka-erasure-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Erasure API
  slug: tvarka-erasure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-erasure-api-openapi.yml
- filename: tvarka-files-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Files API
  slug: tvarka-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-files-api-openapi.yml
- filename: tvarka-ltv-api-openapi.yml
  format: yaml
  label: Tvarka ATK API LTV API
  slug: tvarka-ltv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-ltv-api-openapi.yml
- filename: tvarka-pairing-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Pairing API
  slug: tvarka-pairing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-pairing-api-openapi.yml
- filename: tvarka-signings-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Signings API
  slug: tvarka-signings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-signings-api-openapi.yml
- filename: tvarka-tvarka-atk-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-tvarka-atk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-atk-api-api-openapi.yml
- filename: tvarka-tvarka-sign-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka Sign API
  slug: tvarka-tvarka-sign-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-sign-api-api-openapi.yml
- filename: tvarka-validation-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Validation API
  slug: tvarka-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-validation-api-openapi.yml
- filename: tvarka-well-known-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Well Known API
  slug: tvarka-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-well-known-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Tvarka, išskyrus 16 skyriuje nurodytą Nemokamą planą ir 18 skyriuje nurodytas asmenines el. pašto paskyras, neskirta vartotojams (B2C).
    type: business
  - text: Fizinis asmuo gali sukurti el. pašto Paskyrą ir naudotis Tvarka Sign savo dokumentams be ryšio su įmone.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free plan personal use only
    text: Nemokamu planu galima naudotis tik asmeniniais (ne verslo ar profesinės veiklos) tikslais
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Prisijungiama atitinkamai Paslaugai siūlomu autentifikavimo būdu: elektroninės tapatybės priemone (pavyzdžiui, LT ID, Smart-ID, Mobile-ID ar asmens tapatybės kortele) arba vienkartine el. pašto nuoroda'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tvarka ATK API
provenance_date: '2026-11-10'
provider_name: Tvarka ATK API
provider_slug: tvarka
slug: tvarka-eligibility
source_date: '2026-11-10'
source_filename: tvarka-eligibility.yml
source_heading: Eligibility
source_page: https://tvarka.pro/salygos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tvarka ATK API\naid: tvarka\nurl: https://tvarka.pro/salygos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Tvarka, išskyrus 16 skyriuje nurodytą Nemokamą planą ir 18 skyriuje nurodytas asmenines el. pašto paskyras,\n    neskirta vartotojams (B2C).\n- type: individual\n  text: Fizinis asmuo gali sukurti el. pašto Paskyrą ir naudotis Tvarka Sign savo dokumentams be ryšio su įmone.\nrestricted_uses:\n- summary: Free plan personal use only\n  text: Nemokamu planu galima naudotis tik asmeniniais (ne verslo ar profesinės veiklos) tikslais\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Prisijungiama atitinkamai Paslaugai siūlomu autentifikavimo būdu: elektroninės tapatybės priemone (pavyzdžiui,\n    LT ID, Smart-ID, Mobile-ID ar asmens tapatybės kortele) arba vienkartine el. pašto nuoroda'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tvarka/eligibility/tvarka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Tvarka ATK API's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- Digital Signature
- eIDAS
- QES
- Lithuania
- OpenAPI
- eID
- Smart-ID
- Mobile-ID
- NFC
- Timestamping
- LTV
- Webhook
- Identity
- Trust Services
- GDPR
---
