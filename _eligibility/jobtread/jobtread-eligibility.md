---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated by JobTread from its offices in the United States of America.
  entity_types:
  - text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be the Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive regulated personal data
    text: Customer agrees that it shall not use the Service to send or store personal information subject to special regulatory or contractual handling requirements
  - summary: No unlawful or infringing material
    text: to send or store infringing, obscene, threatening, or otherwise unlawful material, including material violative of third-party privacy rights
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
name: JobTread
provenance_date: '2026-11-09'
provider_name: JobTread
provider_slug: jobtread
slug: jobtread-eligibility
source_date: '2026-11-09'
source_filename: jobtread-eligibility.yml
source_heading: Eligibility
source_page: https://www.jobtread.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JobTread\naid: jobtread\nurl: https://www.jobtread.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated by JobTread from its offices in the United States of America.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of your organization, that organization is deemed to be\n    the Customer\nrestricted_uses:\n- summary: No sensitive regulated personal data\n  text: Customer agrees that it shall not use the Service to send or store personal information subject to special\n    regulatory or contractual\
  \ handling requirements\n- summary: No unlawful or infringing material\n  text: to send or store infringing, obscene, threatening, or otherwise unlawful material, including material violative\n    of third-party privacy rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobtread/eligibility/jobtread-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from JobTread's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Estimating
- Project Management
- Software-as-a-Service
- Finance
---
