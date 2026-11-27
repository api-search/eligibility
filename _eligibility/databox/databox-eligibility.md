---
api_specs:
- filename: databox-openapi-generated.yml
  format: yaml
  label: Databox API
  slug: databox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/databox/openapi/_ae-authored/databox-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No spam or unsolicited messages
    text: (1) send spam or otherwise duplicative or unsolicited messages in violation of applicable laws
  - summary: No unlawful or harmful material
    text: (2) send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortuous material
  - summary: No malicious code
    text: (3) send or store material containing software viruses, worms, Trojan horses or other harmful computer code
  - summary: No unauthorised access
    text: (5) attempt to gain unauthorised access to the Service or its related systems or networks.
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
name: Databox
provenance_date: '2026-11-09'
provider_name: Databox
provider_slug: databox
slug: databox-eligibility
source_date: '2026-11-09'
source_filename: databox-eligibility.yml
source_heading: Eligibility
source_page: https://databox.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Databox\naid: databox\nurl: https://databox.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No spam or unsolicited messages\n  text: (1) send spam or otherwise duplicative or unsolicited messages in violation of applicable laws\n- summary: No unlawful or harmful material\n  text: (2) send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortuous material\n- summary: No malicious code\n  text: (3) send or store material containing software viruses, worms, Trojan horses or other harmful\
  \ computer code\n- summary: No unauthorised access\n  text: (5) attempt to gain unauthorised access to the Service or its related systems or networks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/databox/eligibility/databox-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 4 quoted statements, read from Databox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Artificial Intelligence
- Data Integration
- Business Intelligence
---
