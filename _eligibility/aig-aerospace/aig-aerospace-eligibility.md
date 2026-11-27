---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is not directed at persons in any jurisdiction where distribution of its information is contrary to local law.
  entity_types:
  - text: If you are using the Website on behalf of an individual or entity, you represent and warrant that you have authority to bind that individual and/or entity to the Terms of Use
    type: business
  minimum_age:
    text: you are of legal age in your country to form a binding contract
    value: legal age in your country
  restricted_uses:
  - summary: Surplus lines materials
    text: Any materials accessible through the Website relating to surplus lines products are intended for use solely by properly licensed surplus lines producers.
  - summary: Unlawful or fraudulent use
    text: use the Website for any unlawful, unauthorized, fraudulent or malicious purpose
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
name: AIG Aerospace
provenance_date: '2026-11-09'
provider_name: AIG Aerospace
provider_slug: aig-aerospace
slug: aig-aerospace-eligibility
source_date: '2026-11-09'
source_filename: aig-aerospace-eligibility.yml
source_heading: Eligibility
source_page: https://www.aig.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIG Aerospace\naid: aig-aerospace\nurl: https://www.aig.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is not directed at persons in any jurisdiction where distribution of its information is contrary\n    to local law.\nentity_types:\n- type: business\n  text: If you are using the Website on behalf of an individual or entity, you represent and warrant that you have\n    authority to bind that individual and/or entity to the Terms of Use\nrestricted_uses:\n- summary: Surplus lines materials\n  text: Any materials accessible through the Website relating\
  \ to surplus lines products are intended for use solely\n    by properly licensed surplus lines producers.\n- summary: Unlawful or fraudulent use\n  text: use the Website for any unlawful, unauthorized, fraudulent or malicious purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age in your country\n  text: you are of legal age in your country to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/aig-aerospace/eligibility/aig-aerospace-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AIG Aerospace's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Aviation
- Aerospace
- Specialty Insurance
- Property and Casualty
- Claims
- Unmanned Aircraft
- Enterprise
---
