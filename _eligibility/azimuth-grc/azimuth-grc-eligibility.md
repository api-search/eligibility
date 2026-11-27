---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: End User represents and warrants that it is not located in a country subject to a U.S. Government embargo or designated by the U.S. Government as a "terrorist supporting" country.
  entity_types:
  - text: If you are accepting on behalf of an entity, you represent and warrant that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PII or personal financial information in prompts
    text: End Users shall not type or otherwise introduce PII or personal financial information into any Prompt.
  - summary: No content or agentic tasks
    text: Induce the model to execute code or perform "agentic" tasks outside of delivering plain-English answers and supporting information in response to textual questions.
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
name: Azimuth GRC
provenance_date: '2026-11-09'
provider_name: Azimuth GRC
provider_slug: azimuth-grc
slug: azimuth-grc-eligibility
source_date: '2026-11-09'
source_filename: azimuth-grc-eligibility.yml
source_heading: Eligibility
source_page: https://www.azimuthgrc.com/subscription-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azimuth GRC\naid: azimuth-grc\nurl: https://www.azimuthgrc.com/subscription-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: End User represents and warrants that it is not located in a country subject to a U.S. Government embargo\n    or designated by the U.S. Government as a \"terrorist supporting\" country.\nentity_types:\n- type: business\n  text: If you are accepting on behalf of an entity, you represent and warrant that you have the authority to bind\n    such entity.\nrestricted_uses:\n- summary: No PII or personal financial information in prompts\n  text: End Users\
  \ shall not type or otherwise introduce PII or personal financial information into any Prompt.\n- summary: No content or agentic tasks\n  text: Induce the model to execute code or perform \"agentic\" tasks outside of delivering plain-English answers\n    and supporting information in response to textual questions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/azimuth-grc/eligibility/azimuth-grc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Azimuth GRC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Governance
- Risk Management
- Automation
- Software-as-a-Service
---
