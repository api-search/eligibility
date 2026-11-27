---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a legal entity to engage our services.
    type: business
  - text: Our services are offered strictly on a business-to-business basis.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, infringing or harmful purposes
    text: Using services for illegal, infringing, or harmful purposes.
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
name: the2410-com
provenance_date: '2026-11-10'
provider_name: the2410-com
provider_slug: the2410-com
slug: the2410-com-eligibility
source_date: '2026-11-10'
source_filename: the2410-com-eligibility.yml
source_heading: Eligibility
source_page: https://the2410.com/en/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: the2410-com\naid: the2410-com\nurl: https://the2410.com/en/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be a legal entity to engage our services.\n- type: individual\n  text: Our services are offered strictly on a business-to-business basis.\nrestricted_uses:\n- summary: Illegal, infringing or harmful purposes\n  text: Using services for illegal, infringing, or harmful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/the2410-com/eligibility/the2410-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from the2410-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- B2B
- Web Development
- Artificial Intelligence
- Automation
---
