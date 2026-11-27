---
api_specs:
- filename: argorant-com-account-api-openapi.yml
  format: yaml
  label: Argorant Account API
  slug: argorant-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-account-api-openapi.yml
- filename: argorant-com-blocklist-api-openapi.yml
  format: yaml
  label: Argorant Blocklist API
  slug: argorant-com-blocklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-blocklist-api-openapi.yml
- filename: argorant-com-campaigns-api-openapi.yml
  format: yaml
  label: Argorant Campaigns API
  slug: argorant-com-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-campaigns-api-openapi.yml
- filename: argorant-com-companies-api-openapi.yml
  format: yaml
  label: Argorant Companies API
  slug: argorant-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-companies-api-openapi.yml
- filename: argorant-com-credits-api-openapi.yml
  format: yaml
  label: Argorant Credits API
  slug: argorant-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-credits-api-openapi.yml
- filename: argorant-com-email-finder-api-openapi.yml
  format: yaml
  label: Argorant Email finder API
  slug: argorant-com-email-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-email-finder-api-openapi.yml
- filename: argorant-com-enrich-api-openapi.yml
  format: yaml
  label: Argorant Enrich API
  slug: argorant-com-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-enrich-api-openapi.yml
- filename: argorant-com-exports-api-openapi.yml
  format: yaml
  label: Argorant Exports API
  slug: argorant-com-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-exports-api-openapi.yml
- filename: argorant-com-inbox-api-openapi.yml
  format: yaml
  label: Argorant Inbox API
  slug: argorant-com-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-inbox-api-openapi.yml
- filename: argorant-com-integrations-api-openapi.yml
  format: yaml
  label: Argorant Integrations API
  slug: argorant-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-integrations-api-openapi.yml
- filename: argorant-com-lists-api-openapi.yml
  format: yaml
  label: Argorant Lists API
  slug: argorant-com-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-lists-api-openapi.yml
- filename: argorant-com-lookups-api-openapi.yml
  format: yaml
  label: Argorant Lookups API
  slug: argorant-com-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-lookups-api-openapi.yml
- filename: argorant-com-mailboxes-api-openapi.yml
  format: yaml
  label: Argorant Mailboxes API
  slug: argorant-com-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-mailboxes-api-openapi.yml
- filename: argorant-com-people-api-openapi.yml
  format: yaml
  label: Argorant People API
  slug: argorant-com-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-people-api-openapi.yml
- filename: argorant-com-verification-api-openapi.yml
  format: yaml
  label: Argorant Verification API
  slug: argorant-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-verification-api-openapi.yml
- filename: argorant-com-webhooks-api-openapi.yml
  format: yaml
  label: Argorant Webhooks API
  slug: argorant-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argorant-com/openapi/argorant-com-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  - text: If you use Argorant on behalf of a company or other organization, you represent that you are authorized to bind that organization, and "you" refers to it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: No FCRA or eligibility use
    text: (f) use the service or any data from it as a factor in establishing eligibility for credit, employment, insurance, housing, tenancy, education, government benefits, or any other purpose regulated by the Fair Credit Reporting Act or similar laws
  - summary: No sensitive-characteristic targeting or harassment
    text: (g) use the service for unlawful purposes, harassment, stalking, threats, discrimination, or to infer or target sensitive characteristics such as health, religion, race or ethnicity, political views, union membership, or sexual orientation
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
name: Argorant
provenance_date: '2026-11-09'
provider_name: Argorant
provider_slug: argorant-com
slug: argorant-com-eligibility
source_date: '2026-11-09'
source_filename: argorant-com-eligibility.yml
source_heading: Eligibility
source_page: https://argorant.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Argorant\naid: argorant-com\nurl: https://argorant.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\n- type: business\n  text: If you use Argorant on behalf of a company or other organization, you represent that you are authorized\n    to bind that organization, and \"you\" refers to it.\nrestricted_uses:\n- summary: No FCRA or eligibility use\n  text: (f) use the service or any data from it as a factor in establishing eligibility for credit, employment,\n\
  \    insurance, housing, tenancy, education, government benefits, or any other purpose regulated by the Fair Credit\n    Reporting Act or similar laws\n- summary: No sensitive-characteristic targeting or harassment\n  text: (g) use the service for unlawful purposes, harassment, stalking, threats, discrimination, or to infer or\n    target sensitive characteristics such as health, religion, race or ethnicity, political views, union membership,\n    or sexual orientation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/argorant-com/eligibility/argorant-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Argorant's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Data
- Email Verification
- Artificial Intelligence
- Outreach
- Software-as-a-Service
---
