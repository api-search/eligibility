---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law are permitted to access the Platform or be a Member.
    type: individual
  - text: If you use the Platform on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law are permitted to access the Platform or be a Member.
    value: '18'
  restricted_uses:
  - summary: Care Providers must be licensed and insured
    text: By registering as a Care Provider, Care Providers represent and warrant that they, and the employees, agents, contractors, and subcontractors who may perform work for them, are properly and fully qualified and experienced, and licensed and insured as required by applicable laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Otter may, for transparency or fraud prevention or detection purposes (directly or through third parties) ask a Member to provide a form of government identification (for example, a driver’s license or passport), date of birth, and other information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Otter
provenance_date: '2026-11-10'
provider_name: Otter
provider_slug: withotter-com
slug: withotter-com-eligibility
source_date: '2026-11-10'
source_filename: withotter-com-eligibility.yml
source_heading: Eligibility
source_page: https://withotter.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Otter\naid: withotter-com\nurl: https://withotter.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law\n    are permitted to access the Platform or be a Member.\n- type: business\n  text: If you use the Platform on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: Care Providers must be licensed and insured\n  text: By registering as a\
  \ Care Provider, Care Providers represent and warrant that they, and the employees, agents,\n    contractors, and subcontractors who may perform work for them, are properly and fully qualified and experienced,\n    and licensed and insured as required by applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Otter may, for transparency or fraud prevention or detection purposes (directly or through third parties)\n    ask a Member to provide a form of government identification (for example, a driver’s license or passport), date\n    of birth, and other information\nminimum_age:\n  value: '18'\n  text: Only individuals who are at least 18 years old and can form legally binding contracts under applicable law\n    are permitted to access the Platform or be a Member.\n"
source_yaml_url: https://artifacts.apis.io/withotter-com/eligibility/withotter-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Otter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Workflows
- Integration
---
