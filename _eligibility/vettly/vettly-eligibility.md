---
api_specs:
- filename: vettly-moderation-api-openapi.yml
  format: yaml
  label: Vettly Moderation API
  slug: vettly-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-moderation-api-openapi.yml
- filename: vettly-system-api-openapi.yml
  format: yaml
  label: Vettly System API
  slug: vettly-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-system-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not be located in a country subject to a U.S. Government embargo or designated as a "terrorist supporting" country
  entity_types:
  - text: Be at least 18 years of age or the age of majority in your jurisdiction
    type: individual
  - text: 'If you are using the Services on behalf of an organization, company, or other legal entity, you represent and warrant that: (a) you have the authority to bind that entity to these Terms'
    type: business
  minimum_age:
    text: Be at least 18 years of age or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Hidden or coercive monitoring
    text: Use Vettly Family or Companion for hidden monitoring, coercive surveillance, or attempting to bypass platform privacy controls
  - summary: Censorship or viewpoint discrimination
    text: Censor political speech, suppress lawful expression, or engage in viewpoint discrimination
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Services, you must create an account by providing accurate, current, and complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vettly
provenance_date: '2026-11-10'
provider_name: Vettly
provider_slug: vettly
slug: vettly-eligibility
source_date: '2026-11-10'
source_filename: vettly-eligibility.yml
source_heading: Eligibility
source_page: https://vettly.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vettly\naid: vettly\nurl: https://vettly.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not be located in a country subject to a U.S. Government embargo or designated as a \"terrorist supporting\"\n    country\nentity_types:\n- type: individual\n  text: Be at least 18 years of age or the age of majority in your jurisdiction\n- type: business\n  text: 'If you are using the Services on behalf of an organization, company, or other legal entity, you represent\n    and warrant that: (a) you have the authority to bind that entity to these Terms'\nrestricted_uses:\n- summary:\
  \ Hidden or coercive monitoring\n  text: Use Vettly Family or Companion for hidden monitoring, coercive surveillance, or attempting to bypass platform\n    privacy controls\n- summary: Censorship or viewpoint discrimination\n  text: Censor political speech, suppress lawful expression, or engage in viewpoint discrimination\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Services, you must create an account by providing accurate, current, and complete information.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/vettly/eligibility/vettly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Vettly's own page on 2026-11-10.
synthetic: false
tags:
- Content Moderation
- Trust and Safety
- Security
- Text Analysis
- Image Moderation
- video-moderation
- UGC
- Compliance
- agent-guardrails
- MCP
---
