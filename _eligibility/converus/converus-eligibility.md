---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you represent that you are at least eighteen (18) years old.
    type: individual
  - text: for your own personal, non-commercial use or legitimate business purposes
    type: business
  minimum_age:
    text: By using the Site, you represent that you are at least eighteen (18) years old.
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
name: Converus
provenance_date: '2026-11-09'
provider_name: Converus
provider_slug: converus
slug: converus-eligibility
source_date: '2026-11-09'
source_filename: converus-eligibility.yml
source_heading: Eligibility
source_page: https://converus.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Converus\naid: converus\nurl: https://converus.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you represent that you are at least eighteen (18) years old.\n- type: business\n  text: for your own personal, non-commercial use or legitimate business purposes\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you represent that you are at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/converus/eligibility/converus-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Converus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lie Detection
- Artificial Intelligence
- Security
- Government
---
