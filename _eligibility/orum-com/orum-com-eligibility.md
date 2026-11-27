---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: (i) a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)
  entity_types:
  - text: You may use the Services only if you have the legal power and capacity to form a contract with Orum.
    type: individual
  - text: If you open a user account on behalf of, or are otherwise using the Services on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: Any use or access to the Services by anyone under eighteen (18) years of age is strictly prohibited and in violation of these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harassing communications
    text: access or engage in any use of the Service to communicate any message or material that is deemed harassing, threatening, indecent, obscene, slanderous, or otherwise unlawful
  - summary: Unsolicited calling/messaging
    text: you shall not transmit or cause to be transmitted communications to recipients who have opted-out, withdrawn consent or for whom you do not otherwise have all necessary consents and permissions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orum
provenance_date: '2026-11-10'
provider_name: Orum
provider_slug: orum-com
slug: orum-com-eligibility
source_date: '2026-11-10'
source_filename: orum-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.orum.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orum\naid: orum-com\nurl: https://www.orum.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: (i) a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan and Syria)\nentity_types:\n- type: individual\n  text: You may use the Services only if you have the legal power and capacity to form a contract with Orum.\n- type: business\n  text: If you open a user account on behalf of, or are otherwise using the Services on behalf of an organization,\n    you are agreeing to these Terms for that organization\nrestricted_uses:\n\
  - summary: Unlawful or harassing communications\n  text: access or engage in any use of the Service to communicate any message or material that is deemed harassing,\n    threatening, indecent, obscene, slanderous, or otherwise unlawful\n- summary: Unsolicited calling/messaging\n  text: you shall not transmit or cause to be transmitted communications to recipients who have opted-out, withdrawn\n    consent or for whom you do not otherwise have all necessary consents and permissions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under eighteen (18) years of age is strictly prohibited and\n    in violation of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/orum-com/eligibility/orum-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Orum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- Sales Engagement
- Sales Dialer
- Outbound Sales
- Sales Coaching
- Conversation Intelligence
- Telephony
- Revenue Operations
- Webhook
- Parallel Dialing
- Sales Automation
---
