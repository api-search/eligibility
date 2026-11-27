---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you choose to access the Platform from locations other than India, you will do so at your own risk, and you will be solely liable and responsible for compliance with applicable local laws and regulations of such location.
  entity_types:
  - text: For the purposes of registration/creation of an account on the Platform, you confirm that you are 18 years of age.
    type: individual
  minimum_age:
    text: The Service is not available for use by persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No illegal or restricted package requests
    text: You agree that you will not request Package Services for Package(s) which are illegal, hazardous, dangerous, or otherwise restricted or constitute items that are prohibited by any statute or law or regulation or the provisions of these Terms.
  - summary: No fraud or unlawful use
    text: You will not use the Platform for unlawful purposes, including but not limited to sending or storing any unlawful material or for fraudulent purposes
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we may ask you for Information or documents that will allow us to reasonably identify you, requiring you to take steps to confirm your right over your email address or financial instruments, or verifying your Information against third party databases or through other sources.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rapido
provenance_date: '2026-11-10'
provider_name: Rapido
provider_slug: rapido
slug: rapido-eligibility
source_date: '2026-11-10'
source_filename: rapido-eligibility.yml
source_heading: Eligibility
source_page: https://www.rapido.bike/CustomerTerms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rapido\naid: rapido\nurl: https://www.rapido.bike/CustomerTerms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: If you choose to access the Platform from locations other than India, you will do so at your own risk, and\n    you will be solely liable and responsible for compliance with applicable local laws and regulations of such\n    location.\nentity_types:\n- type: individual\n  text: For the purposes of registration/creation of an account on the Platform, you confirm that you are 18 years\n    of age.\nrestricted_uses:\n- summary: No illegal or restricted package\
  \ requests\n  text: You agree that you will not request Package Services for Package(s) which are illegal, hazardous, dangerous,\n    or otherwise restricted or constitute items that are prohibited by any statute or law or regulation or the provisions\n    of these Terms.\n- summary: No fraud or unlawful use\n  text: You will not use the Platform for unlawful purposes, including but not limited to sending or storing any\n    unlawful material or for fraudulent purposes\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we may ask you for Information or documents that will allow us to reasonably identify you, requiring you\n    to take steps to confirm your right over your email address or financial instruments, or verifying your Information\n    against third party databases or through other sources.\nminimum_age:\n  value: '18'\n  text: The Service is not available for use by persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/rapido/eligibility/rapido-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Rapido's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Services
- Mobility
- Transportation
- Ride Hailing
- Bike Taxi
- Logistics
- India
---
