---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Content Sweep serves internationally supported jurisdictions; there is no United States residency or billing-country requirement. Availability shown during paid-service country setup and checkout is controlling
  entity_types:
  - text: You represent that you are at least 18 years old, have the legal capacity to enter into these Terms, and will use the Service only for yourself as an independent adult creator
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Non-copyright claims
    text: You may not use the Service for counter-notices, litigation, subpoenas, settlements, ownership disputes, emergency or safety matters, impersonation, deepfakes, defamation, privacy, right-of-publicity, or other non-copyright claims.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: Content Sweep does not collect raw government ID under this baseline.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: contentsweep-ai
provenance_date: '2026-11-09'
provider_name: contentsweep-ai
provider_slug: contentsweep-ai
slug: contentsweep-ai-eligibility
source_date: '2026-11-09'
source_filename: contentsweep-ai-eligibility.yml
source_heading: Eligibility
source_page: https://contentsweep.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: contentsweep-ai\naid: contentsweep-ai\nurl: https://contentsweep.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Content Sweep serves internationally supported jurisdictions; there is no United States residency or billing-country\n    requirement. Availability shown during paid-service country setup and checkout is controlling\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old, have the legal capacity to enter into these Terms, and\n    will use the Service only for yourself as an independent adult creator\nrestricted_uses:\n\
  - summary: Non-copyright claims\n  text: You may not use the Service for counter-notices, litigation, subpoenas, settlements, ownership disputes,\n    emergency or safety matters, impersonation, deepfakes, defamation, privacy, right-of-publicity, or other non-copyright\n    claims.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: Content Sweep does not collect raw government ID under this baseline.\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/contentsweep-ai/eligibility/contentsweep-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from contentsweep-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Adult-Content-Protection
- DMCA
- Content Monitoring
- Privacy
---
