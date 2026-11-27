---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service or purchase hardware if you are located in, or ordinarily resident in, a country or region subject to comprehensive US sanctions, or if you are listed on any US government restricted-party list.
  entity_types:
  - text: The Service is offered exclusively to businesses and business users, and only for commercial purposes.
    type: business
  minimum_age:
    text: By using the Service you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal goods or services
    text: sell goods or services that are illegal or that violate Adyen's restricted and prohibited business lists
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
name: finalpos-com
provenance_date: '2026-11-09'
provider_name: finalpos-com
provider_slug: finalpos-com
slug: finalpos-com-eligibility
source_date: '2026-11-09'
source_filename: finalpos-com-eligibility.yml
source_heading: Eligibility
source_page: https://finalpos.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: finalpos-com\naid: finalpos-com\nurl: https://finalpos.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service or purchase hardware if you are located in, or ordinarily resident in, a country\n    or region subject to comprehensive US sanctions, or if you are listed on any US government restricted-party\n    list.\nentity_types:\n- type: business\n  text: The Service is offered exclusively to businesses and business users, and only for commercial purposes.\nrestricted_uses:\n- summary: Illegal goods or services\n  text: sell goods or services that\
  \ are illegal or that violate Adyen's restricted and prohibited business lists\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Service you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/finalpos-com/eligibility/finalpos-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from finalpos-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Point-of-Sale
- Retail
- Payments
- Fintech
---
