---
api_specs:
- filename: youlearn-openapi-generated.yml
  format: yaml
  label: YouLearn API
  slug: youlearn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youlearn/openapi/_ae-authored/youlearn-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age. All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    value: '13'
  restricted_uses:
  - summary: Not for HIPAA/FISMA-regulated interactions
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: No GLBA-violating use
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
name: YouLearn
provenance_date: '2026-11-10'
provider_name: YouLearn
provider_slug: youlearn
slug: youlearn-eligibility
source_date: '2026-11-10'
source_filename: youlearn-eligibility.yml
source_heading: Eligibility
source_page: https://www.youlearn.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YouLearn\naid: youlearn\nurl: https://www.youlearn.ai/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not intended for distribution to or use by any person or entity in any jurisdiction or country\n    where such distribution or use would be contrary to law or regulation.\nentity_types: []\nrestricted_uses:\n- summary: Not for HIPAA/FISMA-regulated interactions\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA),\
  \ etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: No GLBA-violating use\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age. All users who are minors in the jurisdiction\n    in which they reside (generally under the age of 18) must have the permission of, and be directly supervised\n    by, their parent or guardian to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/youlearn/eligibility/youlearn-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from YouLearn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Artificial Intelligence
- Tutoring
- Learning
---
