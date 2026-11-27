---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual who accepts these Terms on behalf of an organization represents that they are authorized to do so, and the organization shall be bound accordingly.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive-use restriction
    text: You agree that you will not, directly or indirectly, use any Confidential Information obtained through access to the Service to design, develop, build, launch, market,
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the API requires registration and may require payment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Court Rules
provenance_date: '2026-11-09'
provider_name: Court Rules
provider_slug: courtrules
slug: courtrules-eligibility
source_date: '2026-11-09'
source_filename: courtrules-eligibility.yml
source_heading: Eligibility
source_page: https://www.courtrules.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Court Rules\naid: courtrules\nurl: https://www.courtrules.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any individual who accepts these Terms on behalf of an organization represents that they are authorized\n    to do so, and the organization shall be bound accordingly.\nrestricted_uses:\n- summary: Competitive-use restriction\n  text: You agree that you will not, directly or indirectly, use any Confidential Information obtained through access\n    to the Service to design, develop, build, launch, market,\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the API requires registration and may require payment.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/courtrules/eligibility/courtrules-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Court Rules's own page on 2026-11-09.
synthetic: false
tags:
- Legal Data
- CourtRules
- Compliance
- US Law
---
