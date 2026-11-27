---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The service currently places calls to United States and Canada numbers only.
  entity_types:
  - text: You must be 18 or older and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be 18 or older and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Calls requiring prior express written consent under TCPA
    text: or for any call requiring prior express written consent under the TCPA or equivalent state law
  - summary: Emergency services contact
    text: or to contact emergency services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification is by SMS code; your number is your identity and your caller ID.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DialMCP
provenance_date: '2026-11-09'
provider_name: DialMCP
provider_slug: dialmcp-com
slug: dialmcp-com-eligibility
source_date: '2026-11-09'
source_filename: dialmcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://dialmcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DialMCP\naid: dialmcp-com\nurl: https://dialmcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The service currently places calls to United States and Canada numbers only.\nentity_types:\n- type: individual\n  text: You must be 18 or older and able to form a binding contract.\nrestricted_uses:\n- summary: Calls requiring prior express written consent under TCPA\n  text: or for any call requiring prior express written consent under the TCPA or equivalent state law\n- summary: Emergency services contact\n  text: or to contact emergency services\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification is by SMS code; your number is your identity and your caller ID.\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/dialmcp-com/eligibility/dialmcp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from DialMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Phone Calls
- Voice AI
- Telephony
---
