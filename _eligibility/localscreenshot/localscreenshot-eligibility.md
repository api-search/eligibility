---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or company.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Capturing pages without right or illegal use
    text: public pages only, nothing illegal, nothing that harms a website or a person.
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
name: localscreenshot
provenance_date: '2026-11-09'
provider_name: localscreenshot
provider_slug: localscreenshot
slug: localscreenshot-eligibility
source_date: '2026-11-09'
source_filename: localscreenshot-eligibility.yml
source_heading: Eligibility
source_page: https://localscreenshot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: localscreenshot\naid: localscreenshot\nurl: https://localscreenshot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: One account per person or company.\nrestricted_uses:\n- summary: Capturing pages without right or illegal use\n  text: public pages only, nothing illegal, nothing that harms a website or a person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/localscreenshot/eligibility/localscreenshot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from localscreenshot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Screenshots
- Artificial Intelligence
- Automation
---
