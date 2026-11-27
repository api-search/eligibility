---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and operated within the United States and is not intended for use outside of the United States.
  minimum_age:
    text: You are not authorized to access or use the Site if you are under 18
    value: '18'
  restricted_uses:
  - summary: Under-18 users barred
    text: You are not authorized to access or use the Site if you are under 18
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
name: GigaIO
provenance_date: '2026-11-09'
provider_name: GigaIO
provider_slug: gigaio
slug: gigaio-eligibility
source_date: '2026-11-09'
source_filename: gigaio-eligibility.yml
source_heading: Eligibility
source_page: https://gigaio.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GigaIO\naid: gigaio\nurl: https://gigaio.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and operated within the United States and is not intended for use outside of the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Under-18 users barred\n  text: You are not authorized to access or use the Site if you are under 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are not authorized to access or use the Site if you are under 18\n"
source_yaml_url: https://artifacts.apis.io/gigaio/eligibility/gigaio-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from GigaIO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Composable Infrastructure
- Edge Computing
- Artificial Intelligence
- High Performance Computing
- Data Center
- Hardware
- GPU
- PCIe
- Infrastructure as Code
---
