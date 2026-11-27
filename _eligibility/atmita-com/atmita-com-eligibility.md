---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Service is not intended for users under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Harmful AI content
    text: Abuse AI features to generate harmful, misleading, or illegal content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must sign in using a supported sign-in method - currently Google, Apple, or a one-time code sent to an email address you provide.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atmita
provenance_date: '2026-11-09'
provider_name: Atmita
provider_slug: atmita-com
slug: atmita-com-eligibility
source_date: '2026-11-09'
source_filename: atmita-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.atmita.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atmita\naid: atmita-com\nurl: https://www.atmita.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful AI content\n  text: Abuse AI features to generate harmful, misleading, or illegal content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must sign in using a supported sign-in method - currently Google, Apple, or a one-time\n    code sent to an email address you provide.\nminimum_age:\n  value: '13'\n  text: The Service is not intended for users under 13 years\
  \ of age.\n"
source_yaml_url: https://artifacts.apis.io/atmita-com/eligibility/atmita-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Atmita's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Software-as-a-Service
- Agents
---
