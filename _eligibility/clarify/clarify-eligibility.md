---
api_specs:
- filename: clarify-activities-api-openapi.yml
  format: yaml
  label: Clarify Activities API
  slug: clarify-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-activities-api-openapi.yml
- filename: clarify-campaigns-api-openapi.yml
  format: yaml
  label: Clarify Campaigns API
  slug: clarify-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-campaigns-api-openapi.yml
- filename: clarify-comments-api-openapi.yml
  format: yaml
  label: Clarify Comments API
  slug: clarify-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-comments-api-openapi.yml
- filename: clarify-invitations-api-openapi.yml
  format: yaml
  label: Clarify Invitations API
  slug: clarify-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-invitations-api-openapi.yml
- filename: clarify-layouts-api-openapi.yml
  format: yaml
  label: Clarify Layouts API
  slug: clarify-layouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-layouts-api-openapi.yml
- filename: clarify-listrows-api-openapi.yml
  format: yaml
  label: Clarify List Rows API
  slug: clarify-listrows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-listrows-api-openapi.yml
- filename: clarify-lists-api-openapi.yml
  format: yaml
  label: Clarify Lists API
  slug: clarify-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-lists-api-openapi.yml
- filename: clarify-meetingrecordings-api-openapi.yml
  format: yaml
  label: Clarify Meeting Recordings API
  slug: clarify-meetingrecordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-meetingrecordings-api-openapi.yml
- filename: clarify-objectaccess-api-openapi.yml
  format: yaml
  label: Clarify Object Access API
  slug: clarify-objectaccess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-objectaccess-api-openapi.yml
- filename: clarify-recordaccess-api-openapi.yml
  format: yaml
  label: Clarify Record Access API
  slug: clarify-recordaccess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-recordaccess-api-openapi.yml
- filename: clarify-recordattachments-api-openapi.yml
  format: yaml
  label: Clarify Record Attachments API
  slug: clarify-recordattachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-recordattachments-api-openapi.yml
- filename: clarify-recordrelationships-api-openapi.yml
  format: yaml
  label: Clarify Record Relationships API
  slug: clarify-recordrelationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-recordrelationships-api-openapi.yml
- filename: clarify-records-api-openapi.yml
  format: yaml
  label: Clarify Records API
  slug: clarify-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-records-api-openapi.yml
- filename: clarify-resources-api-openapi.yml
  format: yaml
  label: Clarify Resources API
  slug: clarify-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-resources-api-openapi.yml
- filename: clarify-schemas-api-openapi.yml
  format: yaml
  label: Clarify Schemas API
  slug: clarify-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-schemas-api-openapi.yml
- filename: clarify-users-api-openapi.yml
  format: yaml
  label: Clarify Users API
  slug: clarify-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-users-api-openapi.yml
- filename: clarify-workflows-api-openapi.yml
  format: yaml
  label: Clarify Workflows API
  slug: clarify-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-workflows-api-openapi.yml
- filename: clarify-workspacesettings-api-openapi.yml
  format: yaml
  label: Clarify Workspace Settings API
  slug: clarify-workspacesettings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-workspacesettings-api-openapi.yml
- filename: clarify-api-keys-api-openapi.yml
  format: yaml
  label: Clarify API Keys API
  slug: clarify-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarify/openapi/clarify-api-keys-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a legally binding contract with us
    type: individual
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's employer
    type: business
  minimum_age:
    text: which is under the age of 18 in most jurisdictions
    value: '18'
  restricted_uses:
  - summary: Minors
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction is strictly prohibited
  - summary: Commercial solicitation
    text: use the Service for any commercial solicitation purposes
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
name: Clarify
provenance_date: '2026-11-09'
provider_name: Clarify
provider_slug: clarify
slug: clarify-eligibility
source_date: '2026-11-09'
source_filename: clarify-eligibility.yml
source_heading: Eligibility
source_page: https://www.clarify.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clarify\naid: clarify\nurl: https://www.clarify.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a legally binding contract with us\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's\n    employer\nrestricted_uses:\n- summary: Minors\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable\
  \ jurisdiction is strictly prohibited\n- summary: Commercial solicitation\n  text: use the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: which is under the age of 18 in most jurisdictions\n"
source_yaml_url: https://artifacts.apis.io/clarify/eligibility/clarify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clarify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Artificial Intelligence
- Automation
- Sales
---
