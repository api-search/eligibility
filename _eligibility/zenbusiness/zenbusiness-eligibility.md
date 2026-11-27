---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Service is intended only for use in the United States. Use of or access to the Services from a U.S. Government sanctioned or prohibited country is in violation of this Agreement and is strictly prohibited.
  entity_types:
  - text: You must be 18 years of age or older to use or register for Services.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to use or register for Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited industries for Payment Services
    text: 'You may not use the Payment Services for the following businesses or business activities: (a) any illegal activity or goods;'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: ZenBusiness will review the information you submit while signing up for the Services to verify and validate your identity. You authorize ZenBusiness to request identity verifying information about you, including a consumer report and criminal history background check.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ZenBusiness
provenance_date: '2026-11-10'
provider_name: ZenBusiness
provider_slug: zenbusiness
slug: zenbusiness-eligibility
source_date: '2026-11-10'
source_filename: zenbusiness-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenbusiness.com/support-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenBusiness\naid: zenbusiness\nurl: https://www.zenbusiness.com/support-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Service is intended only for use in the United States. Use of or access to the Services from a U.S.\n    Government sanctioned or prohibited country is in violation of this Agreement and is strictly prohibited.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use or register for Services.\nrestricted_uses:\n- summary: Prohibited industries for Payment Services\n  text: 'You may not use the Payment\
  \ Services for the following businesses or business activities: (a) any illegal\n    activity or goods;'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: ZenBusiness will review the information you submit while signing up for the Services to verify and validate\n    your identity. You authorize ZenBusiness to request identity verifying information about you, including a consumer\n    report and criminal history background check.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use or register for Services.\n"
source_yaml_url: https://artifacts.apis.io/zenbusiness/eligibility/zenbusiness-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ZenBusiness's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Business Formation
- LLC Formation
- Registered Agent
- Compliance
- Small Business
- Legal Tech
---
