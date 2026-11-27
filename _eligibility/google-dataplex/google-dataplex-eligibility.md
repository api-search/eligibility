---
api_specs:
- filename: google-dataplex-projects-api-openapi.yml
  format: yaml
  label: Google Dataplex Projects API
  slug: google-dataplex-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-dataplex/openapi/google-dataplex-projects-api-openapi.yml
- filename: google-dataplex-organizations-api-openapi.yml
  format: yaml
  label: Google Dataplex Dataplex Organizations API
  slug: google-dataplex-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-dataplex/openapi/google-dataplex-organizations-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: But not all services mentioned may be available in your country.
  entity_types:
  - text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .
    type: business
  - text: If you meet these age requirements you can create a Google Account for your convenience.
    type: individual
  minimum_age:
    text: If you’re under the age required to manage your own Google Account , you must have your parent or legal guardian’s permission to use a Google Account.
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: comply with applicable laws, including export control, sanctions, and human trafficking laws
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
name: Google Dataplex
provenance_date: '2026-11-09'
provider_name: Google Dataplex
provider_slug: google-dataplex
slug: google-dataplex-eligibility
source_date: '2026-11-09'
source_filename: google-dataplex-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Dataplex\naid: google-dataplex\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: But not all services mentioned may be available in your country.\nentity_types:\n- type: business\n  text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .\n- type: individual\n  text: If you meet these age requirements you can create a Google Account for your convenience.\nrestricted_uses:\n- summary: Compliance with laws\n  text: comply with applicable laws, including export control, sanctions, and human\
  \ trafficking laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you’re under the age required to manage your own Google Account , you must have your parent or legal\n    guardian’s permission to use a Google Account.\n"
source_yaml_url: https://artifacts.apis.io/google-dataplex/eligibility/google-dataplex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Google Dataplex's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Governance
- Metadata Management
- Google Cloud
- AI Agents
---
