---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country subject to sanctions.
  entity_types:
  - text: Have authority to bind your business (if registering on behalf of an entity).
    type: business
  minimum_age:
    text: Be at least 18 years old or the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unsolicited marketing
    text: Send unlawful, unsolicited, or non-consensual marketing communications.
  - summary: Sanctioned parties
    text: You are not on any sanctions list maintained by Singapore, the United States, United Kingdom, or European Union.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Any Zaapi customer may connect a WhatsApp Business account to the Services, subject to these Terms and to Meta's onboarding requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zaapi
provenance_date: '2026-11-10'
provider_name: Zaapi
provider_slug: zaapi
slug: zaapi-eligibility
source_date: '2026-11-10'
source_filename: zaapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.zaapi.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zaapi\naid: zaapi\nurl: https://www.zaapi.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country subject to sanctions.\nentity_types:\n- type: business\n  text: Have authority to bind your business (if registering on behalf of an entity).\nrestricted_uses:\n- summary: Unlawful or unsolicited marketing\n  text: Send unlawful, unsolicited, or non-consensual marketing communications.\n- summary: Sanctioned parties\n  text: You are not on any sanctions list maintained by Singapore, the United States, United Kingdom, or European\n    Union.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Any Zaapi customer may connect a WhatsApp Business account to the Services, subject to these Terms and to\n    Meta's onboarding requirements.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/zaapi/eligibility/zaapi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Zaapi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- Conversational AI
- Chat Commerce
- Customer Communication
- E-Commerce
- Omnichannel Messaging
- Southeast Asia
- Small Business
---
