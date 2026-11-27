---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is available only to individuals who possess the legal authority to enter into these Terms and to form a binding agreement under any applicable law.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Prisma Photonics
provenance_date: '2026-11-10'
provider_name: Prisma Photonics
provider_slug: prisma-photonics
slug: prisma-photonics-eligibility
source_date: '2026-11-10'
source_filename: prisma-photonics-eligibility.yml
source_heading: Eligibility
source_page: https://www.prismaphotonics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prisma Photonics\naid: prisma-photonics\nurl: https://www.prismaphotonics.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is available only to individuals who possess the legal authority to enter into these Terms and\n    to form a binding agreement under any applicable law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prisma-photonics/eligibility/prisma-photonics-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Prisma Photonics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fiber Sensing
- Distributed Acoustic Sensing
- Infrastructure Monitoring
- Critical Infrastructure
- Perimeter Security
- Energy
- Sensors
---
