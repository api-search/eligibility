---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are accessing the Internet from a physical location within the United States of America
  entity_types:
  - text: Client and its authorized users are at least eighteen (18) years of age and are accessing the Services solely in a commercial or business capacity.
    type: business
  minimum_age:
    text: These Websites are offered and available to users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Websites only for lawful purposes and in accordance with this Agreement.
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
name: 8fig
provenance_date: '2026-11-09'
provider_name: 8fig
provider_slug: 8fig
slug: 8fig-eligibility
source_date: '2026-11-09'
source_filename: 8fig-eligibility.yml
source_heading: Eligibility
source_page: https://www.8fig.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 8fig\naid: 8fig\nurl: https://www.8fig.co/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are accessing the Internet from a physical location within the United States of America\nentity_types:\n- type: business\n  text: Client and its authorized users are at least eighteen (18) years of age and are accessing the Services solely\n    in a commercial or business capacity.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Websites only for lawful purposes and in accordance with this Agreement.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: These Websites are offered and available to users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/8fig/eligibility/8fig-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 8fig's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Fintech
- Financing
- Lending
- Growth Capital
- Working Capital
- Embedded Finance
---
