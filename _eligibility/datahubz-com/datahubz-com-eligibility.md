---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Services, you must be at least 18 years old and have the capacity to form a binding contract.
    type: individual
  - text: If you are using our Services on behalf of an organization, you are agreeing to these Terms on behalf of that organization and warrant that you have the authority to do so.
    type: business
  minimum_age:
    text: To use the Services, you must be at least 18 years old and have the capacity to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Attest misuse
    text: you may not use Attest to sign or record documents on behalf of another person without their authorization, to impersonate anyone, to create records intended to deceive, or to store or share unlawful content.
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
name: datahubz-com
provenance_date: '2026-11-09'
provider_name: datahubz-com
provider_slug: datahubz-com
slug: datahubz-com-eligibility
source_date: '2026-11-09'
source_filename: datahubz-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.datahubz.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: datahubz-com\naid: datahubz-com\nurl: https://www.datahubz.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Services, you must be at least 18 years old and have the capacity to form a binding contract.\n- type: business\n  text: If you are using our Services on behalf of an organization, you are agreeing to these Terms on behalf of\n    that organization and warrant that you have the authority to do so.\nrestricted_uses:\n- summary: Attest misuse\n  text: you may not use Attest to sign or record documents\
  \ on behalf of another person without their authorization,\n    to impersonate anyone, to create records intended to deceive, or to store or share unlawful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Services, you must be at least 18 years old and have the capacity to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/datahubz-com/eligibility/datahubz-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from datahubz-com's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Security
- Software-as-a-Service
- Automation
- DataHubz
---
