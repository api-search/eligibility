---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not intended for use in any jurisdiction where its use is not permitted
  entity_types:
  - text: the following terms apply to all users who purchase the “Agency” subscription plan or otherwise white-label our Services
    type: business
  minimum_age:
    text: YOU MAY NOT ORDER OR OBTAIN PRODUCTS OR SERVICES FROM THE SERVICES IF YOU (A) DO NOT AGREE TO THESE TERMS, (B) ARE NOT AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: Your use of our Services is conditional on you using our Services for lawful purposes only and in accordance with these Terms.
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
name: LocalImpact
provenance_date: '2026-11-09'
provider_name: LocalImpact
provider_slug: localimpact
slug: localimpact-eligibility
source_date: '2026-11-09'
source_filename: localimpact-eligibility.yml
source_heading: Eligibility
source_page: https://localimpact.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LocalImpact\naid: localimpact\nurl: https://localimpact.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not intended for use in any jurisdiction where its use is not permitted\nentity_types:\n- type: business\n  text: the following terms apply to all users who purchase the “Agency” subscription plan or otherwise white-label\n    our Services\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Your use of our Services is conditional on you using our Services for lawful purposes only and in accordance\n    with these Terms.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ORDER OR OBTAIN PRODUCTS OR SERVICES FROM THE SERVICES IF YOU (A) DO NOT AGREE TO THESE TERMS,\n    (B) ARE NOT AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/localimpact/eligibility/localimpact-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LocalImpact's own page on 2026-11-09.
synthetic: false
tags:
- Review
- Software-as-a-Service
- Local Business
- Reputation
- Software
---
