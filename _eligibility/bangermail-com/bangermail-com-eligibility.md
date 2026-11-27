---
api_specs:
- filename: bangermail-com-forms-api-openapi.yml
  format: yaml
  label: BangerMail Inc. Forms API
  slug: bangermail-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bangermail-com/openapi/bangermail-com-forms-api-openapi.yml
- filename: bangermail-com-workspaces-api-openapi.yml
  format: yaml
  label: BangerMail Inc. Workspaces API
  slug: bangermail-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bangermail-com/openapi/bangermail-com-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Banger on behalf of a company or other organization, you confirm that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You may use Banger only if you can form a binding agreement and are at least sixteen years old.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful email
    text: do not use Banger for unlawful, deceptive, or harmful email
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
name: BangerMail Inc.
provenance_date: '2026-11-09'
provider_name: BangerMail Inc.
provider_slug: bangermail-com
slug: bangermail-com-eligibility
source_date: '2026-11-09'
source_filename: bangermail-com-eligibility.yml
source_heading: Eligibility
source_page: https://bangermail.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BangerMail Inc.\naid: bangermail-com\nurl: https://bangermail.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Banger on behalf of a company or other organization, you confirm that you have authority to bind\n    that organization to these Terms\nrestricted_uses:\n- summary: Unlawful or harmful email\n  text: do not use Banger for unlawful, deceptive, or harmful email\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use Banger only if\
  \ you can form a binding agreement and are at least sixteen years old.\n"
source_yaml_url: https://artifacts.apis.io/bangermail-com/eligibility/bangermail-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BangerMail Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Artificial Intelligence
- Automation
- Software-as-a-Service
- Marketing
---
