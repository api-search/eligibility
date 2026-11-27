---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To access or use the Service, you must be 13 years of age or older. If you are 13 or older but under the age of 18, you may only use the Service with the permission of your parent or legal guardian.
    type: individual
  - text: If you are using the Service on behalf of a company or other entity, you represent that you are authorized to legally bind that entity to these Terms of Use.
    type: business
  minimum_age:
    text: To access or use the Service, you must be 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: No restricted information uploads
    text: in the use of the Services, You are not allowed to use, upload and submit Restricted Information
  - summary: Export restrictions
    text: no portion of the Inkling Service may be exported or re-exported (a) into any U.S.-embargoed countries or (b) to anyone on the U.S. Treasury Department’s Specially Designated Nationals List
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
name: Inkling
provenance_date: '2026-11-09'
provider_name: Inkling
provider_slug: inkling
slug: inkling-eligibility
source_date: '2026-11-09'
source_filename: inkling-eligibility.yml
source_heading: Eligibility
source_page: https://www.inkling.com/inkling-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inkling\naid: inkling\nurl: https://www.inkling.com/inkling-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To access or use the Service, you must be 13 years of age or older. If you are 13 or older but under the\n    age of 18, you may only use the Service with the permission of your parent or legal guardian.\n- type: business\n  text: If you are using the Service on behalf of a company or other entity, you represent that you are authorized\n    to legally bind that entity to these Terms of Use.\nrestricted_uses:\n\
  - summary: No restricted information uploads\n  text: in the use of the Services, You are not allowed to use, upload and submit Restricted Information\n- summary: Export restrictions\n  text: no portion of the Inkling Service may be exported or re-exported (a) into any U.S.-embargoed countries or\n    (b) to anyone on the U.S. Treasury Department’s Specially Designated Nationals List\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To access or use the Service, you must be 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/inkling/eligibility/inkling-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Inkling's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Learning
- Training
- Employee Enablement
- Content Authoring
- LMS
- Frontline Workers
---
