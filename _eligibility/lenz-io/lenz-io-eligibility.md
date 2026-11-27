---
api_specs:
- filename: lenz-io-account-api-openapi.yml
  format: yaml
  label: lenz-io Account API
  slug: lenz-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-account-api-openapi.yml
- filename: lenz-io-ask-api-openapi.yml
  format: yaml
  label: lenz-io Ask API
  slug: lenz-io-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-ask-api-openapi.yml
- filename: lenz-io-assess-api-openapi.yml
  format: yaml
  label: lenz-io Assess API
  slug: lenz-io-assess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-assess-api-openapi.yml
- filename: lenz-io-citecheck-api-openapi.yml
  format: yaml
  label: lenz-io Citecheck API
  slug: lenz-io-citecheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-citecheck-api-openapi.yml
- filename: lenz-io-discovery-api-openapi.yml
  format: yaml
  label: lenz-io Discovery API
  slug: lenz-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-discovery-api-openapi.yml
- filename: lenz-io-extract-api-openapi.yml
  format: yaml
  label: lenz-io Extract API
  slug: lenz-io-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-extract-api-openapi.yml
- filename: lenz-io-lenz-ai-fact-checking-api-api-openapi.yml
  format: yaml
  label: lenz-io Lenz — AI Fact Checking API
  slug: lenz-io-lenz-ai-fact-checking-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-lenz-ai-fact-checking-api-api-openapi.yml
- filename: lenz-io-library-api-openapi.yml
  format: yaml
  label: lenz-io Library API
  slug: lenz-io-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-library-api-openapi.yml
- filename: lenz-io-review-api-openapi.yml
  format: yaml
  label: lenz-io Review API
  slug: lenz-io-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-review-api-openapi.yml
- filename: lenz-io-verifications-api-openapi.yml
  format: yaml
  label: lenz-io Verifications API
  slug: lenz-io-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-verifications-api-openapi.yml
- filename: lenz-io-verify-api-openapi.yml
  format: yaml
  label: lenz-io Verify API
  slug: lenz-io-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lenz-io/openapi/lenz-io-verify-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  - text: If you use the service on behalf of a business, you confirm that you have authority to bind it, and “you” in these Terms includes that business.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated or personal data
    text: Do not submit personal data, payment card data, health records, or other regulated data that you are not authorised to share with third-party LLM processors.
  - summary: Unlawful purpose
    text: Use the service for any unlawful purpose or in violation of any applicable laws or regulations
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
name: lenz-io
provenance_date: '2026-11-09'
provider_name: lenz-io
provider_slug: lenz-io
slug: lenz-io-eligibility
source_date: '2026-11-09'
source_filename: lenz-io-eligibility.yml
source_heading: Eligibility
source_page: https://lenz.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: lenz-io\naid: lenz-io\nurl: https://lenz.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\n- type: business\n  text: If you use the service on behalf of a business, you confirm that you have authority to bind it, and “you”\n    in these Terms includes that business.\nrestricted_uses:\n- summary: Regulated or personal data\n  text: Do not submit personal data, payment card data, health records, or other regulated data that you are not\n    authorised to share with third-party LLM processors.\n\
  - summary: Unlawful purpose\n  text: Use the service for any unlawful purpose or in violation of any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/lenz-io/eligibility/lenz-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from lenz-io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Fact Checking
- Enterprise
- Audit
---
