---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The membership is allowed only for individuals of full age (18 years or older) and with full legal capacity.
    type: individual
  minimum_age:
    text: The membership is allowed only for individuals of full age (18 years or older)
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: the services are offered only for users use, and not for the use or benefit of any third party.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Habyt may either reject or accept the registration request submitted by the user.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Habyt
provenance_date: '2026-11-09'
provider_name: Habyt
provider_slug: habyt
slug: habyt-eligibility
source_date: '2026-11-09'
source_filename: habyt-eligibility.yml
source_heading: Eligibility
source_page: https://habyt.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Habyt\naid: habyt\nurl: https://habyt.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The membership is allowed only for individuals of full age (18 years or older) and with full legal capacity.\nrestricted_uses:\n- summary: Personal use only\n  text: the services are offered only for users use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Habyt may either reject or accept the registration request submitted by the user.\nminimum_age:\n\
  \  value: '18'\n  text: The membership is allowed only for individuals of full age (18 years or older)\n"
source_yaml_url: https://artifacts.apis.io/habyt/eligibility/habyt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Habyt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Real Estate
- Housing
- Co-Living
- Flexible Living
- Hospitality
- Property
---
