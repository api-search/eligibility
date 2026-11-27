---
api_specs:
- filename: faable-com-openapi-generated.yml
  format: yaml
  label: Faable API
  slug: faable-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/faable-com/openapi/_ae-authored/faable-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept this Agreement on behalf of a company or other legal entity, you represent that you have authority to bind that entity, and “you” refers to that entity.
    type: business
  - text: To use the Services you must be at least 18 years old and provide accurate, current information.
    type: individual
  minimum_age:
    text: To use the Services you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: runs phishing , credential-harvesting, fake login, or impersonation pages; sends spam or unsolicited bulk email
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
name: Faable
provenance_date: '2026-11-09'
provider_name: Faable
provider_slug: faable-com
slug: faable-com-eligibility
source_date: '2026-11-09'
source_filename: faable-com-eligibility.yml
source_heading: Eligibility
source_page: https://faable.com/docs/platform/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Faable\naid: faable-com\nurl: https://faable.com/docs/platform/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept this Agreement on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity, and “you” refers to that entity.\n- type: individual\n  text: To use the Services you must be at least 18 years old and provide accurate, current information.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: runs phishing , credential-harvesting, fake login,\
  \ or impersonation pages; sends spam or unsolicited bulk\n    email\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Services you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/faable-com/eligibility/faable-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Faable's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- ZeroOps
- Hosting
- Identity
- GDPR
- Software-as-a-Service
---
