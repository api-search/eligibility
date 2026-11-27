---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your personal, non-commercial use
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
name: Culturerobotics
provenance_date: '2026-11-09'
provider_name: Culturerobotics
provider_slug: culturerobotics
slug: culturerobotics-eligibility
source_date: '2026-11-09'
source_filename: culturerobotics-eligibility.yml
source_heading: Eligibility
source_page: https://www.culturebiosciences.com/terms-of-service?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Culturerobotics\naid: culturerobotics\nurl: https://www.culturebiosciences.com/terms-of-service?hsLang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. Access to the Site from countries or\n    territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants\
  \ that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/culturerobotics/eligibility/culturerobotics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Culturerobotics's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Cloud
- Bioprocessing
- Software
- Cell Culture
---
