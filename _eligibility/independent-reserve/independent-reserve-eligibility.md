---
api_specs:
- filename: independent-reserve-private-api-openapi.yml
  format: yaml
  label: Independent Reserve Private API
  slug: independent-reserve-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/independent-reserve/openapi/independent-reserve-private-api-openapi.yml
- filename: independent-reserve-public-api-openapi.yml
  format: yaml
  label: Independent Reserve Public API
  slug: independent-reserve-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/independent-reserve/openapi/independent-reserve-public-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The Platform is available only to residents located in the countries listed on https://www.independentreserve.com/au/help/getting-started and is not intended to be offered or made available to any person who resides outside of these countries.
  entity_types:
  - text: be an individual who is at least 18 years old
    type: individual
  - text: be an Entity
    type: business
  minimum_age:
    text: be an individual who is at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Criminal or prohibited activity
    text: 'not use the service to engage in any criminal or restricted activities, including (but not limited) to: terrorist financing; money laundering; illegal gambling; distributing or funding drugs; malicious hacking'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 'for the purposes of verifying your identity, you consent to: the verification of your personal information with credit bureau header files (for verification only)'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Independent Reserve
provenance_date: '2026-11-09'
provider_name: Independent Reserve
provider_slug: independent-reserve
slug: independent-reserve-eligibility
source_date: '2026-11-09'
source_filename: independent-reserve-eligibility.yml
source_heading: Eligibility
source_page: https://www.independentreserve.com/help/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Independent Reserve\naid: independent-reserve\nurl: https://www.independentreserve.com/help/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The Platform is available only to residents located in the countries listed on https://www.independentreserve.com/au/help/getting-started\n    and is not intended to be offered or made available to any person who resides outside of these countries.\nentity_types:\n- type: individual\n  text: be an individual who is at least 18 years old\n- type: business\n  text: be an Entity\nrestricted_uses:\n- summary:\
  \ Criminal or prohibited activity\n  text: 'not use the service to engage in any criminal or restricted activities, including (but not limited) to:\n    terrorist financing; money laundering; illegal gambling; distributing or funding drugs; malicious hacking'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 'for the purposes of verifying your identity, you consent to: the verification of your personal information\n    with credit bureau header files (for verification only)'\nminimum_age:\n  value: '18'\n  text: be an individual who is at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/independent-reserve/eligibility/independent-reserve-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Independent Reserve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Bitcoin
- Financial Services
---
