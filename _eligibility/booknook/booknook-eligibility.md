---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are designed for users in the United States. Users temporarily accessing the Services from other locations do so at their own risk and must comply with local laws.
  entity_types:
  - text: You must be (i) at least 18 years of age (or the applicable age of majority in your province, territory, or country) or an emancipated minor, or (ii) using the Services under the authorization of School Personnel or a parent/guardian as permitted by law.
    type: individual
  minimum_age:
    text: You must be (i) at least 18 years of age (or the applicable age of majority in your province, territory, or country) or an emancipated minor, or (ii) using the Services under the authorization of School Personnel or a parent/guardian as permitted by law.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not use, export, or re-export the Services except as authorized by United States law and the laws of the jurisdiction(s) in which the Services were obtained or used.
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
name: BookNook
provenance_date: '2026-11-09'
provider_name: BookNook
provider_slug: booknook
slug: booknook-eligibility
source_date: '2026-11-09'
source_filename: booknook-eligibility.yml
source_heading: Eligibility
source_page: https://www.booknook.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BookNook\naid: booknook\nurl: https://www.booknook.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are designed for users in the United States. Users temporarily accessing the Services from\n    other locations do so at their own risk and must comply with local laws.\nentity_types:\n- type: individual\n  text: You must be (i) at least 18 years of age (or the applicable age of majority in your province, territory,\n    or country) or an emancipated minor, or (ii) using the Services under the authorization of School Personnel\n    or a parent/guardian\
  \ as permitted by law.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You may not use, export, or re-export the Services except as authorized by United States law and the laws\n    of the jurisdiction(s) in which the Services were obtained or used.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be (i) at least 18 years of age (or the applicable age of majority in your province, territory,\n    or country) or an emancipated minor, or (ii) using the Services under the authorization of School Personnel\n    or a parent/guardian as permitted by law.\n"
source_yaml_url: https://artifacts.apis.io/booknook/eligibility/booknook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BookNook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Tutoring
- K-12
- Learning Platform
- Reading
- Mathematics
- Student Data
- Rostering
---
