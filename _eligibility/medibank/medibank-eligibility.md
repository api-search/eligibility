---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Medibank health insurance coverage is only available to Australian residents and holders of valid Australian visas.
  entity_types:
  - text: Medibank Message Us is intended solely for use by Australian residents and holders of valid Australian visas who are eligible to purchase our insurance products.
    type: individual
  minimum_age:
    text: To be eligible to use Medibank Message Us you must be 16 years of age or older.
    value: '16'
  restricted_uses:
  - summary: No corruption or interference with the service
    text: 'You must not use or attempt to use Medibank Message Us to: (a) corrupt, damage or interfere with Medibank Message Us or any Medibank or third party data, software, hardware, website or information technology systems'
  - source: https://www.medibank.com.au/terms-and-conditions/
    summary: No misuse for family violence or financial abuse
    text: This includes using or attempting to use a Medibank policy to cause harm to another person, such as limiting their access to healthcare, information, or entitlements.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Medibank has the sole right to determine your eligibility for, and the extent of your access to, Medibank Message Us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Medibank
provenance_date: '2026-11-10'
provider_name: Medibank
provider_slug: medibank
slug: medibank-eligibility
source_date: '2026-11-10'
source_filename: medibank-eligibility.yml
source_heading: Eligibility
source_page: https://www.medibank.com.au/legal-information/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medibank\naid: medibank\nurl: https://www.medibank.com.au/legal-information/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.medibank.com.au/legal-information/\n  - https://www.medibank.com.au/terms-and-conditions/\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Medibank health insurance coverage is only available to Australian residents and holders of valid Australian\n    visas.\nentity_types:\n- type: individual\n  text: Medibank Message Us is intended solely for use by Australian residents and holders of valid Australian visas\n    who are eligible to purchase our insurance products.\nrestricted_uses:\n\
  - summary: No corruption or interference with the service\n  text: 'You must not use or attempt to use Medibank Message Us to: (a) corrupt, damage or interfere with Medibank\n    Message Us or any Medibank or third party data, software, hardware, website or information technology systems'\n- summary: No misuse for family violence or financial abuse\n  text: This includes using or attempting to use a Medibank policy to cause harm to another person, such as limiting\n    their access to healthcare, information, or entitlements.\n  source: https://www.medibank.com.au/terms-and-conditions/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Medibank has the sole right to determine your eligibility for, and the extent of your access to, Medibank\n    Message Us.\nminimum_age:\n  value: '16'\n  text: To be eligible to use Medibank Message Us you must be 16 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/medibank/eligibility/medibank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Medibank's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Australia
- Health Insurance
- Private Health Insurance
- Life and Health
- Carrier
- Claims
- Policy Administration
- Travel Insurance
- Pet Insurance
---
