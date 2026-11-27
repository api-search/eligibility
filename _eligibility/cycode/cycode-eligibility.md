---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is only intended for individuals aged eighteen (18) years or older.
    type: individual
  - text: for yourself or on behalf of the person or entity committed by you to the Terms
    type: business
  minimum_age:
    text: The Website is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Benchmarking or competitive analysis
    text: (viii) access or use the Website for benchmarking or similar competitive analysis purposes or in order to build a competitive product or service.
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
name: Cycode
provenance_date: '2026-11-09'
provider_name: Cycode
provider_slug: cycode
slug: cycode-eligibility
source_date: '2026-11-09'
source_filename: cycode-eligibility.yml
source_heading: Eligibility
source_page: https://cycode.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cycode\naid: cycode\nurl: https://cycode.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is only intended for individuals aged eighteen (18) years or older.\n- type: business\n  text: for yourself or on behalf of the person or entity committed by you to the Terms\nrestricted_uses:\n- summary: Benchmarking or competitive analysis\n  text: (viii) access or use the Website for benchmarking or similar competitive analysis purposes or in order to\n    build a competitive product or service.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/cycode/eligibility/cycode-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cycode's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Application Security
- Software Supply Chain Security
- ASPM
- DevSecOps
- Secrets Scanning
- SAST
- Software Composition Analysis
- Developer Tools
- MCP
- CLI
---
