---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for professional hosts/property managers. We do not offer consumer accounts.
    type: business
  minimum_age:
    text: You also represent that you are at least 18 years old (or the age of legal majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Life-safety or emergency use
    text: You agree not to use the Service for any purpose where the failure of the Service could lead to serious harm or death, such as emergency communications or life safety systems.
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
name: ChargeAutomation
provenance_date: '2026-11-09'
provider_name: ChargeAutomation
provider_slug: chargeautomation
slug: chargeautomation-eligibility
source_date: '2026-11-09'
source_filename: chargeautomation-eligibility.yml
source_heading: Eligibility
source_page: https://chargeautomation.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChargeAutomation\naid: chargeautomation\nurl: https://chargeautomation.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for professional hosts/property managers. We do not offer consumer accounts.\nrestricted_uses:\n- summary: Life-safety or emergency use\n  text: You agree not to use the Service for any purpose where the failure of the Service could lead to serious\n    harm or death, such as emergency communications or life safety systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You also represent that you are at least 18 years old (or the age of legal majority in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/chargeautomation/eligibility/chargeautomation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ChargeAutomation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hospitality
- Guest Experience
- Payments
- Property Management
---
