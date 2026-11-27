---
api_specs:
- filename: jithox-com-iban-api-openapi.yml
  format: yaml
  label: jithox-com Iban API
  slug: jithox-com-iban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-iban-api-openapi.yml
- filename: jithox-com-invoice-api-openapi.yml
  format: yaml
  label: jithox-com Invoice API
  slug: jithox-com-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-invoice-api-openapi.yml
- filename: jithox-com-payment-api-openapi.yml
  format: yaml
  label: jithox-com Payment API
  slug: jithox-com-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-payment-api-openapi.yml
- filename: jithox-com-peppol-api-openapi.yml
  format: yaml
  label: jithox-com Peppol API
  slug: jithox-com-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-peppol-api-openapi.yml
- filename: jithox-com-vat-api-openapi.yml
  format: yaml
  label: jithox-com Vat API
  slug: jithox-com-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-vat-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only connect mailboxes and numbers you are entitled to use for your business.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No misleading, spam, harassment or impersonation
    text: Do not use Jithox to mislead, spam, harass or impersonate anyone.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The three priced tools require verified access and sufficient balance or applicable trial credit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: jithox-com
provenance_date: '2026-11-09'
provider_name: jithox-com
provider_slug: jithox-com
slug: jithox-com-eligibility
source_date: '2026-11-09'
source_filename: jithox-com-eligibility.yml
source_heading: Eligibility
source_page: https://jithox.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jithox-com\naid: jithox-com\nurl: https://jithox.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Only connect mailboxes and numbers you are entitled to use for your business.\nrestricted_uses:\n- summary: No misleading, spam, harassment or impersonation\n  text: Do not use Jithox to mislead, spam, harass or impersonate anyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The three priced tools require verified access and sufficient balance or applicable trial credit.\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/jithox-com/eligibility/jithox-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from jithox-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Back Office
- Tools
---
