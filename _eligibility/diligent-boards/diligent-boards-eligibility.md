---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the legal entity, including its Affiliates (collectively “ Client ”) identified in the applicable Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, abusive or harmful use
    text: use the API in any way that is unlawful, harmful, threatening, abusive, harassing, tortious, defamatory, vulgar, obscene, libelous, invasive of another’s privacy or right of publicity, hateful, or racially, ethnically or otherwise objectionable
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
name: Diligent
provenance_date: '2026-11-09'
provider_name: Diligent
provider_slug: diligent-boards
slug: diligent-boards-eligibility
source_date: '2026-11-09'
source_filename: diligent-boards-eligibility.yml
source_heading: Eligibility
source_page: https://developer.diligent.com/docs/api_terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diligent\naid: diligent-boards\nurl: https://developer.diligent.com/docs/api_terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the legal entity, including its Affiliates (collectively “ Client ”) identified in the applicable Order\nrestricted_uses:\n- summary: Unlawful, abusive or harmful use\n  text: use the API in any way that is unlawful, harmful, threatening, abusive, harassing, tortious, defamatory,\n    vulgar, obscene, libelous, invasive of another’s privacy or right of publicity, hateful, or racially, ethnically\n\
  \    or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/diligent-boards/eligibility/diligent-boards-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Diligent's own page on 2026-11-09.
synthetic: false
tags:
- Governance
- Risk Management
- Compliance
- GRC
- Board Management
- Audit
- Entity Management
- ESG
- Enterprise
---
