---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THIS SITE IS INTENDED FOR A UNITED STATES AUDIENCE, SOME PRODUCTS MAY NOT BE AVAILABLE OUTSIDE THE UNITED STATES.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws for product use
    text: You are responsible for compliance with all laws, rules, regulations, ordinances, codes and guidelines in connection with the use of any CorneaGen products.
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
name: CorneaGen
provenance_date: '2026-11-09'
provider_name: CorneaGen
provider_slug: corneagen
slug: corneagen-eligibility
source_date: '2026-11-09'
source_filename: corneagen-eligibility.yml
source_heading: Eligibility
source_page: https://corneagen.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CorneaGen\naid: corneagen\nurl: https://corneagen.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THIS SITE IS INTENDED FOR A UNITED STATES AUDIENCE, SOME PRODUCTS MAY NOT BE AVAILABLE OUTSIDE THE UNITED\n    STATES.\nentity_types: []\nrestricted_uses:\n- summary: Compliance with laws for product use\n  text: You are responsible for compliance with all laws, rules, regulations, ordinances, codes and guidelines in\n    connection with the use of any CorneaGen products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corneagen/eligibility/corneagen-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from CorneaGen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Ophthalmology
- Surgery
- Tissue
---
