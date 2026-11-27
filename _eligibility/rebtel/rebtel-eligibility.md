---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers from the USA will purchase the service from Rebtel Canada Inc, a company incorporated under the laws of Canada
  entity_types:
  - text: The Services are for your individual use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale or commercial use of Services
    text: You shall not resell or commercialize the Services to any third party.
  - summary: No emergency calls
    text: The Services do not and are not intended to support or carry emergency calls to any type of hospitals, law enforcement agencies, medical care unit or any type of emergency services of any kind
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to require any level of or additional identity verification to access any of the Partner Services, in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: rebtel
provenance_date: '2026-11-10'
provider_name: rebtel
provider_slug: rebtel
slug: rebtel-eligibility
source_date: '2026-11-10'
source_filename: rebtel-eligibility.yml
source_heading: Eligibility
source_page: https://www.rebtel.com/en/legal-information/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rebtel\naid: rebtel\nurl: https://www.rebtel.com/en/legal-information/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customers from the USA will purchase the service from Rebtel Canada Inc, a company incorporated under the\n    laws of Canada\nentity_types:\n- type: individual\n  text: The Services are for your individual use only.\nrestricted_uses:\n- summary: No resale or commercial use of Services\n  text: You shall not resell or commercialize the Services to any third party.\n- summary: No emergency calls\n  text: The Services do not and are\
  \ not intended to support or carry emergency calls to any type of hospitals, law\n    enforcement agencies, medical care unit or any type of emergency services of any kind\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to require any level of or additional identity verification to access any of the Partner\n    Services, in our sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rebtel/eligibility/rebtel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from rebtel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- VoIP
- International Calling
- Mobile Top-Up
- Remittances
- Consumer
- Messaging
- Sweden
---
