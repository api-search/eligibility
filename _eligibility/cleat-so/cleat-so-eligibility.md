---
api_specs:
- filename: cleat-so-lines-api-openapi.yml
  format: yaml
  label: Cleat Lines API
  slug: cleat-so-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleat-so/openapi/cleat-so-lines-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Cleat gives you US mobile numbers (“lines”).
  entity_types:
  - text: You must be at least 18 and give accurate information. An account belongs to one person.
    type: individual
  minimum_age:
    text: You must be at least 18 and give accurate information.
    value: '18'
  restricted_uses:
  - summary: Fraud, impersonation, evasion
    text: commit fraud, steal or misuse anyone’s identity, or impersonate a person or business
  - summary: Financial and account evasion
    text: to take payments, run a marketplace or trading account, or move money in a name that isn’t yours
  - summary: Prohibited content categories
    text: for anything to do with drugs, weapons, sanctions evasion, money laundering, terrorism, child sexual abuse material, or trafficking of any kind
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To read the texts a line receives, you verify your identity with a government ID and a selfie, handled by our identity verification provider, Stripe or Didit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleat
provenance_date: '2026-11-09'
provider_name: Cleat
provider_slug: cleat-so
slug: cleat-so-eligibility
source_date: '2026-11-09'
source_filename: cleat-so-eligibility.yml
source_heading: Eligibility
source_page: https://cleat.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleat\naid: cleat-so\nurl: https://cleat.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Cleat gives you US mobile numbers (“lines”).\nentity_types:\n- type: individual\n  text: You must be at least 18 and give accurate information. An account belongs to one person.\nrestricted_uses:\n- summary: Fraud, impersonation, evasion\n  text: commit fraud, steal or misuse anyone’s identity, or impersonate a person or business\n- summary: Financial and account evasion\n  text: to take payments, run a marketplace or trading account, or move money in a name that isn’t yours\n-\
  \ summary: Prohibited content categories\n  text: for anything to do with drugs, weapons, sanctions evasion, money laundering, terrorism, child sexual abuse\n    material, or trafficking of any kind\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To read the texts a line receives, you verify your identity with a government ID and a selfie, handled by\n    our identity verification provider, Stripe or Didit.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and give accurate information.\n"
source_yaml_url: https://artifacts.apis.io/cleat-so/eligibility/cleat-so-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Cleat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- Phone Numbers
- Verification Codes
- Two-Factor Authentication
- Webhooks
- Telephony
---
