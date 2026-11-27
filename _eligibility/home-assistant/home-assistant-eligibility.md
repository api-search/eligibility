---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: the Content is not pornographic, does not contain threats or incite violence, and does not violate the privacy or publicity rights of any third party
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
name: Home Assistant
provenance_date: '2026-11-09'
provider_name: Home Assistant
provider_slug: home-assistant
slug: home-assistant-eligibility
source_date: '2026-11-09'
source_filename: home-assistant-eligibility.yml
source_heading: Eligibility
source_page: https://www.home-assistant.io/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Home Assistant\naid: home-assistant\nurl: https://www.home-assistant.io/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: the Content is not pornographic, does not contain threats or incite violence, and does not violate the privacy\n    or publicity rights of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: The Website is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/home-assistant/eligibility/home-assistant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Home Assistant's own page on 2026-11-09.
synthetic: false
tags:
- Home Automation
- Open Source
- IoT
- Community
- Non-Profit
---
