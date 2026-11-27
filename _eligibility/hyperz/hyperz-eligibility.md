---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: HYPERTURE is a business service.
    type: business
  minimum_age:
    text: By registering, you confirm that you are at least 18 years old and authorized to bind the organization you represent.
    value: '18'
  restricted_uses:
  - summary: No uploads without consent or of minors
    text: Upload photos without the person's consent or upload anyone under 18.
  - summary: No impersonation, fraud or deception
    text: Create images intended to impersonate, defraud, harass or deceive.
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
name: HYPERZ AI
provenance_date: '2026-11-09'
provider_name: HYPERZ AI
provider_slug: hyperz
slug: hyperz-eligibility
source_date: '2026-11-09'
source_filename: hyperz-eligibility.yml
source_heading: Eligibility
source_page: https://www.hyperture.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HYPERZ AI\naid: hyperz\nurl: https://www.hyperture.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: HYPERTURE is a business service.\nrestricted_uses:\n- summary: No uploads without consent or of minors\n  text: Upload photos without the person's consent or upload anyone under 18.\n- summary: No impersonation, fraud or deception\n  text: Create images intended to impersonate, defraud, harass or deceive.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: By registering, you confirm that you are at least 18 years old and authorized to bind the organization you\n    represent.\n"
source_yaml_url: https://artifacts.apis.io/hyperz/eligibility/hyperz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HYPERZ AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Photography
- Headshots
- Image Generation
- Creative Tools
---
