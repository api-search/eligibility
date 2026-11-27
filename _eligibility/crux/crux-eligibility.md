---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are legally formed and domiciled in the United States
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: OFAC and sanctions compliance
    text: You are not and shall not be prohibited from transacting business of the type contemplated by these Terms, pursuant to any federal regulations and executive orders and lists administered or published by OFAC.
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
name: Crux
provenance_date: '2026-11-09'
provider_name: Crux
provider_slug: crux
slug: crux-eligibility
source_date: '2026-11-09'
source_filename: crux-eligibility.yml
source_heading: Eligibility
source_page: https://www.crux.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crux\naid: crux\nurl: https://www.crux.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are legally formed and domiciled in the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: OFAC and sanctions compliance\n  text: You are not and shall\
  \ not be prohibited from transacting business of the type contemplated by these Terms,\n    pursuant to any federal regulations and executive orders and lists administered or published by OFAC.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/crux/eligibility/crux-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Crux's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clean Energy
- Climate Finance
- Tax Credits
- Capital Markets
- Fintech
- Energy
- Marketplace
- Sustainability
---
