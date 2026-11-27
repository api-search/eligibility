---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Globe Properties, you are affirming that you are at least 18 years old or of legal age of majority in your jurisdiction of residence
    type: individual
  minimum_age:
    text: Globe Properties are not intended for children under the age of 18 and no person under the age of 18 may use Globe Properties.
    value: '18'
  restricted_uses:
  - summary: Under-18 use
    text: no person under the age of 18 may use Globe Properties.
  - summary: AI training on Globe Properties data
    text: use any data contained in or obtained from Globe Properties to train any large language models or other forms of generative artificial intelligence.
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
name: Globe Life
provenance_date: '2026-11-09'
provider_name: Globe Life
provider_slug: globe-life
slug: globe-life-eligibility
source_date: '2026-11-09'
source_filename: globe-life-eligibility.yml
source_heading: Eligibility
source_page: https://home.globelifeinsurance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Globe Life\naid: globe-life\nurl: https://home.globelifeinsurance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use Globe Properties, you are affirming that you are at least 18 years old or of legal age of majority\n    in your jurisdiction of residence\nrestricted_uses:\n- summary: Under-18 use\n  text: no person under the age of 18 may use Globe Properties.\n- summary: AI training on Globe Properties data\n  text: use any data contained in or obtained from Globe Properties to train any large\
  \ language models or other\n    forms of generative artificial intelligence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Globe Properties are not intended for children under the age of 18 and no person under the age of 18 may\n    use Globe Properties.\n"
source_yaml_url: https://artifacts.apis.io/globe-life/eligibility/globe-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Globe Life's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Life Insurance
- Financial Services
- Supplemental Health
- Medicare Supplement
- Insurance Carrier
- Fortune 1000
---
