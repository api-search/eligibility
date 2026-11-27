---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Create an account or post any content if you are not over 13 years of age years of age;
    value: '13'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: Impersonate or post on behalf of any person or entity or otherwise misrepresent your affiliation with a person or entity;
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
name: Campflare
provenance_date: '2026-11-09'
provider_name: Campflare
provider_slug: campflare
slug: campflare-eligibility
source_date: '2026-11-09'
source_filename: campflare-eligibility.yml
source_heading: Eligibility
source_page: https://campflare.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campflare\naid: campflare\nurl: https://campflare.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: Impersonate or post on behalf of any person or entity or otherwise misrepresent your affiliation with a\n    person or entity;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Create an account or post any content if you are not over 13 years of age years of age;\n"
source_yaml_url: https://artifacts.apis.io/campflare/eligibility/campflare-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Campflare's own page on 2026-11-09.
synthetic: false
tags:
- Campgrounds
- Outdoor
- Recreation
- Availability
- Alerts
- Webhook
- Reservations
---
