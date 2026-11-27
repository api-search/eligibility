---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in, organized under the laws of, or ordinarily resident in any jurisdiction subject to comprehensive sanctions or embargoes under applicable laws; no countries are named.
  entity_types:
  - text: where acting on behalf of an entity, is duly authorized to bind such entity
    type: business
  minimum_age:
    text: it is at least eighteen (18) years of age (or the age of majority in the applicable jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: Prohibited end-uses
    text: use the Services for any prohibited end-use, including but not limited to military, defense, nuclear, missile, chemical, or biological weapons-related activities, except as expressly authorized by applicable law and approved in writing by the Company;
  - summary: Restricted parties
    text: access or use the Services on behalf of, or for the benefit of, any Restricted Party;
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: The Company may, at its sole discretion and at any time, require the Customer to provide information, documentation, or certifications to verify identity, legal status, ownership, eligibility, and compliance with applicable laws and these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ironlane
provenance_date: '2026-11-09'
provider_name: Ironlane
provider_slug: ironlane
slug: ironlane-eligibility
source_date: '2026-11-09'
source_filename: ironlane-eligibility.yml
source_heading: Eligibility
source_page: https://ironlane.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ironlane\naid: ironlane\nurl: https://ironlane.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in, organized under the laws of, or ordinarily resident in any jurisdiction\n    subject to comprehensive sanctions or embargoes under applicable laws; no countries are named.\nentity_types:\n- type: business\n  text: where acting on behalf of an entity, is duly authorized to bind such entity\nrestricted_uses:\n- summary: Prohibited end-uses\n  text: use the Services for any prohibited end-use, including but not limited to military, defense,\
  \ nuclear, missile,\n    chemical, or biological weapons-related activities, except as expressly authorized by applicable law and approved\n    in writing by the Company;\n- summary: Restricted parties\n  text: access or use the Services on behalf of, or for the benefit of, any Restricted Party;\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: The Company may, at its sole discretion and at any time, require the Customer to provide information, documentation,\n    or certifications to verify identity, legal status, ownership, eligibility, and compliance with applicable laws\n    and these Terms.\nminimum_age:\n  value: '18'\n  text: it is at least eighteen (18) years of age (or the age of majority in the applicable jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/ironlane/eligibility/ironlane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ironlane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Inference
- Routing
- Platform
---
