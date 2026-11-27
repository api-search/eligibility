---
api_specs:
- filename: andromeda-ai-openapi-generated.yml
  format: yaml
  label: Andromeda API
  slug: andromeda-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andromeda-ai/openapi/_ae-authored/andromeda-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of a company or other organization, you represent that you have authority to bind it
    type: business
  - text: If you are a U.S. government entity, the Services constitute “Commercial Items” as defined at 48 C.F.R. § 2.101
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: you will not access or use the Services from, or for the benefit of any person in, a country or region, or for an end use, for which a U.S. export license is required and has not been obtained.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Andromeda may ask you to verify your identity, your organization, the locations from which you access the Services, and your intended use, before or after you transact.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Andromeda
provenance_date: '2026-11-09'
provider_name: Andromeda
provider_slug: andromeda-ai
slug: andromeda-ai-eligibility
source_date: '2026-11-09'
source_filename: andromeda-ai-eligibility.yml
source_heading: Eligibility
source_page: https://andromeda.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andromeda\naid: andromeda-ai\nurl: https://andromeda.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of a company or other organization, you represent that you have authority\n    to bind it\n- type: government\n  text: If you are a U.S. government entity, the Services constitute “Commercial Items” as defined at 48 C.F.R.\n    § 2.101\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: you will not access or use the Services from, or for the benefit of any person in, a\
  \ country or region,\n    or for an end use, for which a U.S. export license is required and has not been obtained.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Andromeda may ask you to verify your identity, your organization, the locations from which you access the\n    Services, and your intended use, before or after you transact.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/andromeda-ai/eligibility/andromeda-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Andromeda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cloud
- Platform
- Machine Learning
- Enterprise
---
