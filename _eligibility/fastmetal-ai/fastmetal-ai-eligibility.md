---
api_specs:
- filename: fastmetal-ai-api-openapi-generated.yml
  format: yaml
  label: fastmetal-ai api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastmetal-ai/openapi/_ae-authored/fastmetal-ai-api-openapi-generated.yml
- filename: fastmetal-ai-core-openapi-generated.yml
  format: yaml
  label: fastmetal-ai core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastmetal-ai/openapi/_ae-authored/fastmetal-ai-core-openapi-generated.yml
- filename: fastmetal-ai-guides-openapi-generated.yml
  format: yaml
  label: fastmetal-ai All guides API
  slug: guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastmetal-ai/openapi/_ae-authored/fastmetal-ai-guides-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual, corporation or other organisation that agrees to these Terms
    type: individual
  - text: Where it agrees to these Terms on behalf of a corporation or other organisation, it has authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: It is at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Anti-social forces excluded
    text: It is not an Anti-Social Force as defined in Article 25.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Registration is complete, and a service contract on these Terms is formed between the User and the Company, when the Company approves the application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: fastmetal-ai
provenance_date: '2026-11-09'
provider_name: fastmetal-ai
provider_slug: fastmetal-ai
slug: fastmetal-ai-eligibility
source_date: '2026-11-09'
source_filename: fastmetal-ai-eligibility.yml
source_heading: Eligibility
source_page: https://fastmetal.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fastmetal-ai\naid: fastmetal-ai\nurl: https://fastmetal.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual, corporation or other organisation that agrees to these Terms\n- type: business\n  text: Where it agrees to these Terms on behalf of a corporation or other organisation, it has authority to bind\n    that organisation to these Terms.\nrestricted_uses:\n- summary: Anti-social forces excluded\n  text: It is not an Anti-Social Force as defined in Article 25.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Registration is complete, and a service contract on these Terms is formed between the User and the Company,\n    when the Company approves the application.\nminimum_age:\n  value: '18'\n  text: It is at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/fastmetal-ai/eligibility/fastmetal-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from fastmetal-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Cloud
---
