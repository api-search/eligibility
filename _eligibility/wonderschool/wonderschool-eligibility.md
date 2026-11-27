---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law are permitted to access the Services.
    type: individual
  - text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law are permitted to access the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent conduct
    text: Violate any law or regulation
  - summary: Harmful or deceptive conduct
    text: Engage in any harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable conduct
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Wonderschool may, for transparency or fraud prevention or detection purposes (directly or through third parties) ask a Member to provide a form of government identification (for example, a driver’s license or passport), date of birth, and other information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wonderschool
provenance_date: '2026-11-10'
provider_name: Wonderschool
provider_slug: wonderschool
slug: wonderschool-eligibility
source_date: '2026-11-10'
source_filename: wonderschool-eligibility.yml
source_heading: Eligibility
source_page: https://www.wonderschool.com/corp/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wonderschool\naid: wonderschool\nurl: https://www.wonderschool.com/corp/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law\n    are permitted to access the Services.\n- type: business\n  text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: Unlawful or fraudulent conduct\n  text: Violate any law or\
  \ regulation\n- summary: Harmful or deceptive conduct\n  text: Engage in any harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable conduct\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Wonderschool may, for transparency or fraud prevention or detection purposes (directly or through third\n    parties) ask a Member to provide a form of government identification (for example, a driver’s license or passport),\n    date of birth, and other information\nminimum_age:\n  value: '18'\n  text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law\n    are permitted to access the Services.\n"
source_yaml_url: https://artifacts.apis.io/wonderschool/eligibility/wonderschool-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wonderschool's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Childcare
- Early Childhood Education
- Daycare
- Preschool
- Education
- Government
- Employer Benefits
---
