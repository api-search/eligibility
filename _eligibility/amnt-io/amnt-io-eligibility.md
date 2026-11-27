---
api_specs:
- filename: amnt-io-account-api-openapi.yml
  format: yaml
  label: AMNT Account API
  slug: amnt-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-account-api-openapi.yml
- filename: amnt-io-agents-api-openapi.yml
  format: yaml
  label: AMNT Agents API
  slug: amnt-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-agents-api-openapi.yml
- filename: amnt-io-runs-api-openapi.yml
  format: yaml
  label: AMNT Runs API
  slug: amnt-io-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-runs-api-openapi.yml
- filename: amnt-io-svg-api-openapi.yml
  format: yaml
  label: AMNT SVG API
  slug: amnt-io-svg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-svg-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer in the UK or the EU, you normally have 14 days to cancel a purchase of digital content or services.
  entity_types:
  - text: You must be at least 18 years old and able to enter into a legally binding contract to use the Services.
    type: individual
  - text: If you use them on behalf of a company or other organisation, you confirm that you are authorised to accept these Terms for it, and "you" includes that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a legally binding contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful content and conduct
    text: upload or share content that is unlawful, harmful, threatening, abusive, harassing, defamatory, hateful, obscene or sexually exploitative, including any content involving minors
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse to open an account, or ask you to verify information, where we reasonably need to.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AMNT
provenance_date: '2026-11-09'
provider_name: AMNT
provider_slug: amnt-io
slug: amnt-io-eligibility
source_date: '2026-11-09'
source_filename: amnt-io-eligibility.yml
source_heading: Eligibility
source_page: https://amnt.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMNT\naid: amnt-io\nurl: https://amnt.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer in the UK or the EU, you normally have 14 days to cancel a purchase of digital content\n    or services.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a legally binding contract to use the Services.\n- type: business\n  text: If you use them on behalf of a company or other organisation, you confirm that you are authorised to accept\n    these Terms for it, and \"you\" includes that organisation.\nrestricted_uses:\n\
  - summary: Unlawful content and conduct\n  text: upload or share content that is unlawful, harmful, threatening, abusive, harassing, defamatory, hateful,\n    obscene or sexually exploitative, including any content involving minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse to open an account, or ask you to verify information, where we reasonably need to.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a legally binding contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/amnt-io/eligibility/amnt-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AMNT's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Tools
- Creators
- Developers
- Agents
---
