---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled, operated and administered by Nuro from our offices within the USA. If you access the Service from a location outside the USA, you are responsible for compliance with all local laws.
  minimum_age:
    text: If you are under 18, you may use www.nuro.ai only with permission of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Unlawful use prohibited
    text: As a condition of your use of the Site, you warrant to Nuro that you will not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: Nuro
provenance_date: '2026-11-10'
provider_name: Nuro
provider_slug: nuro
slug: nuro-eligibility
source_date: '2026-11-10'
source_filename: nuro-eligibility.yml
source_heading: Eligibility
source_page: https://www.nuro.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuro\naid: nuro\nurl: https://www.nuro.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled, operated and administered by Nuro from our offices within the USA. If you access\n    the Service from a location outside the USA, you are responsible for compliance with all local laws.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: As a condition of your use of the Site, you warrant to Nuro that you will not use the Site for any purpose\n    that is unlawful or prohibited by these Terms.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 18, you may use www.nuro.ai only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/nuro/eligibility/nuro-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nuro's own page on 2026-11-10.
synthetic: false
tags:
- Autonomous Vehicles
- Self-Driving
- Robotaxi
- Goods Delivery
- Licensing
- Nuro Driver
- Nuro Toolkit
---
