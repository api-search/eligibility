---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for the Platform and/or Services on behalf of a company or organization, the term "you" is also meant to refer to that company, where it makes sense from the context.
    type: business
  minimum_age:
    text: you are at least 18 years old and have the ability to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries and unlawful use
    text: use in countries subject to sanctions under applicable law
  - summary: Children, finance or health data
    text: you will not provide us with any sensitive or other categories of data that are subject to additional protections under law, such as data regarding children, finance, or health.
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
name: Native Security
provenance_date: '2026-11-10'
provider_name: Native Security
provider_slug: native-security
slug: native-security-eligibility
source_date: '2026-11-10'
source_filename: native-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.native.security/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Native Security\naid: native-security\nurl: https://www.native.security/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for the Platform and/or Services on behalf of a company or organization, the term\n    \"you\" is also meant to refer to that company, where it makes sense from the context.\nrestricted_uses:\n- summary: Sanctioned countries and unlawful use\n  text: use in countries subject to sanctions under applicable law\n- summary: Children, finance or health data\n  text: you will not provide\
  \ us with any sensitive or other categories of data that are subject to additional protections\n    under law, such as data regarding children, finance, or health.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old and have the ability to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/native-security/eligibility/native-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Native Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cloud Security
- Cloud
- Compliance
- Governance
- Multi-Cloud
- AI Security
---
