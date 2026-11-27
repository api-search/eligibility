---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 (or whatever the legal adult age is where you live), you can only use our Services if your parent or guardian agrees to these Terms and supervises your use of the Services.
    type: individual
  - text: If you're using our services for someone else (like a person or company), these Terms apply to both you and them.
    type: business
  minimum_age:
    text: If you are under 18 (or whatever the legal adult age is where you live), you can only use our Services if your parent or guardian agrees to these Terms and supervises your use of the Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct
    text: Use the Services to engage in illegal activities or violate the rights of others.
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
name: Prenda
provenance_date: '2026-11-10'
provider_name: Prenda
provider_slug: prenda
slug: prenda-eligibility
source_date: '2026-11-10'
source_filename: prenda-eligibility.yml
source_heading: Eligibility
source_page: https://www.prenda.com/page/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prenda\naid: prenda\nurl: https://www.prenda.com/page/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 (or whatever the legal adult age is where you live), you can only use our Services if\n    your parent or guardian agrees to these Terms and supervises your use of the Services.\n- type: business\n  text: If you're using our services for someone else (like a person or company), these Terms apply to both you\n    and them.\nrestricted_uses:\n- summary: Prohibited conduct\n  text: Use the Services\
  \ to engage in illegal activities or violate the rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 (or whatever the legal adult age is where you live), you can only use our Services if\n    your parent or guardian agrees to these Terms and supervises your use of the Services.\n"
source_yaml_url: https://artifacts.apis.io/prenda/eligibility/prenda-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Prenda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Education Technology
- Microschools
- K-12
- LMS
- Curriculum
- School Choice
- Homeschooling
- Design Systems
---
