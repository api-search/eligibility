---
api_specs:
- filename: freqblog-com-audio-api-openapi.yml
  format: yaml
  label: freqblog-com Audio API
  slug: freqblog-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-audio-api-openapi.yml
- filename: freqblog-com-backfill-api-openapi.yml
  format: yaml
  label: freqblog-com Backfill API
  slug: freqblog-com-backfill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-backfill-api-openapi.yml
- filename: freqblog-com-catalog-api-openapi.yml
  format: yaml
  label: freqblog-com Catalog API
  slug: freqblog-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-catalog-api-openapi.yml
- filename: freqblog-com-me-api-openapi.yml
  format: yaml
  label: freqblog-com Me API
  slug: freqblog-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-me-api-openapi.yml
- filename: freqblog-com-request-free-key-api-openapi.yml
  format: yaml
  label: freqblog-com Request Free Key API
  slug: freqblog-com-request-free-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-request-free-key-api-openapi.yml
- filename: freqblog-com-spotify-compat-api-openapi.yml
  format: yaml
  label: freqblog-com Spotify Compat API
  slug: freqblog-com-spotify-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-spotify-compat-api-openapi.yml
- filename: freqblog-com-system-api-openapi.yml
  format: yaml
  label: freqblog-com System API
  slug: freqblog-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-system-api-openapi.yml
- filename: freqblog-com-utility-api-openapi.yml
  format: yaml
  label: freqblog-com Utility API
  slug: freqblog-com-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-utility-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer (an individual using our services wholly outside of any trade, business, or profession), your statutory rights under the Consumer Rights Act 2015 and Consumer Contracts Regulations 2013 are not affected by these terms.
    type: individual
  - text: Any use in or for a product or service that charges users, carries advertising or sponsorship, sells subscriptions or in-app purchases, or is run for a business, a client or paid work.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free keys non-commercial only
    text: A free key may be used for non-commercial purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: freqblog-com
provenance_date: '2026-11-09'
provider_name: freqblog-com
provider_slug: freqblog-com
slug: freqblog-com-eligibility
source_date: '2026-11-09'
source_filename: freqblog-com-eligibility.yml
source_heading: Eligibility
source_page: https://freqblog.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: freqblog-com\naid: freqblog-com\nurl: https://freqblog.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer (an individual using our services wholly outside of any trade, business, or profession),\n    your statutory rights under the Consumer Rights Act 2015 and Consumer Contracts Regulations 2013 are not affected\n    by these terms.\n- type: business\n  text: Any use in or for a product or service that charges users, carries advertising or sponsorship, sells subscriptions\n    or in-app purchases,\
  \ or is run for a business, a client or paid work.\nrestricted_uses:\n- summary: Free keys non-commercial only\n  text: A free key may be used for non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/freqblog-com/eligibility/freqblog-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from freqblog-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Audio
- Metadata
---
