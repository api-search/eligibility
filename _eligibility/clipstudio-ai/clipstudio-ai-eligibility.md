---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: Illegal or unauthorized purpose
    text: you will not use the Services for any illegal or unauthorized purpose
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
name: Clip Studio AI
provenance_date: '2026-11-09'
provider_name: Clip Studio AI
provider_slug: clipstudio-ai
slug: clipstudio-ai-eligibility
source_date: '2026-11-09'
source_filename: clipstudio-ai-eligibility.yml
source_heading: Eligibility
source_page: https://clipstudio.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clip Studio AI\naid: clipstudio-ai\nurl: https://clipstudio.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-regulated data\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: Illegal\
  \ or unauthorized purpose\n  text: you will not use the Services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/clipstudio-ai/eligibility/clipstudio-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Clip Studio AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Video Generation
- Generative AI
- Image Generation
- Short-Form Video
- Video Ads
- MCP
---
