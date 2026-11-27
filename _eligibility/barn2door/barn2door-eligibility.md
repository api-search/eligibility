---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accepting, you represent that you have the capacity to enter into this Agreement and are 18 years or older.
    type: individual
  - text: If you are acting on behalf of a company or organization, you represent that you have the authority to bind such entity(ies).
    type: business
  - text: As a wholesale Buyer you represent that your organization is a lawfully registered and active organization entitled to wholesale pricing under applicable law.
    type: business
  minimum_age:
    text: You must be 18 years or older to use our Services.
    value: '18'
  restricted_uses:
  - summary: Competitors barred from using Services
    text: Any party that competes with Barn2Door, whether now or contemplating to do so in the future, is expressly prohibited from accessing and/or using our Services and the Site
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: As a wholesale Buyer, you agree and accept that you may be required to provide proof of lawful entity organization, existence (e.g. EIN), good standing and authorization to act on behalf of a wholesale buying entity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Barn2Door
provenance_date: '2026-11-09'
provider_name: Barn2Door
provider_slug: barn2door
slug: barn2door-eligibility
source_date: '2026-11-09'
source_filename: barn2door-eligibility.yml
source_heading: Eligibility
source_page: https://www.barn2door.com/legal#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barn2Door\naid: barn2door\nurl: https://www.barn2door.com/legal#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accepting, you represent that you have the capacity to enter into this Agreement and are 18 years or\n    older.\n- type: business\n  text: If you are acting on behalf of a company or organization, you represent that you have the authority to bind\n    such entity(ies).\n- type: business\n  text: As a wholesale Buyer you represent that your organization is a lawfully registered and active organization\n\
  \    entitled to wholesale pricing under applicable law.\nrestricted_uses:\n- summary: Competitors barred from using Services\n  text: Any party that competes with Barn2Door, whether now or contemplating to do so in the future, is expressly\n    prohibited from accessing and/or using our Services and the Site\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: As a wholesale Buyer, you agree and accept that you may be required to provide proof of lawful entity organization,\n    existence (e.g. EIN), good standing and authorization to act on behalf of a wholesale buying entity.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/barn2door/eligibility/barn2door-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Barn2Door's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Food
- E-Commerce
- Farm Management
- Local Food
- Payments
- Logistics
- Software-as-a-Service
---
