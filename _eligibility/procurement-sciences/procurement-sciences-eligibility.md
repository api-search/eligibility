---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not access or use the Services from an Embargoed Jurisdiction or in violation of any U.S. export embargo, prohibition or restriction.
  entity_types:
  - text: Customer must be a legal entity, or an individual at least eighteen (18) years of age and legally capable of entering into a binding contract, in order to accept this Agreement.
    type: business
  - text: an individual at least eighteen (18) years of age and legally capable of entering into a binding contract
    type: individual
  minimum_age:
    text: an individual at least eighteen (18) years of age and legally capable of entering into a binding contract
    value: '18'
  restricted_uses:
  - summary: CUI handling
    text: unless such use involving CUI is in compliance with applicable laws and regulations and Company’s policies, including, but not limited to, the requirement that Customer use CUI inside the FedRAMP authorized boundary
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
name: Procurement Sciences
provenance_date: '2026-11-10'
provider_name: Procurement Sciences
provider_slug: procurement-sciences
slug: procurement-sciences-eligibility
source_date: '2026-11-10'
source_filename: procurement-sciences-eligibility.yml
source_heading: Eligibility
source_page: https://www.procurementsciences.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Procurement Sciences\naid: procurement-sciences\nurl: https://www.procurementsciences.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not access or use the Services from an Embargoed Jurisdiction or in violation of any U.S. export\n    embargo, prohibition or restriction.\nentity_types:\n- type: business\n  text: Customer must be a legal entity, or an individual at least eighteen (18) years of age and legally capable\n    of entering into a binding contract, in order to accept this Agreement.\n- type: individual\n  text: an individual at least eighteen\
  \ (18) years of age and legally capable of entering into a binding contract\nrestricted_uses:\n- summary: CUI handling\n  text: unless such use involving CUI is in compliance with applicable laws and regulations and Company’s policies,\n    including, but not limited to, the requirement that Customer use CUI inside the FedRAMP authorized boundary\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual at least eighteen (18) years of age and legally capable of entering into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/procurement-sciences/eligibility/procurement-sciences-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Procurement Sciences's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Artificial Intelligence
- Government
- GovTech
- GovCon
- Public Sector
- Procurement
- Proposal Automation
- Capture Management
---
