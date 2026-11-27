---
api_specs:
- filename: agree-com-agreements-api-openapi.yml
  format: yaml
  label: Agree.com Agreements API
  slug: agree-com-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-agreements-api-openapi.yml
- filename: agree-com-contacts-api-openapi.yml
  format: yaml
  label: Agree.com Contacts API
  slug: agree-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-contacts-api-openapi.yml
- filename: agree-com-customers-api-openapi.yml
  format: yaml
  label: Agree.com Customers API
  slug: agree-com-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-customers-api-openapi.yml
- filename: agree-com-invoices-api-openapi.yml
  format: yaml
  label: Agree.com Invoices API
  slug: agree-com-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-invoices-api-openapi.yml
- filename: agree-com-reports-api-openapi.yml
  format: yaml
  label: Agree.com Reports API
  slug: agree-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-reports-api-openapi.yml
- filename: agree-com-webhooks-api-openapi.yml
  format: yaml
  label: Agree.com Webhooks API
  slug: agree-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-webhooks-api-openapi.yml
- filename: agree-com-subscriptions-api-openapi.yml
  format: yaml
  label: Agree.com Subscriptions API
  slug: agree-com-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agree-com/openapi/agree-com-subscriptions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for users who are at least 18 years old who reside in the United States. Persons under the age of 18 or who are not located in the United States are not permitted to use or register for the Services.
  entity_types:
  - text: If you are agreeing to these Legal Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old who reside in the United States.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data uses
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA violations
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Agree.com
provenance_date: '2026-11-09'
provider_name: Agree.com
provider_slug: agree-com
slug: agree-com-eligibility
source_date: '2026-11-09'
source_filename: agree-com-eligibility.yml
source_heading: Eligibility
source_page: https://agree.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agree.com\naid: agree-com\nurl: https://agree.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for users who are at least 18 years old who reside in the United States. Persons\n    under the age of 18 or who are not located in the United States are not permitted to use or register for the\n    Services.\nentity_types:\n- type: business\n  text: If you are agreeing to these Legal Terms on behalf of an organization or entity, you represent and warrant\n    that you are authorized to agree to these Terms on that organization or entity’s behalf\n\
  restricted_uses:\n- summary: Industry-regulated data uses\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA violations\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old who reside in the United States.\n"
source_yaml_url: https://artifacts.apis.io/agree-com/eligibility/agree-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Agree.com's own page on 2026-11-09.
synthetic: false
tags:
- Agreements
- E-Signature
- Contract Management
- Invoicing
- Billing
- Payments
- Accounts Receivable
- Fintech
- Financial Services
- Webhook
- MCP
- Agent-Native
---
