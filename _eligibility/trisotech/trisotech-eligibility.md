---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” or “Your” in this agreement means the individual, company, organization or other legal entity accepting this agreement.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS AND CONDITIONS
    type: business
  minimum_age:
    text: All users must be 13 years or older to access and use the Services.
    value: '13'
  restricted_uses:
  - summary: No illegal or obscene uploads
    text: You agree not to upload, post, email or transmit otherwise any material that is illegal, pornographic, abusive, or obscene.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a name, valid email address and other information necessary to register with the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trisotech
provenance_date: '2026-11-10'
provider_name: Trisotech
provider_slug: trisotech
slug: trisotech-eligibility
source_date: '2026-11-10'
source_filename: trisotech-eligibility.yml
source_heading: Eligibility
source_page: https://www.trisotech.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trisotech\naid: trisotech\nurl: https://www.trisotech.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” or “Your” in this agreement means the individual, company, organization or other legal entity accepting\n    this agreement.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS AND CONDITIONS\nrestricted_uses:\n- summary: No illegal or obscene uploads\n\
  \  text: You agree not to upload, post, email or transmit otherwise any material that is illegal, pornographic, abusive,\n    or obscene.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a name, valid email address and other information necessary to register with the Services.\nminimum_age:\n  value: '13'\n  text: All users must be 13 years or older to access and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/trisotech/eligibility/trisotech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Trisotech's own page on 2026-11-10.
synthetic: false
tags:
- Business Process Management
- Decision Management
- Workflow Automation
- Low-Code
- BPMN
- DMN
- CMMN
- Healthcare
- FHIR
- Clinical Decision Support
- Standards
- AI Agents
- MCP
- Enterprise Architecture
---
