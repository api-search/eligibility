---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Libre.fm is hosted in the United Kingdom.
  entity_types:
  - text: You must be at least 18 years old to use Libre.fm
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use Libre.fm
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Creating a Libre.fm account requires you provide a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Libre.fm
provenance_date: '2026-11-09'
provider_name: Libre.fm
provider_slug: libre-fm
slug: libre-fm-eligibility
source_date: '2026-11-09'
source_filename: libre-fm-eligibility.yml
source_heading: Eligibility
source_page: https://libre.fm/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Libre.fm\naid: libre-fm\nurl: https://libre.fm/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Libre.fm is hosted in the United Kingdom.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Libre.fm\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Creating a Libre.fm account requires you provide a valid email address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Libre.fm\n"
source_yaml_url: https://artifacts.apis.io/libre-fm/eligibility/libre-fm-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Libre.fm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Open Source
- Scrobbling
- Community
---
