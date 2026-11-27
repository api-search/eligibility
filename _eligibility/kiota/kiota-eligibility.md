---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you create a Microsoft Learn Profile account on behalf of an entity, such as your business or employer, you represent that you have the legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harmful or unlawful content and conduct
    text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Kiota
provenance_date: '2026-11-09'
provider_name: Kiota
provider_slug: kiota
slug: kiota-eligibility
source_date: '2026-11-09'
source_filename: kiota-eligibility.yml
source_heading: Eligibility
source_page: https://learn.microsoft.com/en-us/legal/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kiota\naid: kiota\nurl: https://learn.microsoft.com/en-us/legal/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you create a Microsoft Learn Profile account on behalf of an entity, such as your business or employer,\n    you represent that you have the legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Harmful or unlawful content and conduct\n  text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful\n    or prohibited by these terms,\
  \ conditions, and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kiota/eligibility/kiota-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kiota's own page on 2026-11-09.
synthetic: false
tags:
- Code Generation
- Microsoft
- OpenAPI
- SDK
- Developer Tools
- API Client
- Open Source
- CLI
- JSON Schema
- SDK Generation
---
