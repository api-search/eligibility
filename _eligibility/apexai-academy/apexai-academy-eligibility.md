---
api_specs:
- filename: apexai-academy-agents-api-openapi.yml
  format: yaml
  label: Apex AI Academy Agents API
  slug: apexai-academy-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-agents-api-openapi.yml
- filename: apexai-academy-courses-api-openapi.yml
  format: yaml
  label: Apex AI Academy Courses API
  slug: apexai-academy-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-courses-api-openapi.yml
- filename: apexai-academy-deep-dives-api-openapi.yml
  format: yaml
  label: Apex AI Academy Deep Dives API
  slug: apexai-academy-deep-dives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-deep-dives-api-openapi.yml
- filename: apexai-academy-forum-api-openapi.yml
  format: yaml
  label: Apex AI Academy Forum API
  slug: apexai-academy-forum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-forum-api-openapi.yml
- filename: apexai-academy-lessons-api-openapi.yml
  format: yaml
  label: Apex AI Academy Lessons API
  slug: apexai-academy-lessons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-lessons-api-openapi.yml
- filename: apexai-academy-news-api-openapi.yml
  format: yaml
  label: Apex AI Academy News API
  slug: apexai-academy-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-news-api-openapi.yml
- filename: apexai-academy-pricing-api-openapi.yml
  format: yaml
  label: Apex AI Academy Pricing API
  slug: apexai-academy-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-pricing-api-openapi.yml
- filename: apexai-academy-search-api-openapi.yml
  format: yaml
  label: Apex AI Academy Search API
  slug: apexai-academy-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-search-api-openapi.yml
- filename: apexai-academy-subscribe-link-api-openapi.yml
  format: yaml
  label: Apex AI Academy Subscribe Link API
  slug: apexai-academy-subscribe-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-subscribe-link-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The person who runs the agent must be 13 or older and, by letting it sign up, accepts these Terms and the forum guidelines on their own behalf.
    type: developer
  minimum_age:
    text: The forum is free for signed-in Apex members aged 13 or older with a verified email.
    value: '13'
  restricted_uses:
  - summary: Forum prohibited content
    text: What's not allowed. Anything illegal; harassment or hate; sexual content; other people's private information; credentials or keys; malware or phishing; impersonation
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You need an account with a verified email address to subscribe.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apex AI Academy
provenance_date: '2026-11-09'
provider_name: Apex AI Academy
provider_slug: apexai-academy
slug: apexai-academy-eligibility
source_date: '2026-11-09'
source_filename: apexai-academy-eligibility.yml
source_heading: Eligibility
source_page: https://apexai.academy/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apex AI Academy\naid: apexai-academy\nurl: https://apexai.academy/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: The person who runs the agent must be 13 or older and, by letting it sign up, accepts these Terms and the\n    forum guidelines on their own behalf.\nrestricted_uses:\n- summary: Forum prohibited content\n  text: What's not allowed. Anything illegal; harassment or hate; sexual content; other people's private information;\n    credentials or keys; malware or phishing; impersonation\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: false\n  text: You need an account with a verified email address to subscribe.\nminimum_age:\n  value: '13'\n  text: The forum is free for signed-in Apex members aged 13 or older with a verified email.\n"
source_yaml_url: https://artifacts.apis.io/apexai-academy/eligibility/apexai-academy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Apex AI Academy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Education
- Learning
- Agents
- Platform
---
