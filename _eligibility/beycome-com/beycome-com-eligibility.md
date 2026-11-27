---
api_specs:
- filename: beycome-com-openapi-generated.yml
  format: yaml
  label: Beycome API
  slug: beycome-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beycome-com/openapi/_ae-authored/beycome-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Outside the U.S.: you must follow your local rules on online conduct, Content and User Data.'
  entity_types:
  - text: Each Party promises the other that (a) it is a legal entity in good standing; (b) it is authorized to agree to these Terms
    type: business
  minimum_age:
    text: You must be 18 or older to use Beycome.
    value: '18'
  restricted_uses:
  - summary: Processing data beyond Terms
    text: Process User Data or Personal Information beyond what these Terms allow.
  - summary: Illegal use of other Users' data
    text: you may not use other Users' data you get through the Service for anything illegal.
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
name: Beycome
provenance_date: '2026-11-09'
provider_name: Beycome
provider_slug: beycome-com
slug: beycome-com-eligibility
source_date: '2026-11-09'
source_filename: beycome-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.beycome.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beycome\naid: beycome-com\nurl: https://www.beycome.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Outside the U.S.: you must follow your local rules on online conduct, Content and User Data.'\nentity_types:\n- type: business\n  text: Each Party promises the other that (a) it is a legal entity in good standing; (b) it is authorized to agree\n    to these Terms\nrestricted_uses:\n- summary: Processing data beyond Terms\n  text: Process User Data or Personal Information beyond what these Terms allow.\n- summary: Illegal use of other Users' data\n  text: you\
  \ may not use other Users' data you get through the Service for anything illegal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to use Beycome.\n"
source_yaml_url: https://artifacts.apis.io/beycome-com/eligibility/beycome-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Beycome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Fintech
- Home Selling
- MLS
- FlatFee
---
