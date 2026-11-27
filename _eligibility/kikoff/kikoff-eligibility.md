---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site and App are intended solely for Users who are citizens or legal residents of the United States of America and are physically present in the United States of America at the time of such use.
  entity_types:
  - text: Users who are citizens or legal residents of the United States of America and are physically present in the United States of America at the time of such use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: (b) is unlawful, fraudulent, or deceptive
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you complete the account opening process, you authorize us to create and maintain an account in your name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kikoff
provenance_date: '2026-11-09'
provider_name: Kikoff
provider_slug: kikoff
slug: kikoff-eligibility
source_date: '2026-11-09'
source_filename: kikoff-eligibility.yml
source_heading: Eligibility
source_page: https://kikoff.com/terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kikoff\naid: kikoff\nurl: https://kikoff.com/terms.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site and App are intended solely for Users who are citizens or legal residents of the United States\n    of America and are physically present in the United States of America at the time of such use.\nentity_types:\n- type: individual\n  text: Users who are citizens or legal residents of the United States of America and are physically present in\n    the United States of America at the time of such use.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: (b)\
  \ is unlawful, fraudulent, or deceptive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you complete the account opening process, you authorize us to create and maintain an account in your\n    name\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kikoff/eligibility/kikoff-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Kikoff's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Credit
- Credit Building
- Credit Reporting
- Consumer Finance
- Personal Finance
- Lending
---
