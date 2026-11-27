---
api_specs:
- filename: bugmojo-com-openapi-generated.yml
  format: yaml
  label: BugMojo API
  slug: bugmojo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bugmojo-com/openapi/_ae-authored/bugmojo-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use BugMojo.
    value: '16'
  restricted_uses:
  - summary: No unlawful personal data capture
    text: capture, upload, or store data you don’t have the right to collect, including other people’s personal data without a lawful basis
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
name: BugMojo
provenance_date: '2026-11-09'
provider_name: BugMojo
provider_slug: bugmojo-com
slug: bugmojo-com-eligibility
source_date: '2026-11-09'
source_filename: bugmojo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bugmojo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BugMojo\naid: bugmojo-com\nurl: https://www.bugmojo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: No unlawful personal data capture\n  text: capture, upload, or store data you don’t have the right to collect, including other people’s personal data\n    without a lawful basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: You must be at least 16 years old to use BugMojo.\n"
source_yaml_url: https://artifacts.apis.io/bugmojo-com/eligibility/bugmojo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BugMojo's own page on 2026-11-09.
synthetic: false
tags:
- Bug Tracking
- Artificial Intelligence
- Developer Tools
- Session Replay
- Open Source
---
