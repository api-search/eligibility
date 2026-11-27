---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Services. If you are under 18, you may only use the Services with the involvement and consent of a parent or legal guardian who agrees to be bound by these Terms.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose, unauthorised access, impersonation
    text: Use the Services for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features of the Services, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AFD Institute
provenance_date: '2026-11-09'
provider_name: AFD Institute
provider_slug: afdinstitute-com
slug: afdinstitute-com-eligibility
source_date: '2026-11-09'
source_filename: afdinstitute-com-eligibility.yml
source_heading: Eligibility
source_page: https://afdinstitute.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AFD Institute\naid: afdinstitute-com\nurl: https://afdinstitute.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services. If you are under 18, you may only use the Services\n    with the involvement and consent of a parent or legal guardian who agrees to be bound by these Terms.\nrestricted_uses:\n- summary: Unlawful purpose, unauthorised access, impersonation\n  text: Use the Services for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: To access certain features of the Services, you must create an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/afdinstitute-com/eligibility/afdinstitute-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AFD Institute's own page on 2026-11-09.
synthetic: false
tags:
- Standards
- Education
- Certification
- Artificial Intelligence
- Belgium
---
