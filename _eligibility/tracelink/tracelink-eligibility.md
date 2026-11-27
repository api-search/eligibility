---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” means the individual person accessing or using the TraceLink APIs on his or her own behalf
    type: individual
  - text: if the API or Documentation are accessed or used on behalf of an organization, corporation or other legal entity, “you” means such legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-violating use
    text: use the TraceLink APIs in any manner or for any purpose that violates any law or regulation, promotes illegal activities, violates third party rights or terms of service
  - summary: Spamming or unlawful marketing
    text: use the TraceLink APIs to engage in spamming or other advertising or marketing activities that violate any applicable laws, regulations or generally-accepted advertising industry guidelines;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate identification, contact, and other information required as part of the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TraceLink
provenance_date: '2026-11-10'
provider_name: TraceLink
provider_slug: tracelink
slug: tracelink-eligibility
source_date: '2026-11-10'
source_filename: tracelink-eligibility.yml
source_heading: Eligibility
source_page: https://www.tracelink.com/legal-and-trust/api-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TraceLink\naid: tracelink\nurl: https://www.tracelink.com/legal-and-trust/api-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” means the individual person accessing or using the TraceLink APIs on his or her own behalf\n- type: business\n  text: if the API or Documentation are accessed or used on behalf of an organization, corporation or other legal\n    entity, “you” means such legal entity.\nrestricted_uses:\n- summary: Unlawful or rights-violating use\n  text: use the TraceLink APIs in any manner or for any purpose\
  \ that violates any law or regulation, promotes illegal\n    activities, violates third party rights or terms of service\n- summary: Spamming or unlawful marketing\n  text: use the TraceLink APIs to engage in spamming or other advertising or marketing activities that violate any\n    applicable laws, regulations or generally-accepted advertising industry guidelines;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate identification, contact, and other information required as part of the registration\n    process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tracelink/eligibility/tracelink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from TraceLink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supply Chain
- Pharmaceuticals
- Life Sciences
- Serialization
- Track and Trace
- Compliance
- Healthcare
- EPCIS
- Logistics
- B2B Integration
---
