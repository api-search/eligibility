---
api_specs:
- filename: saperly-api-token-registry-api-openapi.yml
  format: yaml
  label: Saperly API Token Registry API
  slug: saperly-api-token-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-api-token-registry-api-openapi.yml
- filename: saperly-assistant-api-openapi.yml
  format: yaml
  label: Saperly Assistant API
  slug: saperly-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-assistant-api-openapi.yml
- filename: saperly-connections-api-openapi.yml
  format: yaml
  label: Saperly Connections API
  slug: saperly-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-connections-api-openapi.yml
- filename: saperly-consent-api-openapi.yml
  format: yaml
  label: Saperly Consent API
  slug: saperly-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-consent-api-openapi.yml
- filename: saperly-customvoices-api-openapi.yml
  format: yaml
  label: Saperly Custom Voices API
  slug: saperly-customvoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-customvoices-api-openapi.yml
- filename: saperly-health-api-openapi.yml
  format: yaml
  label: Saperly Health API
  slug: saperly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-health-api-openapi.yml
- filename: saperly-keys-api-openapi.yml
  format: yaml
  label: Saperly Keys API
  slug: saperly-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-keys-api-openapi.yml
- filename: saperly-languages-api-openapi.yml
  format: yaml
  label: Saperly Languages API
  slug: saperly-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-languages-api-openapi.yml
- filename: saperly-messaging-api-openapi.yml
  format: yaml
  label: Saperly Messaging API
  slug: saperly-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-messaging-api-openapi.yml
- filename: saperly-numbers-api-openapi.yml
  format: yaml
  label: Saperly Numbers API
  slug: saperly-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-numbers-api-openapi.yml
- filename: saperly-pricing-api-openapi.yml
  format: yaml
  label: Saperly Pricing API
  slug: saperly-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-pricing-api-openapi.yml
- filename: saperly-usage-api-openapi.yml
  format: yaml
  label: Saperly Usage API
  slug: saperly-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-usage-api-openapi.yml
- filename: saperly-voice-api-openapi.yml
  format: yaml
  label: Saperly Voice API
  slug: saperly-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-voice-api-openapi.yml
- filename: saperly-voices-api-openapi.yml
  format: yaml
  label: Saperly Voices API
  slug: saperly-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-voices-api-openapi.yml
- filename: saperly-workspace-api-openapi.yml
  format: yaml
  label: Saperly Workspace API
  slug: saperly-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-workspace-api-openapi.yml
- filename: saperly-workspace-invitations-api-openapi.yml
  format: yaml
  label: Saperly Workspace Invitations API
  slug: saperly-workspace-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-workspace-invitations-api-openapi.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You may not use Saperly if you are located in, ordinarily resident in, or organised under the laws of any jurisdiction subject to comprehensive U.S. sanctions (currently Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)
  entity_types:
  - text: You must be at least 18 years old to use Saperly.
    type: individual
  - text: If you are accepting on behalf of a company, partnership, or other legal entity, you represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old to use Saperly.
    value: '18'
  restricted_uses:
  - summary: Unreviewed high-stakes automated decisions
    text: High-stakes automated decisions in medicine, law, finance, credit, housing, employment, or government benefits without qualified human review of the output before dissemination.
  - summary: Debt collection, crypto, gambling and similar campaigns
    text: Loans, credit repair, debt collection, cryptocurrency, gambling, multi-level marketing, or investment advice campaigns.
  - summary: Voice cloning without authorisation
    text: Voice cloning of any real person without notarised written authorisation from that person.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You are responsible for the accuracy of know-your-customer information you provide to Saperly during registration and at any time thereafter.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Saperly
provenance_date: '2026-11-10'
provider_name: Saperly
provider_slug: saperly
slug: saperly-eligibility
source_date: '2026-11-10'
source_filename: saperly-eligibility.yml
source_heading: Eligibility
source_page: https://saperly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saperly\naid: saperly\nurl: https://saperly.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You may not use Saperly if you are located in, ordinarily resident in, or organised under the laws of any\n    jurisdiction subject to comprehensive U.S. sanctions (currently Cuba, Iran, North Korea, Syria, and the Crimea,\n    Donetsk, and Luhansk regions of Ukraine)\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Saperly.\n- type: business\n  text: If you are accepting on behalf of a company, partnership, or other\
  \ legal entity, you represent that you\n    have the authority to bind that entity\nrestricted_uses:\n- summary: Unreviewed high-stakes automated decisions\n  text: High-stakes automated decisions in medicine, law, finance, credit, housing, employment, or government benefits\n    without qualified human review of the output before dissemination.\n- summary: Debt collection, crypto, gambling and similar campaigns\n  text: Loans, credit repair, debt collection, cryptocurrency, gambling, multi-level marketing, or investment advice\n    campaigns.\n- summary: Voice cloning without authorisation\n  text: Voice cloning of any real person without notarised written authorisation from that person.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You are responsible for the accuracy of know-your-customer information you provide to Saperly during registration\n    and at any time thereafter.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use\
  \ Saperly.\n"
source_yaml_url: https://artifacts.apis.io/saperly/eligibility/saperly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Saperly's own page on 2026-11-10.
synthetic: false
tags:
- Telephony
- Voice
- SMS
- Phone Numbers
- AI Agents
- Consent
- Compliance
- MCP
- Messaging
- Communications
---
