---
api_specs:
- filename: editsquare-projects-api-openapi.yml
  format: yaml
  label: Edit Square Projects API
  slug: editsquare-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-projects-api-openapi.yml
- filename: editsquare-renders-api-openapi.yml
  format: yaml
  label: Edit Square Renders API
  slug: editsquare-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-renders-api-openapi.yml
- filename: editsquare-teams-api-openapi.yml
  format: yaml
  label: Edit Square Teams API
  slug: editsquare-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-teams-api-openapi.yml
- filename: editsquare-templates-api-openapi.yml
  format: yaml
  label: Edit Square Templates API
  slug: editsquare-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-templates-api-openapi.yml
- filename: editsquare-users-api-openapi.yml
  format: yaml
  label: Edit Square Users API
  slug: editsquare-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer (an individual buying for purposes outside your trade, business or profession), you have a legal right to cancel within 14 days of your first purchase.
    type: individual
  - text: If you use the Services on behalf of a company or other organisation, you confirm that you have authority to bind that organisation to these Terms
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Services. If you are under 18, you may only purchase a plan with the permission of a parent or guardian.
    value: '16'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: use the Services to store, create, distribute or transmit anything that is unlawful, infringing, defamatory, harassing, sexually explicit involving minors, or that promotes violence or discrimination
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
name: Edit Square
provenance_date: '2026-11-09'
provider_name: Edit Square
provider_slug: editsquare
slug: editsquare-eligibility
source_date: '2026-11-09'
source_filename: editsquare-eligibility.yml
source_heading: Eligibility
source_page: https://editsquare.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edit Square\naid: editsquare\nurl: https://editsquare.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer (an individual buying for purposes outside your trade, business or profession), you\n    have a legal right to cancel within 14 days of your first purchase.\n- type: business\n  text: If you use the Services on behalf of a company or other organisation, you confirm that you have authority\n    to bind that organisation to these Terms\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text:\
  \ use the Services to store, create, distribute or transmit anything that is unlawful, infringing, defamatory,\n    harassing, sexually explicit involving minors, or that promotes violence or discrimination\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Services. If you are under 18, you may only purchase a plan\n    with the permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/editsquare/eligibility/editsquare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Edit Square's own page on 2026-11-09.
synthetic: false
tags:
- Motion Graphics
- Video Editing
- Cloud Rendering
---
