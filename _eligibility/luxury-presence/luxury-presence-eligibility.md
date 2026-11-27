---
api_specs:
- filename: luxury-presence-agents-api-openapi.yml
  format: yaml
  label: Luxury Presence Agents API
  slug: luxury-presence-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luxury-presence/openapi/luxury-presence-agents-api-openapi.yml
- filename: luxury-presence-media-api-openapi.yml
  format: yaml
  label: Luxury Presence Media API
  slug: luxury-presence-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luxury-presence/openapi/luxury-presence-media-api-openapi.yml
- filename: luxury-presence-offices-api-openapi.yml
  format: yaml
  label: Luxury Presence Offices API
  slug: luxury-presence-offices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luxury-presence/openapi/luxury-presence-offices-api-openapi.yml
- filename: luxury-presence-teams-api-openapi.yml
  format: yaml
  label: Luxury Presence Teams API
  slug: luxury-presence-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luxury-presence/openapi/luxury-presence-teams-api-openapi.yml
- filename: luxury-presence-webhooks-api-openapi.yml
  format: yaml
  label: Luxury Presence Webhooks API
  slug: luxury-presence-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luxury-presence/openapi/luxury-presence-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for the Luxury Presence Services on behalf of an organization, you warrant that you are authorized to agree to this Agreement on their behalf.
    type: business
  minimum_age:
    text: The Luxury Presence Services are not intended for individuals under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No discriminatory housing advertising
    text: create, publish, or distribute any advertisement that indicates a preference or limitation based on a protected characteristic
  - summary: No sensitive or regulated data upload
    text: you will not upload to the Luxury Presence Services or otherwise provide to Luxury Presence any sensitive or regulated data, information or other content
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
name: Luxury Presence
provenance_date: '2026-11-10'
provider_name: Luxury Presence
provider_slug: luxury-presence
slug: luxury-presence-eligibility
source_date: '2026-11-10'
source_filename: luxury-presence-eligibility.yml
source_heading: Eligibility
source_page: https://www.luxurypresence.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luxury Presence\naid: luxury-presence\nurl: https://www.luxurypresence.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for the Luxury Presence Services on behalf of an organization, you warrant that you\n    are authorized to agree to this Agreement on their behalf.\nrestricted_uses:\n- summary: No discriminatory housing advertising\n  text: create, publish, or distribute any advertisement that indicates a preference or limitation based on a protected\n    characteristic\n\
  - summary: No sensitive or regulated data upload\n  text: you will not upload to the Luxury Presence Services or otherwise provide to Luxury Presence any sensitive\n    or regulated data, information or other content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Luxury Presence Services are not intended for individuals under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/luxury-presence/eligibility/luxury-presence-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Luxury Presence's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Real Estate
- PropTech
- CRM
- Marketing
- Websites
- Webhook
- Lead Generation
---
