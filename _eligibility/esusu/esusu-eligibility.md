---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: is a legal resident of the United States. We make no representation that the Esusu Service is appropriate or available for use outside the United States.
  entity_types:
  - text: The Esusu Service is offered and available to any user who is 18 years of age or older, has the legal capacity to form a binding contract with Esusu, and is a legal resident of the United States.
    type: individual
  minimum_age:
    text: The Esusu Service is offered and available to any user who is 18 years of age or older
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order for you to use certain portions of the Esusu Service, we may be required to verify your identity. You authorize us to make any inquiries we consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Esusu
provenance_date: '2026-11-09'
provider_name: Esusu
provider_slug: esusu
slug: esusu-eligibility
source_date: '2026-11-09'
source_filename: esusu-eligibility.yml
source_heading: Eligibility
source_page: https://www.esusurent.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Esusu\naid: esusu\nurl: https://www.esusurent.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: is a legal resident of the United States. We make no representation that the Esusu Service is appropriate\n    or available for use outside the United States.\nentity_types:\n- type: individual\n  text: The Esusu Service is offered and available to any user who is 18 years of age or older, has the legal capacity\n    to form a binding contract with Esusu, and is a legal resident of the United States.\nrestricted_uses: []\nverification:\n  kyc:\
  \ true\n  kyb: null\n  approval_required: null\n  text: In order for you to use certain portions of the Esusu Service, we may be required to verify your identity.\n    You authorize us to make any inquiries we consider necessary to validate your identity.\nminimum_age:\n  value: '18'\n  text: The Esusu Service is offered and available to any user who is 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/esusu/eligibility/esusu-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Esusu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Fintech
- Financial Services
- Credit
- Credit Building
- Rent Reporting
- Real Estate
- Identity Verification
- Income Verification
---
