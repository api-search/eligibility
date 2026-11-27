---
api_specs:
- filename: openmail-sh-attachments-api-openapi.yml
  format: yaml
  label: openmail-sh Attachments API
  slug: openmail-sh-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-attachments-api-openapi.yml
- filename: openmail-sh-domains-api-openapi.yml
  format: yaml
  label: openmail-sh Domains API
  slug: openmail-sh-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-domains-api-openapi.yml
- filename: openmail-sh-feedback-api-openapi.yml
  format: yaml
  label: openmail-sh Feedback API
  slug: openmail-sh-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-feedback-api-openapi.yml
- filename: openmail-sh-inboxes-api-openapi.yml
  format: yaml
  label: openmail-sh Inboxes API
  slug: openmail-sh-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-inboxes-api-openapi.yml
- filename: openmail-sh-limits-api-openapi.yml
  format: yaml
  label: openmail-sh Limits API
  slug: openmail-sh-limits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-limits-api-openapi.yml
- filename: openmail-sh-messages-api-openapi.yml
  format: yaml
  label: openmail-sh Messages API
  slug: openmail-sh-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-messages-api-openapi.yml
- filename: openmail-sh-owned-domains-api-openapi.yml
  format: yaml
  label: openmail-sh Owned Domains API
  slug: openmail-sh-owned-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-owned-domains-api-openapi.yml
- filename: openmail-sh-pods-api-openapi.yml
  format: yaml
  label: openmail-sh Pods API
  slug: openmail-sh-pods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-pods-api-openapi.yml
- filename: openmail-sh-policy-api-openapi.yml
  format: yaml
  label: openmail-sh Policy API
  slug: openmail-sh-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-policy-api-openapi.yml
- filename: openmail-sh-threads-api-openapi.yml
  format: yaml
  label: openmail-sh Threads API
  slug: openmail-sh-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-threads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited bulk messaging
    text: Spam, phishing, or unsolicited bulk messaging
  - summary: Content prohibited under AI Act
    text: Sending content whose generation or distribution is prohibited under the AI Act, including content covered by its Article 5 prohibitions
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
name: openmail-sh
provenance_date: '2026-11-10'
provider_name: openmail-sh
provider_slug: openmail-sh
slug: openmail-sh-eligibility
source_date: '2026-11-10'
source_filename: openmail-sh-eligibility.yml
source_heading: Eligibility
source_page: https://openmail.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: openmail-sh\naid: openmail-sh\nurl: https://openmail.sh/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\nrestricted_uses:\n- summary: Spam and unsolicited bulk messaging\n  text: Spam, phishing, or unsolicited bulk messaging\n- summary: Content prohibited under AI Act\n  text: Sending content whose generation or distribution is prohibited under the AI Act, including content covered\n    by its Article 5 prohibitions\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/openmail-sh/eligibility/openmail-sh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from openmail-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Artificial Intelligence
- Developers
---
