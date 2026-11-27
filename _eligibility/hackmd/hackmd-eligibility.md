---
api_specs:
- filename: hackmd-history-api-openapi.yml
  format: yaml
  label: HackMD History API
  slug: hackmd-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-history-api-openapi.yml
- filename: hackmd-profile-api-openapi.yml
  format: yaml
  label: HackMD Profile API
  slug: hackmd-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-profile-api-openapi.yml
- filename: hackmd-team-folders-api-openapi.yml
  format: yaml
  label: HackMD Team Folders API
  slug: hackmd-team-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-team-folders-api-openapi.yml
- filename: hackmd-team-notes-api-openapi.yml
  format: yaml
  label: HackMD Team Notes API
  slug: hackmd-team-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-team-notes-api-openapi.yml
- filename: hackmd-teams-api-openapi.yml
  format: yaml
  label: HackMD Teams API
  slug: hackmd-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-teams-api-openapi.yml
- filename: hackmd-trash-api-openapi.yml
  format: yaml
  label: HackMD Trash API
  slug: hackmd-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-trash-api-openapi.yml
- filename: hackmd-user-folders-api-openapi.yml
  format: yaml
  label: HackMD User Folders API
  slug: hackmd-user-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-user-folders-api-openapi.yml
- filename: hackmd-user-notes-api-openapi.yml
  format: yaml
  label: HackMD User Notes API
  slug: hackmd-user-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-user-notes-api-openapi.yml
- filename: hackmd-comments-api-openapi.yml
  format: yaml
  label: HackMD Comments API
  slug: hackmd-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-comments-api-openapi.yml
- filename: hackmd-team-webhooks-api-openapi.yml
  format: yaml
  label: HackMD Team Webhooks API
  slug: hackmd-team-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-team-webhooks-api-openapi.yml
- filename: hackmd-versions-api-openapi.yml
  format: yaml
  label: HackMD Versions API
  slug: hackmd-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-versions-api-openapi.yml
- filename: hackmd-webhooks-api-openapi.yml
  format: yaml
  label: HackMD Webhooks API
  slug: hackmd-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hackmd/openapi/hackmd-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Customer enters into this Terms of Service on behalf of a company or other legal entity, it represents that it has the authority to bind such entity and all users who access the HackMD Service through the Customer's account
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 13. You must ensure that all your account users are over 13 years old.
    value: '13'
  restricted_uses:
  - summary: Users under 13
    text: The Services are not intended for and should not be used by anyone under the age of 13.
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
name: HackMD
provenance_date: '2026-11-09'
provider_name: HackMD
provider_slug: hackmd
slug: hackmd-eligibility
source_date: '2026-11-09'
source_filename: hackmd-eligibility.yml
source_heading: Eligibility
source_page: https://hackmd.io/s/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HackMD\naid: hackmd\nurl: https://hackmd.io/s/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the Customer enters into this Terms of Service on behalf of a company or other legal entity, it represents\n    that it has the authority to bind such entity and all users who access the HackMD Service through the Customer's\n    account\nrestricted_uses:\n- summary: Users under 13\n  text: The Services are not intended for and should not be used by anyone under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not intended for and should not be used by anyone under the age of 13. You must ensure\n    that all your account users are over 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/hackmd/eligibility/hackmd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from HackMD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Markdown
- Collaboration
- Documentation
- Note Taking
- Knowledge Base
- Productivity
- Content
---
