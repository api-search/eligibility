---
api_specs:
- filename: certifier-io-credential-interactions-api-openapi.yml
  format: yaml
  label: Certifier Credential Interactions API
  slug: certifier-io-credential-interactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifier-io/openapi/certifier-io-credential-interactions-api-openapi.yml
- filename: certifier-io-credential-templates-api-openapi.yml
  format: yaml
  label: Certifier Credential Templates API
  slug: certifier-io-credential-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifier-io/openapi/certifier-io-credential-templates-api-openapi.yml
- filename: certifier-io-credentials-api-openapi.yml
  format: yaml
  label: Certifier Credentials API
  slug: certifier-io-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifier-io/openapi/certifier-io-credentials-api-openapi.yml
- filename: certifier-io-design-templates-api-openapi.yml
  format: yaml
  label: Certifier Design Templates API
  slug: certifier-io-design-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifier-io/openapi/certifier-io-design-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User – a natural or legal person or an organisational entity who orders Services in direct connection with the pursued business or professional activity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content categories
    text: 'You may not generate in Certifier or use within the frames of the Services any Content which may: (a) infringe personal rights or interests of third parties'
  - summary: Special category personal data
    text: you agree that you will not enter into the Certifier any personal data that constitute special categories of personal data within the meaning of Article 9(1) of the GDPR.
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
name: Certifier
provenance_date: '2026-11-09'
provider_name: Certifier
provider_slug: certifier-io
slug: certifier-io-eligibility
source_date: '2026-11-09'
source_filename: certifier-io-eligibility.yml
source_heading: Eligibility
source_page: https://certifier.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certifier\naid: certifier-io\nurl: https://certifier.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: User – a natural or legal person or an organisational entity who orders Services in direct connection with\n    the pursued business or professional activity\nrestricted_uses:\n- summary: Prohibited content categories\n  text: 'You may not generate in Certifier or use within the frames of the Services any Content which may: (a) infringe\n    personal rights or interests of third parties'\n- summary: Special category personal\
  \ data\n  text: you agree that you will not enter into the Certifier any personal data that constitute special categories\n    of personal data within the meaning of Article 9(1) of the GDPR.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/certifier-io/eligibility/certifier-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Certifier's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Certificate
- Artificial Intelligence
- Automation
- Credentials
---
