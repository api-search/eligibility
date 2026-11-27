---
api_specs:
- filename: usersnap-feedback-api-openapi.yml
  format: yaml
  label: Usersnap Feedback API
  slug: usersnap-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-feedback-api-openapi.yml
- filename: usersnap-pre-submit-api-openapi.yml
  format: yaml
  label: Usersnap Pre Submit API
  slug: usersnap-pre-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-pre-submit-api-openapi.yml
- filename: usersnap-project-api-openapi.yml
  format: yaml
  label: Usersnap Project API
  slug: usersnap-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-project-api-openapi.yml
- filename: usersnap-submit-api-openapi.yml
  format: yaml
  label: Usersnap Submit API
  slug: usersnap-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usersnap/openapi/usersnap-submit-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ You” / “Your” / “Client ” means a person, whether natural or legal, acting in the course of a trade or business, and who agrees to be bound by the terms contained in this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or objectionable sites
    text: sites containing illegal material
  - summary: Adult content and hacker programs
    text: sites containing adult-oriented content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Usersnap reserves the right to refuse, cancel or suspend services to any client, at its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Usersnap
provenance_date: '2026-11-10'
provider_name: Usersnap
provider_slug: usersnap
slug: usersnap-eligibility
source_date: '2026-11-10'
source_filename: usersnap-eligibility.yml
source_heading: Eligibility
source_page: https://usersnap.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Usersnap\naid: usersnap\nurl: https://usersnap.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ You” / “Your” / “Client ” means a person, whether natural or legal, acting in the course of a trade or\n    business, and who agrees to be bound by the terms contained in this Agreement.\nrestricted_uses:\n- summary: Illegal or objectionable sites\n  text: sites containing illegal material\n- summary: Adult content and hacker programs\n  text: sites containing adult-oriented content\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: Usersnap reserves the right to refuse, cancel or suspend services to any client, at its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usersnap/eligibility/usersnap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Usersnap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Feedback
- Bug Tracking
- Customer Experience
- Product Management
- Surveys
- Software-as-a-Service
---
