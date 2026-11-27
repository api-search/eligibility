---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For individual consumers, the interpretation and enforcement of this Arbitration Agreement and any arbitration proceedings
    type: individual
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-personal or non-evaluation use
    text: solely for your own personal, noncommercial use, and solely to evaluate or seek support for Company’s offerings
  - summary: Benchmarking or testing for legal claims
    text: using the Site for benchmarking purposes or to investigate, evaluate, test, or monitor the Site for potential legal claims, regulatory complaints, or enforcement actions against the Company
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
name: SiFive
provenance_date: '2026-11-10'
provider_name: SiFive
provider_slug: sifive
slug: sifive-eligibility
source_date: '2026-11-10'
source_filename: sifive-eligibility.yml
source_heading: Eligibility
source_page: https://www.sifive.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SiFive\naid: sifive\nurl: https://www.sifive.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: For individual consumers, the interpretation and enforcement of this Arbitration Agreement and any arbitration\n    proceedings\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Non-personal or non-evaluation use\n  text: solely for your own personal, noncommercial use, and solely to evaluate or seek support\
  \ for Company’s offerings\n- summary: Benchmarking or testing for legal claims\n  text: using the Site for benchmarking purposes or to investigate, evaluate, test, or monitor the Site for potential\n    legal claims, regulatory complaints, or enforcement actions against the Company\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sifive/eligibility/sifive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SiFive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Semiconductors
- RISC-V
- Processor IP
- Chip Design
- Embedded
- Hardware
- Developer Tools
- Electronic Design Automation
- OAuth
- Authentication
---
