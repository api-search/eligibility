---
api_specs:
- filename: georgiaautoquotes-com-agency-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Agency API
  slug: georgiaautoquotes-com-agency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-agency-api-openapi.yml
- filename: georgiaautoquotes-com-benchmark-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Benchmark API
  slug: georgiaautoquotes-com-benchmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-benchmark-api-openapi.yml
- filename: georgiaautoquotes-com-consent-record-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Consent Record API
  slug: georgiaautoquotes-com-consent-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-consent-record-api-openapi.yml
- filename: georgiaautoquotes-com-contact-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Contact API
  slug: georgiaautoquotes-com-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-contact-api-openapi.yml
- filename: georgiaautoquotes-com-dataset-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Dataset API
  slug: georgiaautoquotes-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-dataset-api-openapi.yml
- filename: georgiaautoquotes-com-eligibility-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Eligibility API
  slug: georgiaautoquotes-com-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-eligibility-api-openapi.yml
- filename: georgiaautoquotes-com-forget-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Forget API
  slug: georgiaautoquotes-com-forget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-forget-api-openapi.yml
- filename: georgiaautoquotes-com-join-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Join API
  slug: georgiaautoquotes-com-join-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-join-api-openapi.yml
- filename: georgiaautoquotes-com-prices-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Prices API
  slug: georgiaautoquotes-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-prices-api-openapi.yml
- filename: georgiaautoquotes-com-pull-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Pull API
  slug: georgiaautoquotes-com-pull-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-pull-api-openapi.yml
- filename: georgiaautoquotes-com-quotes-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Quotes API
  slug: georgiaautoquotes-com-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-quotes-api-openapi.yml
- filename: georgiaautoquotes-com-terms-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Terms API
  slug: georgiaautoquotes-com-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-terms-api-openapi.yml
- filename: georgiaautoquotes-com-verify-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Verify API
  slug: georgiaautoquotes-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-verify-api-openapi.yml
- filename: georgiaautoquotes-com-top-up-api-openapi.yml
  format: yaml
  label: georgiaautoquotes-com Top Up API
  slug: georgiaautoquotes-com-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/georgiaautoquotes-com/openapi/georgiaautoquotes-com-top-up-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Recipients are licensed agents appointed for the consumer's state; no country is named.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Contact details only with consent
    text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.
  - summary: No resale of contact details
    text: Licensed agents may contact the consumer and know who they are calling. No resale.
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
name: georgiaautoquotes-com
provenance_date: '2026-11-09'
provider_name: georgiaautoquotes-com
provider_slug: georgiaautoquotes-com
slug: georgiaautoquotes-com-eligibility
source_date: '2026-11-09'
source_filename: georgiaautoquotes-com-eligibility.yml
source_heading: Eligibility
source_page: https://georgiaautoquotes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: georgiaautoquotes-com\naid: georgiaautoquotes-com\nurl: https://georgiaautoquotes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Recipients are licensed agents appointed for the consumer's state; no country is named.\nentity_types: []\nrestricted_uses:\n- summary: Contact details only with consent\n  text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.\n- summary: No resale of contact details\n  text: Licensed agents may contact the consumer and know who they are calling. No resale.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/georgiaautoquotes-com/eligibility/georgiaautoquotes-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from georgiaautoquotes-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- AutoQuotes
- Georgia
- AI Integration
---
