---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE USING THE BLUE J PLATFORM ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.
    type: business
  minimum_age:
    text: you have reached the age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Direct competitors barred from access
    text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE OUR DIRECT COMPETITOR, OR TO MONITOR THEIR FUNCTIONALITY, PERFORMANCE, AVAILABILITY OR ANY OTHER COMPETITIVE OR BENCHMARKING-RELATED PURPOSES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We retain the right, at our sole discretion, to deny you use of the Blue J Platform, at any time and for any reason
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blue J
provenance_date: '2026-11-09'
provider_name: Blue J
provider_slug: blue-j
slug: blue-j-eligibility
source_date: '2026-11-09'
source_filename: blue-j-eligibility.yml
source_heading: Eligibility
source_page: https://www.bluej.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue J\naid: blue-j\nurl: https://www.bluej.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE BLUE J PLATFORM ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND\n    WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.\nrestricted_uses:\n- summary: Direct competitors barred from access\n  text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE OUR DIRECT COMPETITOR, OR TO MONITOR THEIR FUNCTIONALITY, PERFORMANCE,\n    AVAILABILITY OR ANY OTHER COMPETITIVE\
  \ OR BENCHMARKING-RELATED PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We retain the right, at our sole discretion, to deny you use of the Blue J Platform, at any time and for\n    any reason\nminimum_age:\n  value: age of majority\n  text: you have reached the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/blue-j/eligibility/blue-j-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Blue J's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tax
- Legal
- Research
- Compliance
- Software-as-a-Service
- Professional Services
---
