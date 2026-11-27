---
api_specs:
- filename: therankingfactory-com-public-api-openapi.yml
  format: yaml
  label: therankingfactory-com Public API
  slug: therankingfactory-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/therankingfactory-com/openapi/therankingfactory-com-public-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and using the Service for a business or professional purpose.
    type: individual
  - text: If you use the Service for a business, you confirm you are authorized to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and using the Service for a business or professional purpose.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Do not use the Service for illegal activity, or to publish content that is unlawful, misleading, infringing or harmful.
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
name: therankingfactory-com
provenance_date: '2026-11-10'
provider_name: therankingfactory-com
provider_slug: therankingfactory-com
slug: therankingfactory-com-eligibility
source_date: '2026-11-10'
source_filename: therankingfactory-com-eligibility.yml
source_heading: Eligibility
source_page: https://therankingfactory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: therankingfactory-com\naid: therankingfactory-com\nurl: https://therankingfactory.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and using the Service for a business or professional purpose.\n- type: business\n  text: If you use the Service for a business, you confirm you are authorized to accept these Terms for it.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Do not use the Service for illegal activity, or to publish content that is unlawful, misleading, infringing\n\
  \    or harmful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and using the Service for a business or professional purpose.\n"
source_yaml_url: https://artifacts.apis.io/therankingfactory-com/eligibility/therankingfactory-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from therankingfactory-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Marketing
- Analytics
- Automation
---
