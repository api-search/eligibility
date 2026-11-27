---
api_specs:
- filename: google-workspace-allowlisteddomains-api-openapi.yml
  format: yaml
  label: Google Workspace Allowlisted Domains API
  slug: google-workspace-allowlisteddomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-allowlisteddomains-api-openapi.yml
- filename: google-workspace-customerlicense-api-openapi.yml
  format: yaml
  label: Google Workspace Customer License API
  slug: google-workspace-customerlicense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-customerlicense-api-openapi.yml
- filename: google-workspace-customers-api-openapi.yml
  format: yaml
  label: Google Workspace Customers API
  slug: google-workspace-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-customers-api-openapi.yml
- filename: google-workspace-devices-api-openapi.yml
  format: yaml
  label: Google Workspace Devices API
  slug: google-workspace-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-devices-api-openapi.yml
- filename: google-workspace-groups-api-openapi.yml
  format: yaml
  label: Google Workspace Groups API
  slug: google-workspace-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-groups-api-openapi.yml
- filename: google-workspace-inboundoidcssoprofiles-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound Oidc SSO Profiles API
  slug: google-workspace-inboundoidcssoprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundoidcssoprofiles-api-openapi.yml
- filename: google-workspace-inboundsamlssoprofiles-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound Saml SSO Profiles API
  slug: google-workspace-inboundsamlssoprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundsamlssoprofiles-api-openapi.yml
- filename: google-workspace-inboundssoassignments-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound SSO Assignments API
  slug: google-workspace-inboundssoassignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundssoassignments-api-openapi.yml
- filename: google-workspace-operations-api-openapi.yml
  format: yaml
  label: Google Workspace Operations API
  slug: google-workspace-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-operations-api-openapi.yml
- filename: google-workspace-policies-api-openapi.yml
  format: yaml
  label: Google Workspace Policies API
  slug: google-workspace-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-policies-api-openapi.yml
- filename: google-workspace-subscriptions-api-openapi.yml
  format: yaml
  label: Google Workspace Subscriptions API
  slug: google-workspace-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-subscriptions-api-openapi.yml
- filename: google-workspace-userlicense-api-openapi.yml
  format: yaml
  label: Google Workspace User License API
  slug: google-workspace-userlicense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-userlicense-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Customer will not allow End Users under the age of 18 to use Workspace Generative AI Services.
    value: '18'
  restricted_uses:
  - summary: No clinical/medical use of generative AI
    text: Customer will not, and will not allow End Users to, use Workspace Generative AI Services for clinical purposes
  - summary: No PHI in Pre-GA offerings
    text: Customer may not use Pre-GA Offerings to process Protected Health Information as defined in HIPAA.
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
name: Google Workspace
provenance_date: '2026-11-09'
provider_name: Google Workspace
provider_slug: google-workspace
slug: google-workspace-eligibility
source_date: '2026-11-09'
source_filename: google-workspace-eligibility.yml
source_heading: Eligibility
source_page: https://workspace.google.com/terms/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Workspace\naid: google-workspace\nurl: https://workspace.google.com/terms/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No clinical/medical use of generative AI\n  text: Customer will not, and will not allow End Users to, use Workspace Generative AI Services for clinical purposes\n- summary: No PHI in Pre-GA offerings\n  text: Customer may not use Pre-GA Offerings to process Protected Health Information as defined in HIPAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer will not allow End Users under the age of 18 to use Workspace Generative AI Services.\n"
source_yaml_url: https://artifacts.apis.io/google-workspace/eligibility/google-workspace-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Google Workspace's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Collaboration
- Email
- Productivity
- Storage
- Video Conferencing
- Google Workspace
---
