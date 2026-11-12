---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using CoreWise on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unpermitted commercial use
    text: Uses CoreWise for commercial purposes without permission (e.g., white-labeling the service)
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
name: CoreWise
provenance_date: '2026-11-09'
provider_name: CoreWise
provider_slug: corewise-video
slug: corewise-video-eligibility
source_date: '2026-11-09'
source_filename: corewise-video-eligibility.yml
source_heading: Eligibility
source_page: https://corewise.video/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoreWise\naid: corewise-video\nurl: https://corewise.video/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using CoreWise on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Unpermitted commercial use\n  text: Uses CoreWise for commercial purposes without permission (e.g., white-labeling the service)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/corewise-video/eligibility/corewise-video-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CoreWise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Summarization
- Knowledge Management
- Research
- Model Context Protocol
- Content Extraction
---
