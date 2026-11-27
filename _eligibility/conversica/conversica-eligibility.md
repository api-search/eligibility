---
api_specs:
- filename: conversica-conversica-integrations-api-api-openapi.yml
  format: yaml
  label: Conversica Integrations API
  slug: conversica-conversica-integrations-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversica/openapi/conversica-conversica-integrations-api-api-openapi.yml
- filename: conversica-leads-api-openapi.yml
  format: yaml
  label: Conversica Leads API
  slug: conversica-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversica/openapi/conversica-leads-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual, company or legal entity that you represent
    type: other
  - source: https://www.conversica.com/legal-info/terms
    text: the organization placing an order for the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use limited to authorized customer benefit
    text: Your Application only may be used for your benefit or the benefit of a mutual customer so long as you or the mutual customer has a current authorized customer account with us.
  - source: https://www.conversica.com/legal-info/terms
    summary: No Sensitive Personal Data
    text: (c) not use any Service to collect, manage, or process Sensitive Personal Data
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: you agree to not use nor enable an Application prior to our approval
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Conversica
provenance_date: '2026-11-09'
provider_name: Conversica
provider_slug: conversica
slug: conversica-eligibility
source_date: '2026-11-09'
source_filename: conversica-eligibility.yml
source_heading: Eligibility
source_page: https://www.conversica.com/legal-info/conversica-api-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conversica\naid: conversica\nurl: https://www.conversica.com/legal-info/conversica-api-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.conversica.com/legal-info/conversica-api-terms-of-service\n  - https://www.conversica.com/legal-info/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the individual, company or legal entity that you represent\n- type: business\n  text: the organization placing an order for the Services\n  source: https://www.conversica.com/legal-info/terms\nrestricted_uses:\n- summary: Use limited to authorized customer\
  \ benefit\n  text: Your Application only may be used for your benefit or the benefit of a mutual customer so long as you or\n    the mutual customer has a current authorized customer account with us.\n- summary: No Sensitive Personal Data\n  text: (c) not use any Service to collect, manage, or process Sensitive Personal Data\n  source: https://www.conversica.com/legal-info/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: you agree to not use nor enable an Application prior to our approval\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conversica/eligibility/conversica-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Conversica's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversational AI
- AI Agents
- Sales
- Marketing
- Lead Management
- CRM
- Marketing Automation
- Customer Engagement
- Messaging
- SMS
- Email
- Chat
- Automotive
- Higher Education
- Webhook
---
