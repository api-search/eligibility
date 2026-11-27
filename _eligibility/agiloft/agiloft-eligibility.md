---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for use by businesses.
    type: business
  minimum_age:
    text: You must not use or access the Service if you are a minor (meaning an individual who is under the age of majority in the territory in which you are a resident).
    value: age of majority
  restricted_uses:
  - summary: No benchmarking or competing products
    text: Use the Service for benchmarking, or to compile information for a product or service or to create products or perform services which compete or interfere with those of Agiloft;
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
name: Agiloft
provenance_date: '2026-11-09'
provider_name: Agiloft
provider_slug: agiloft
slug: agiloft-eligibility
source_date: '2026-11-09'
source_filename: agiloft-eligibility.yml
source_heading: Eligibility
source_page: https://www.agiloft.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agiloft\naid: agiloft\nurl: https://www.agiloft.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for use by businesses.\nrestricted_uses:\n- summary: No benchmarking or competing products\n  text: Use the Service for benchmarking, or to compile information for a product or service or to create products\n    or perform services which compete or interfere with those of Agiloft;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n \
  \ text: You must not use or access the Service if you are a minor (meaning an individual who is under the age of\n    majority in the territory in which you are a resident).\n"
source_yaml_url: https://artifacts.apis.io/agiloft/eligibility/agiloft-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Agiloft's own page on 2026-11-09.
synthetic: false
tags:
- Contract Lifecycle Management
- Contract Management
- Legal
- Procurement
- Enterprise Software
- No-Code
- Workflow Automation
- Document Automation
- Webhook
- SCIM
- Company
---
