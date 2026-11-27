---
api_specs:
- filename: refract-social-openapi-generated.yml
  format: yaml
  label: Refract API
  slug: refract-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refract-social/openapi/_ae-authored/refract-social-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals aged 18 or older
    type: individual
  - text: Businesses
    type: business
  minimum_age:
    text: Businesses, and individuals aged 18 or older. Refract isn't for children.
    value: '18'
  restricted_uses:
  - summary: Illegal or abusive content
    text: post content that's illegal, infringes someone's rights, harasses or threatens people, sexualises minors, promotes violence or terrorism, or is fraud, phishing or malware
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
name: Refract
provenance_date: '2026-11-10'
provider_name: Refract
provider_slug: refract-social
slug: refract-social-eligibility
source_date: '2026-11-10'
source_filename: refract-social-eligibility.yml
source_heading: Eligibility
source_page: https://refract.social/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Refract\naid: refract-social\nurl: https://refract.social/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individuals aged 18 or older\n- type: business\n  text: Businesses\nrestricted_uses:\n- summary: Illegal or abusive content\n  text: post content that's illegal, infringes someone's rights, harasses or threatens people, sexualises minors,\n    promotes violence or terrorism, or is fraud, phishing or malware\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: Businesses, and individuals aged 18 or older. Refract isn't for children.\n"
source_yaml_url: https://artifacts.apis.io/refract-social/eligibility/refract-social-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Refract's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Scheduling
- Artificial Intelligence
- Automation
- Company
---
