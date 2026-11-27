---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control our Website from our offices within the United States. We make no representation that the Content on our Website is appropriate, legal or available for use in other locations.
  minimum_age:
    text: You represent that you (a) are of a legal age sufficient to agree to these TOU in accordance with applicable law
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You may not use or export the Content in violation of United States export laws and regulations.
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
name: Turnitin
provenance_date: '2026-11-10'
provider_name: Turnitin
provider_slug: turnitin
slug: turnitin-eligibility
source_date: '2026-11-10'
source_filename: turnitin-eligibility.yml
source_heading: Eligibility
source_page: https://www.turnitin.com/terms-of-use-website/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Turnitin\naid: turnitin\nurl: https://www.turnitin.com/terms-of-use-website/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control our Website from our offices within the United States. We make no representation that the Content\n    on our Website is appropriate, legal or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not use or export the Content in violation of United States export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: You represent that you (a) are of a legal age sufficient to agree to these TOU in accordance with applicable\n    law\n"
source_yaml_url: https://artifacts.apis.io/turnitin/eligibility/turnitin-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Turnitin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Academic Integrity
- Plagiarism Detection
- Similarity
- AI Detection
- Assessment
- Research Integrity
- Publishing
- LTI
- Grading
---
