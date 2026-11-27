---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served:
    - IN
    text: The BNPL Option and/or the Credit Line Option is only available for purchasing goods and/or services within the territory of India to a User who ... is an Indian national and a tax resident of India and not a tax resident of the United States of America or any other country
  entity_types:
  - text: The access to Rupifi Portal and Rupifi Services is only available to a person who is competent to enter into legally binding contracts under the Indian Contract Act, 1872.
    type: individual
  minimum_age:
    text: You are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent funds
    text: avail Rupifi Services with funds that may have been obtained illegally or fraudulently or from sources not permitted under applicable law
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: For availing some Rupifi Services, You may be required to provide certain Know Your Customer (KYC) and other authentication documents as prescribed under applicable law
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rupifi
provenance_date: '2026-11-10'
provider_name: Rupifi
provider_slug: rupifi
slug: rupifi-eligibility
source_date: '2026-11-10'
source_filename: rupifi-eligibility.yml
source_heading: Eligibility
source_page: https://www.rupifi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rupifi\naid: rupifi\nurl: https://www.rupifi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded:\n  - US\n  text: The BNPL Option and/or the Credit Line Option is only available for purchasing goods and/or services within\n    the territory of India to a User who ... is an Indian national and a tax resident of India and not a tax resident\n    of the United States of America or any other country\nentity_types:\n- type: individual\n  text: The access to Rupifi Portal and Rupifi Services is only available to a person who is competent to enter\n    into legally binding\
  \ contracts under the Indian Contract Act, 1872.\nrestricted_uses:\n- summary: Illegal or fraudulent funds\n  text: avail Rupifi Services with funds that may have been obtained illegally or fraudulently or from sources not\n    permitted under applicable law\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: For availing some Rupifi Services, You may be required to provide certain Know Your Customer (KYC) and other\n    authentication documents as prescribed under applicable law\nminimum_age:\n  value: '18'\n  text: You are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/rupifi/eligibility/rupifi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rupifi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Buy Now Pay Later
- Embedded Finance
- B2B Payments
- Lending
- India
---
