---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using CaptionPipe for a company, you confirm that you can bind that company, and "you" means the company.
    type: business
  - text: You must be at least 18 years old, or the age of majority where you live if that is higher.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher.
    value: '18'
  restricted_uses:
  - summary: Unlawful content
    text: Send us anything unlawful, or any sexual content involving minors, which we will report.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account with a verified email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CaptionPipe
provenance_date: '2026-11-09'
provider_name: CaptionPipe
provider_slug: captionpipe-com
slug: captionpipe-com-eligibility
source_date: '2026-11-09'
source_filename: captionpipe-com-eligibility.yml
source_heading: Eligibility
source_page: https://captionpipe.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaptionPipe\naid: captionpipe-com\nurl: https://captionpipe.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using CaptionPipe for a company, you confirm that you can bind that company, and \"you\" means\n    the company.\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher.\nrestricted_uses:\n- summary: Unlawful content\n  text: Send us anything unlawful, or any sexual content involving minors, which we will report.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: You need an account with a verified email address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher.\n"
source_yaml_url: https://artifacts.apis.io/captionpipe-com/eligibility/captionpipe-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CaptionPipe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Captions
- Subtitles
- Transcription
- MCP
- Automation
- AI Agents
---
