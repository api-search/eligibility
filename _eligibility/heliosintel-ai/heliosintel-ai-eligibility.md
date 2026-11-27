---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE AGREEING TO THESE TERMS AS AN INDIVIDUAL, “CUSTOMER” REFERS TO YOU INDIVIDUALLY.
    type: individual
  - text: IF YOU ARE AGREEING TO THESE TERMS AS A REPRESENTATIVE OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND THAT ENTITY
    type: business
  - text: All software provided to the U.S. Government is provided with the commercial license rights and restrictions described in this Agreement.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data uploads
    text: not to upload in any way any data regarding an individual’s financial or economic identity, sexual orientation, religious beliefs, medical or physical identity
  - summary: Nuclear, chemical, biological or missile use
    text: None of the Customer Data, nor any information acquired through the use of Proxi AI, is or will be used for nuclear activities, chemical or biological weapons, or missile projects.
  - summary: Embargoed countries and designated nationals
    text: Proxi AI shall not be used, and none of the underlying information, software, or technology may be transferred or otherwise exported or re-exported to countries as to which the United States maintains an embargo
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
name: Helios
provenance_date: '2026-11-09'
provider_name: Helios
provider_slug: heliosintel-ai
slug: heliosintel-ai-eligibility
source_date: '2026-11-09'
source_filename: heliosintel-ai-eligibility.yml
source_heading: Eligibility
source_page: https://heliosintel.ai/legal-terms/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Helios\naid: heliosintel-ai\nurl: https://heliosintel.ai/legal-terms/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IF YOU ARE AGREEING TO THESE TERMS AS AN INDIVIDUAL, “CUSTOMER” REFERS TO YOU INDIVIDUALLY.\n- type: business\n  text: IF YOU ARE AGREEING TO THESE TERMS AS A REPRESENTATIVE OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY\n    TO BIND THAT ENTITY\n- type: government\n  text: All software provided to the U.S. Government is provided with the commercial license rights and restrictions\n\
  \    described in this Agreement.\nrestricted_uses:\n- summary: Sensitive data uploads\n  text: not to upload in any way any data regarding an individual’s financial or economic identity, sexual orientation,\n    religious beliefs, medical or physical identity\n- summary: Nuclear, chemical, biological or missile use\n  text: None of the Customer Data, nor any information acquired through the use of Proxi AI, is or will be used\n    for nuclear activities, chemical or biological weapons, or missile projects.\n- summary: Embargoed countries and designated nationals\n  text: Proxi AI shall not be used, and none of the underlying information, software, or technology may be transferred\n    or otherwise exported or re-exported to countries as to which the United States maintains an embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heliosintel-ai/eligibility/heliosintel-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Helios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sovereign
- Government
- Policy
---
