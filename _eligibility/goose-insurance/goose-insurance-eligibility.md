---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and services offered on the Platform are only available in the jurisdictions in which Goose is properly licensed.
  entity_types:
  - text: made available only for your personal, lawful, non-commercial use in connection with seeking insurance
    type: individual
  - text: Use of the Platform by a competitor company or non-consumer third-party is prohibited.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors and non-consumer third parties
    text: Use of the Platform by a competitor company or non-consumer third-party is prohibited.
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
name: Goose Insurance
provenance_date: '2026-11-09'
provider_name: Goose Insurance
provider_slug: goose-insurance
slug: goose-insurance-eligibility
source_date: '2026-11-09'
source_filename: goose-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.gooseinsurance.com/en-ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goose Insurance\naid: goose-insurance\nurl: https://www.gooseinsurance.com/en-ca/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products and services offered on the Platform are only available in the jurisdictions in which Goose\n    is properly licensed.\nentity_types:\n- type: individual\n  text: made available only for your personal, lawful, non-commercial use in connection with seeking insurance\n- type: business\n  text: Use of the Platform by a competitor company or non-consumer third-party is prohibited.\nrestricted_uses:\n- summary: Competitors and non-consumer\
  \ third parties\n  text: Use of the Platform by a competitor company or non-consumer third-party is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goose-insurance/eligibility/goose-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Goose Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Insurtech
- Life Insurance
- Travel Insurance
- Health Insurance
- Brokerage
- Digital Distribution
- Managing General Agent
- Mobile
---
