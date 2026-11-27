---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    - BH
    text: Your market United Arab Emirates Bahrain
  entity_types:
  - text: You must be legally capable of entering into contracts to use the Platform.
    type: individual
  - text: If you are using the Platform on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: In most jurisdictions, this means you must be at least 18 years old or have reached the age of legal majority.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Platform is intended for personal, non-commercial use.
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
name: Local
provenance_date: '2026-11-09'
provider_name: Local
provider_slug: local-holdings-limited
slug: local-holdings-limited-eligibility
source_date: '2026-11-09'
source_filename: local-holdings-limited-eligibility.yml
source_heading: Eligibility
source_page: https://www.uselocal.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Local\naid: local-holdings-limited\nurl: https://www.uselocal.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  - BH\n  excluded: []\n  text: Your market United Arab Emirates Bahrain\nentity_types:\n- type: individual\n  text: You must be legally capable of entering into contracts to use the Platform.\n- type: business\n  text: If you are using the Platform on behalf of a company or other legal entity, you represent that you have\n    the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The Platform is intended for personal,\
  \ non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In most jurisdictions, this means you must be at least 18 years old or have reached the age of legal majority.\n"
source_yaml_url: https://artifacts.apis.io/local-holdings-limited/eligibility/local-holdings-limited-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Local's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- QR Payments
- Hospitality
- Loyalty
- Point-of-Sale
- Restaurant
- GCC
---
