---
claim_count: 3
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
  - summary: Unlawful use
    text: Violate any laws or regulations.
  - summary: Hate or violence via LLMs
    text: Not use LLMs to promote hate, discrimination, or violence.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, User must register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wordware
provenance_date: '2026-11-10'
provider_name: Wordware
provider_slug: wordware
slug: wordware-eligibility
source_date: '2026-11-10'
source_filename: wordware-eligibility.yml
source_heading: Eligibility
source_page: https://www.wordware.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wordware\naid: wordware\nurl: https://www.wordware.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Violate any laws or regulations.\n- summary: Hate or violence via LLMs\n  text: Not use LLMs to promote hate, discrimination, or violence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, User must register for an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wordware/eligibility/wordware-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Wordware's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- AI Agents
- LLM
- Prompt Engineering
- Workflow Automation
- No-Code
- Company
---
