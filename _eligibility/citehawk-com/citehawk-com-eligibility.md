---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind that organisation to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or rights-infringing submissions
    text: submit domains, prompts, or content you do not have the right to submit, or that infringe or violate any third party's rights
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
name: CiteHawk
provenance_date: '2026-11-09'
provider_name: CiteHawk
provider_slug: citehawk-com
slug: citehawk-com-eligibility
source_date: '2026-11-09'
source_filename: citehawk-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.citehawk.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CiteHawk\naid: citehawk-com\nurl: https://www.citehawk.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind that organisation\n    to these Terms\nrestricted_uses:\n- summary: Unlawful or rights-infringing submissions\n  text: submit domains, prompts, or content you do not have the right to submit, or that infringe or\
  \ violate any\n    third party's rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/citehawk-com/eligibility/citehawk-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CiteHawk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Visibility
- Brands
- Monitoring
---
