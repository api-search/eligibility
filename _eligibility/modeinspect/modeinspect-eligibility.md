---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. Modeinspect makes no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF A COMPANY OR ANOTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Model provider usage policies
    text: you agree not to use Modeinspect in any way that is prohibited by these model providers
  - summary: Sanctioned persons and countries
    text: 'you must and hereby represent that you are not: (a) a citizen or resident of a geographic area in which access to or use of the Website or Services is prohibited by applicable law'
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
name: Modeinspect
provenance_date: '2026-11-10'
provider_name: Modeinspect
provider_slug: modeinspect
slug: modeinspect-eligibility
source_date: '2026-11-10'
source_filename: modeinspect-eligibility.yml
source_heading: Eligibility
source_page: https://modeinspect.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modeinspect\naid: modeinspect\nurl: https://modeinspect.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. Modeinspect makes no representation\n    that the Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF A COMPANY OR ANOTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Model provider usage policies\n \
  \ text: you agree not to use Modeinspect in any way that is prohibited by these model providers\n- summary: Sanctioned persons and countries\n  text: 'you must and hereby represent that you are not: (a) a citizen or resident of a geographic area in which\n    access to or use of the Website or Services is prohibited by applicable law'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/modeinspect/eligibility/modeinspect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Modeinspect's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- Design
- Developer Tools
- Design Engineering
- Artificial Intelligence
- Design to Code
- UI Design
- Prototyping
---
