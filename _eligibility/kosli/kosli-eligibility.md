---
api_specs:
- filename: kosli-openapi-generated.yml
  format: yaml
  label: Kosli API
  slug: kosli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kosli/openapi/_ae-authored/kosli-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the legal capacity and you agree to comply with these Terms of Use
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated uses
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA
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
name: Kosli
provenance_date: '2026-11-09'
provider_name: Kosli
provider_slug: kosli
slug: kosli-eligibility
source_date: '2026-11-09'
source_filename: kosli-eligibility.yml
source_heading: Eligibility
source_page: https://www.kosli.com/privacy-policy/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kosli\naid: kosli\nurl: https://www.kosli.com/privacy-policy/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you have the legal capacity and you agree to comply with these Terms of Use\nrestricted_uses:\n- summary: Industry-specific regulated uses\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may\
  \ not use this Site.\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/kosli/eligibility/kosli-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kosli's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Compliance
- DevOps
---
