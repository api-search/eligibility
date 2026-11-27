---
api_specs:
- filename: signal-accounts-api-openapi.yml
  format: yaml
  label: Signal Accounts API
  slug: signal-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-accounts-api-openapi.yml
- filename: signal-attachments-api-openapi.yml
  format: yaml
  label: Signal Attachments API
  slug: signal-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-attachments-api-openapi.yml
- filename: signal-certificates-api-openapi.yml
  format: yaml
  label: Signal Certificates API
  slug: signal-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-certificates-api-openapi.yml
- filename: signal-devices-api-openapi.yml
  format: yaml
  label: Signal Devices API
  slug: signal-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-devices-api-openapi.yml
- filename: signal-keys-api-openapi.yml
  format: yaml
  label: Signal Keys API
  slug: signal-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-keys-api-openapi.yml
- filename: signal-messages-api-openapi.yml
  format: yaml
  label: Signal Messages API
  slug: signal-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-messages-api-openapi.yml
- filename: signal-profiles-api-openapi.yml
  format: yaml
  label: Signal Profiles API
  slug: signal-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-profiles-api-openapi.yml
- filename: signal-registration-api-openapi.yml
  format: yaml
  label: Signal Registration API
  slug: signal-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-registration-api-openapi.yml
- filename: signal-stickers-api-openapi.yml
  format: yaml
  label: Signal Stickers API
  slug: signal-stickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-stickers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services are not intended for distribution to or use in any country where such distribution or use would violate local law or would subject us to any regulations in another country. We reserve the right to limit our Services in any country.
  entity_types:
  - text: You must be at least 13 years old to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use our Services. The minimum age to use our Services without parental approval may be higher in your home country.
    value: '13'
  restricted_uses:
  - summary: No emergency services access
    text: Our Services do not provide access to emergency service providers like the police, fire department, hospitals, or other public safety organizations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an account you must register for our Services using your phone number. You agree to receive text messages and phone calls (from us or our third-party providers) with verification codes to register for our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Signal
provenance_date: '2026-11-10'
provider_name: Signal
provider_slug: signal
slug: signal-eligibility
source_date: '2026-11-10'
source_filename: signal-eligibility.yml
source_heading: Eligibility
source_page: https://signal.org/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signal\naid: signal\nurl: https://signal.org/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services are not intended for distribution to or use in any country where such distribution or use would\n    violate local law or would subject us to any regulations in another country. We reserve the right to limit our\n    Services in any country.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Services.\nrestricted_uses:\n- summary: No emergency services access\n  text: Our Services do not provide access to emergency service providers\
  \ like the police, fire department, hospitals,\n    or other public safety organizations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an account you must register for our Services using your phone number. You agree to receive text\n    messages and phone calls (from us or our third-party providers) with verification codes to register for our\n    Services.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Services. The minimum age to use our Services without parental\n    approval may be higher in your home country.\n"
source_yaml_url: https://artifacts.apis.io/signal/eligibility/signal-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Signal's own page on 2026-11-10.
synthetic: false
tags:
- Encryption
- Messaging
- Security
- Cryptography
- Open Source
- Privacy
- Real-Time
---
