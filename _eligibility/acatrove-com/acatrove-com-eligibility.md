---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: No PHI or regulated data without agreement
    text: Unless we have signed a written agreement expressly permitting it, do not submit protected health information, identifiable human-subject data, education records protected by FERPA, classified information, or export-controlled technical data.
  - summary: Not for high-risk use
    text: The Service is not designed for emergency, life-safety, or other high-risk use cases where errors could cause death, personal injury, or significant property damage.
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
name: AcaTrove
provenance_date: '2026-11-09'
provider_name: AcaTrove
provider_slug: acatrove-com
slug: acatrove-com-eligibility
source_date: '2026-11-09'
source_filename: acatrove-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.acatrove.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AcaTrove\naid: acatrove-com\nurl: https://www.acatrove.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: No PHI or regulated data without agreement\n  text: Unless we have signed a written agreement expressly permitting it, do not\
  \ submit protected health information,\n    identifiable human-subject data, education records protected by FERPA, classified information, or export-controlled\n    technical data.\n- summary: Not for high-risk use\n  text: The Service is not designed for emergency, life-safety, or other high-risk use cases where errors could\n    cause death, personal injury, or significant property damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/acatrove-com/eligibility/acatrove-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AcaTrove's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Research
- Citations
- Knowledge Management
- Productivity
---
