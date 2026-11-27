---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered to entrepreneurs acting in their commercial or independent professional capacity within § 14 of the German Civil Code (BGB)
    type: business
  - text: and legal persons under public law.
    type: government
  minimum_age:
    text: Account users must have the capacity and authority needed for their role and must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Unlawful surveillance
    text: infringe rights, conduct unlawful surveillance or otherwise use the Services unlawfully
  - summary: Export-restricted recipients or uses
    text: You must not supply or use the SDK or Model Artifacts for prohibited recipients, destinations or end uses, or without required authorizations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By accepting, you confirm that you act in that capacity and have authority to bind the customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ai-coustics
provenance_date: '2026-11-09'
provider_name: ai-coustics
provider_slug: ai-coustics
slug: ai-coustics-eligibility
source_date: '2026-11-09'
source_filename: ai-coustics-eligibility.yml
source_heading: Eligibility
source_page: https://ai-coustics.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ai-coustics\naid: ai-coustics\nurl: https://ai-coustics.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered to entrepreneurs acting in their commercial or independent professional capacity\n    within § 14 of the German Civil Code (BGB)\n- type: government\n  text: and legal persons under public law.\nrestricted_uses:\n- summary: Unlawful surveillance\n  text: infringe rights, conduct unlawful surveillance or otherwise use the Services unlawfully\n- summary: Export-restricted recipients or uses\n\
  \  text: You must not supply or use the SDK or Model Artifacts for prohibited recipients, destinations or end uses,\n    or without required authorizations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By accepting, you confirm that you act in that capacity and have authority to bind the customer.\nminimum_age:\n  value: '16'\n  text: Account users must have the capacity and authority needed for their role and must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/ai-coustics/eligibility/ai-coustics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ai-coustics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Audio
- Speech Enhancement
- Voice AI
- Speech Recognition
- SDK
- Real-Time
- Machine Learning
---
