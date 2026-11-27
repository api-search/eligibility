---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may only purchase and use Subscription Creds if you have reached the age of majority in the jurisdiction in which you reside.
    value: null
  restricted_uses:
  - summary: Complimentary Credits for personal entertainment only
    text: Your acquisition of Complimentary Creds entitles you to receive a limited, non-transferable, revocable license to use Credits (a) in connection with the Service, (b) for your personal entertainment only, and (c) in the ways permitted under these Terms.
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
name: Glif
provenance_date: '2026-11-09'
provider_name: Glif
provider_slug: glif-app
slug: glif-app-eligibility
source_date: '2026-11-09'
source_filename: glif-app-eligibility.yml
source_heading: Eligibility
source_page: https://glif.app/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glif\naid: glif-app\nurl: https://glif.app/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Complimentary Credits for personal entertainment only\n  text: Your acquisition of Complimentary Creds entitles you to receive a limited, non-transferable, revocable license\n    to use Credits (a) in connection with the Service, (b) for your personal entertainment only, and (c) in the\n    ways permitted under these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: You may only purchase and use Subscription Creds if you have reached the age of majority in the jurisdiction\n    in which you reside.\n"
source_yaml_url: https://artifacts.apis.io/glif-app/eligibility/glif-app-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Glif's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- Workflows
- Creative AI
- Generative AI
- Video Generation
- Image Generation
- ComfyUI
- MCP
- LLM Apps
- A2A
---
