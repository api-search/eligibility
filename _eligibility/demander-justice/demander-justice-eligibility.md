---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: La saisine du Tribunal est gratuite en France et ne nécessite pas de représentation par un avocat.
  minimum_age:
    text: null
    value: null
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
name: Demander Justice
provenance_date: '2026-11-09'
provider_name: Demander Justice
provider_slug: demander-justice
slug: demander-justice-eligibility
source_date: '2026-11-09'
source_filename: demander-justice-eligibility.yml
source_heading: Eligibility
source_page: https://www.demanderjustice.com/mentions-legales
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Demander Justice\naid: demander-justice\nurl: https://www.demanderjustice.com/mentions-legales\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: La saisine du Tribunal est gratuite en France et ne nécessite pas de représentation par un avocat.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/demander-justice/eligibility/demander-justice-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Demander Justice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Legal
- Legal Tech
- Justice
- Dispute Resolution
- France
- Access to Justice
---
