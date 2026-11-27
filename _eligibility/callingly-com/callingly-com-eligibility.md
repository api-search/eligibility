---
api_specs:
- filename: callingly-com-openapi-generated.yml
  format: yaml
  label: Callingly API
  slug: callingly-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callingly-com/openapi/_ae-authored/callingly-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Provide true, complete, and current identifying information, including legal business name, business registration or tax identification number, registered address, website, and an authorized contact.
    type: business
  minimum_age:
    source: https://callingly.com/terms-of-service
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or deceptive calling
    text: Originate illegal robocalls, or any call or message that is fraudulent, deceptive, or intended to mislead the recipient about who is calling or why.
  - summary: Unvetted third-party traffic
    text: do not permit an unvetted third party to originate traffic through your account.
  - source: https://callingly.com/terms-of-service
    summary: Unlawful or harmful use
    text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law or regulation.'
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
name: Callingly
provenance_date: '2026-11-09'
provider_name: Callingly
provider_slug: callingly-com
slug: callingly-com-eligibility
source_date: '2026-11-09'
source_filename: callingly-com-eligibility.yml
source_heading: Eligibility
source_page: https://callingly.com/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Callingly\naid: callingly-com\nurl: https://callingly.com/acceptable-use-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://callingly.com/acceptable-use-policy\n  - https://callingly.com/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Provide true, complete, and current identifying information, including legal business name, business registration\n    or tax identification number, registered address, website, and an authorized contact.\nrestricted_uses:\n- summary: Unlawful or deceptive calling\n  text: Originate illegal robocalls, or\
  \ any call or message that is fraudulent, deceptive, or intended to mislead\n    the recipient about who is calling or why.\n- summary: Unvetted third-party traffic\n  text: do not permit an unvetted third party to originate traffic through your account.\n- summary: Unlawful or harmful use\n  text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law\n    or regulation.'\n  source: https://callingly.com/terms-of-service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n  source: https://callingly.com/terms-of-service\n"
source_yaml_url: https://artifacts.apis.io/callingly-com/eligibility/callingly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Callingly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales
- Lead Response
- Speed To Lead
- Telephony
- SMS
- AI Voice Agents
- MCP
---
