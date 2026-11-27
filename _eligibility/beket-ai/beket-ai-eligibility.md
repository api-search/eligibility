---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is available to users globally.
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of a business or organization, you represent that you have authority to bind that entity to these Terms.
    type: business
  - text: including but not limited to early-stage companies and registered nonprofit organizations
    type: nonprofit
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Automated access imposing unreasonable load
    text: Use automated tools, bots, or scripts to access the Service in a manner that imposes unreasonable load on our systems;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Applications are reviewed at our sole discretion, and approval is not guaranteed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beket AI
provenance_date: '2026-11-09'
provider_name: Beket AI
provider_slug: beket-ai
slug: beket-ai-eligibility
source_date: '2026-11-09'
source_filename: beket-ai-eligibility.yml
source_heading: Eligibility
source_page: https://beket.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beket AI\naid: beket-ai\nurl: https://beket.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is available to users globally.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of a business or organization, you represent that you have authority\n    to bind that entity to these Terms.\n- type: nonprofit\n  text: including but not limited to early-stage companies and registered nonprofit organizations\nrestricted_uses:\n- summary: Automated access\
  \ imposing unreasonable load\n  text: Use automated tools, bots, or scripts to access the Service in a manner that imposes unreasonable load on\n    our systems;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Applications are reviewed at our sole discretion, and approval is not guaranteed.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/beket-ai/eligibility/beket-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Beket AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Brands
- Monitoring
- Analytics
---
