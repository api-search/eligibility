---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are being granted access One as a result of your employment or other agreement with Lessen LLC.
    type: other
  - source: https://www.lessen.com/legal/terms-of-use
    text: The Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: One is not intended for children under the age of eighteen and should not be used by anyone under eighteen.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful uploads
    text: Upload or transmit any information that is defamatory, libelous, expresses hate, is unlawfully threatening, or harasses or advocates the harassment of another person.
  - summary: Pornographic or minor-exploitative content
    text: Upload or transmit any information that is pornographic, exploitative of a minor, or obscene.
  - source: https://www.lessen.com/legal/terms-of-use
    summary: Lawful use only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Lessen
provenance_date: '2026-11-09'
provider_name: Lessen
provider_slug: lessen
slug: lessen-eligibility
source_date: '2026-11-09'
source_filename: lessen-eligibility.yml
source_heading: Eligibility
source_page: https://www.lessen.com/legal/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lessen\naid: lessen\nurl: https://www.lessen.com/legal/acceptable-use-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.lessen.com/legal/acceptable-use-policy\n  - https://www.lessen.com/legal/terms-of-use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: You are being granted access One as a result of your employment or other agreement with Lessen LLC.\n- type: individual\n  text: The Website is offered and available to users who are 18 years of age or older.\n  source: https://www.lessen.com/legal/terms-of-use\nrestricted_uses:\n- summary: Unlawful or\
  \ harmful uploads\n  text: Upload or transmit any information that is defamatory, libelous, expresses hate, is unlawfully threatening,\n    or harasses or advocates the harassment of another person.\n- summary: Pornographic or minor-exploitative content\n  text: Upload or transmit any information that is pornographic, exploitative of a minor, or obscene.\n- summary: Lawful use only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\n  source: https://www.lessen.com/legal/terms-of-use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: One is not intended for children under the age of eighteen and should not be used by anyone under eighteen.\n"
source_yaml_url: https://artifacts.apis.io/lessen/eligibility/lessen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Lessen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Property Management
- Facilities Management
- Field Service Management
- Work Order Management
- Maintenance
- Marketplace
- Construction
---
