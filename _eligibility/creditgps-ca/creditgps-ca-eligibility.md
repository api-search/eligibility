---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The Service is offered in Canada and is not directed to persons outside Canada.
  entity_types:
  - text: To use the Service you must be at least the age of majority in your province or territory of residence, a resident of Canada, and able to enter into a binding contract.
    type: individual
  minimum_age:
    text: at least the age of majority in your province or territory of residence
    value: age of majority
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: use the Service for any unlawful purpose or in violation of these Terms
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
name: Credit GPS
provenance_date: '2026-11-09'
provider_name: Credit GPS
provider_slug: creditgps-ca
slug: creditgps-ca-eligibility
source_date: '2026-11-09'
source_filename: creditgps-ca-eligibility.yml
source_heading: Eligibility
source_page: https://creditgps.ca/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credit GPS\naid: creditgps-ca\nurl: https://creditgps.ca/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The Service is offered in Canada and is not directed to persons outside Canada.\nentity_types:\n- type: individual\n  text: To use the Service you must be at least the age of majority in your province or territory of residence,\n    a resident of Canada, and able to enter into a binding contract.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: use the Service for any unlawful purpose or in violation of these Terms\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: at least the age of majority in your province or territory of residence\n"
source_yaml_url: https://artifacts.apis.io/creditgps-ca/eligibility/creditgps-ca-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Credit GPS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit Score
- Personal Finance
- Fintech
- Canada
- Credit Cards
- Financial Education
---
