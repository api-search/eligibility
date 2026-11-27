---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a company or other organization, you confirm that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign-up to the Service may be open to everyone or may require an invitation, depending on current availability.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bilg
provenance_date: '2026-11-09'
provider_name: Bilg
provider_slug: bilgai-com
slug: bilgai-com-eligibility
source_date: '2026-11-09'
source_filename: bilgai-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.bilgai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bilg\naid: bilgai-com\nurl: https://app.bilgai.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a company or other organization, you confirm that you have authority\n    to bind that organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign-up to the Service may be open to everyone or may require an invitation, depending on current availability.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or\
  \ the age of legal majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bilgai-com/eligibility/bilgai-com-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Bilg's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Collaboration
- Knowledge Base
- Productivity
- Team Workspace
---
