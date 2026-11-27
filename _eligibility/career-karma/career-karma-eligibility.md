---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data use
    text: so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: Gramm-Leach-Bliley Act
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Career Karma
provenance_date: '2026-11-09'
provider_name: Career Karma
provider_slug: career-karma
slug: career-karma-eligibility
source_date: '2026-11-09'
source_filename: career-karma-eligibility.yml
source_heading: Eligibility
source_page: https://careerkarma.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Career Karma\naid: career-karma\nurl: https://careerkarma.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-regulated data use\n  text: so if your\
  \ interactions would be subjected to such laws, you may not use this Site.\n- summary: Gramm-Leach-Bliley Act\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/career-karma/eligibility/career-karma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Career Karma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- Career Training
- Bootcamps
- EdTech
- Program Matching
---
