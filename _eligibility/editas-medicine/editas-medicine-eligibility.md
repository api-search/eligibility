---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your own lawful, personal, noncommercial use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Noncommercial personal use only
    text: only for your own lawful, personal, noncommercial use.
  - summary: US export control restrictions
    text: You expressly agree to comply with such restrictions and not to export or re-export any of the Content to countries or persons prohibited under the export control laws.
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
name: Editas Medicine
provenance_date: '2026-11-09'
provider_name: Editas Medicine
provider_slug: editas-medicine
slug: editas-medicine-eligibility
source_date: '2026-11-09'
source_filename: editas-medicine-eligibility.yml
source_heading: Eligibility
source_page: https://www.editasmedicine.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Editas Medicine\naid: editas-medicine\nurl: https://www.editasmedicine.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your own lawful, personal, noncommercial use\nrestricted_uses:\n- summary: Noncommercial personal use only\n  text: only for your own lawful, personal, noncommercial use.\n- summary: US export control restrictions\n  text: You expressly agree to comply with such restrictions and not to export or re-export any of the Content to\n    countries or persons prohibited under the export control laws.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/editas-medicine/eligibility/editas-medicine-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Editas Medicine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Biotechnology
- Gene Editing
- CRISPR
- Genomics
- Therapeutics
- Pharmaceuticals
---
