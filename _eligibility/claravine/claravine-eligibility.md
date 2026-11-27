---
api_specs:
- filename: claravine-openapi-generated.yml
  format: yaml
  label: Claravine API
  slug: claravine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claravine/openapi/_ae-authored/claravine-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Claravine and its licensors make no representation that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS AND CONDITIONS
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export embargo and sanctioned parties
    text: the site shall not be used, and none of the underlying information, software, or technology may be transferred or otherwise exported or re-exported to countries as to which the United States, Switzerland and/or the European Union maintains an embargo
  - summary: No nuclear, chemical, biological or missile use
    text: None of the Content, nor any information acquired through the use of the Service, is or will be used for nuclear activities, chemical or biological weapons, or missile projects
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
name: Claravine
provenance_date: '2026-11-09'
provider_name: Claravine
provider_slug: claravine
slug: claravine-eligibility
source_date: '2026-11-09'
source_filename: claravine-eligibility.yml
source_heading: Eligibility
source_page: https://www.claravine.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claravine\naid: claravine\nurl: https://www.claravine.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Claravine and its licensors make no representation that the Service is appropriate or available for use\n    in other locations.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS AND CONDITIONS\nrestricted_uses:\n- summary: Export embargo and sanctioned parties\n  text: the site shall not be used, and none\
  \ of the underlying information, software, or technology may be transferred\n    or otherwise exported or re-exported to countries as to which the United States, Switzerland and/or the European\n    Union maintains an embargo\n- summary: No nuclear, chemical, biological or missile use\n  text: None of the Content, nor any information acquired through the use of the Service, is or will be used for\n    nuclear activities, chemical or biological weapons, or missile projects\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/claravine/eligibility/claravine-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Claravine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Standards
- Marketing
- Software-as-a-Service
---
