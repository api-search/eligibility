---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are hosted in the United States and intended for visitors located within the United States.
  minimum_age:
    text: We do not knowingly collect, maintain, or use personal information from children under 18 years of age, and no part of our Service(s) is directed to children.
    value: '18'
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
name: Numero
provenance_date: '2026-11-10'
provider_name: Numero
provider_slug: numero
slug: numero-eligibility
source_date: '2026-11-10'
source_filename: numero-eligibility.yml
source_heading: Eligibility
source_page: https://app.numero.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numero\naid: numero\nurl: https://app.numero.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are hosted in the United States and intended for visitors located within the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect, maintain, or use personal information from children under 18 years of age,\n    and no part of our Service(s) is directed to children.\n"
source_yaml_url: https://artifacts.apis.io/numero/eligibility/numero-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Numero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Political Campaigns
- Fundraising
- Donor Management
- CRM
- Email
- Nonprofit Technology
---
