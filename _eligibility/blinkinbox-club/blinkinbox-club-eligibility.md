---
api_specs:
- filename: blinkinbox-club-account-api-openapi.yml
  format: yaml
  label: blinkinbox-club Account API
  slug: blinkinbox-club-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-account-api-openapi.yml
- filename: blinkinbox-club-domains-api-openapi.yml
  format: yaml
  label: blinkinbox-club Domains API
  slug: blinkinbox-club-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-domains-api-openapi.yml
- filename: blinkinbox-club-inboxes-api-openapi.yml
  format: yaml
  label: blinkinbox-club Inboxes API
  slug: blinkinbox-club-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-inboxes-api-openapi.yml
- filename: blinkinbox-club-messages-api-openapi.yml
  format: yaml
  label: blinkinbox-club Messages API
  slug: blinkinbox-club-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-messages-api-openapi.yml
- filename: blinkinbox-club-webhooks-api-openapi.yml
  format: yaml
  label: blinkinbox-club Webhooks API
  slug: blinkinbox-club-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for an organisation, you agree on its behalf.
    type: business
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Not for records you must keep
    text: 'Don’t use a BlinkInbox address for anything you need to keep : banking, work, government services, or any account you may need to recover later.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Use a real email address you control for a developer account; we’ll ask you to confirm it with a code.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: blinkinbox-club
provenance_date: '2026-11-09'
provider_name: blinkinbox-club
provider_slug: blinkinbox-club
slug: blinkinbox-club-eligibility
source_date: '2026-11-09'
source_filename: blinkinbox-club-eligibility.yml
source_heading: Eligibility
source_page: https://blinkinbox.club/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blinkinbox-club\naid: blinkinbox-club\nurl: https://blinkinbox.club/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for an organisation, you agree on its behalf.\nrestricted_uses:\n- summary: Not for records you must keep\n  text: 'Don’t use a BlinkInbox address for anything you need to keep : banking, work, government services, or any\n    account you may need to recover later.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Use a real email address you control for a developer account;\
  \ we’ll ask you to confirm it with a code.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/blinkinbox-club/eligibility/blinkinbox-club-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from blinkinbox-club's own page on 2026-11-09.
synthetic: false
tags:
- Email
- MCP
- Developer Tools
- Disposable
---
