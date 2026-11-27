---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: You will not (i) post on or transmit to the Site any defamatory, libelous, obscene, pornographic, profane, threatening, or unlawful materials
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
name: LiveAction
provenance_date: '2026-11-09'
provider_name: LiveAction
provider_slug: liveaction
slug: liveaction-eligibility
source_date: '2026-11-09'
source_filename: liveaction-eligibility.yml
source_heading: Eligibility
source_page: https://www.liveaction.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiveAction\naid: liveaction\nurl: https://www.liveaction.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: You will not (i) post on or transmit to the Site any defamatory, libelous, obscene, pornographic, profane,\n    threatening, or unlawful materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/liveaction/eligibility/liveaction-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from LiveAction's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Network Monitoring
- Network Observability
- Network Performance Monitoring
- Packet Capture
- Network Forensics
- SD-WAN
- Telemetry
---
