---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Customer” means the entity executing the applicable Order Form.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing Customer Data
    text: use the Solution to upload, collect, transmit, store, use, disclose or process, or ask Feroot to obtain from third parties or perform any of the above with respect to, any Customer Data
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
name: Feroot
provenance_date: '2026-11-09'
provider_name: Feroot
provider_slug: feroot
slug: feroot-eligibility
source_date: '2026-11-09'
source_filename: feroot-eligibility.yml
source_heading: Eligibility
source_page: https://www.feroot.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Feroot\naid: feroot\nurl: https://www.feroot.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Customer” means the entity executing the applicable Order Form.\nrestricted_uses:\n- summary: Unlawful or infringing Customer Data\n  text: use the Solution to upload, collect, transmit, store, use, disclose or process, or ask Feroot to obtain\n    from third parties or perform any of the above with respect to, any Customer Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/feroot/eligibility/feroot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Feroot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Client-Side Security
- Application Security
- Compliance
- PCI DSS
- Privacy
- JavaScript Security
---
