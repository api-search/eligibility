---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By accessing and using the PetsApp Service, you certify that you: (1) are 18 years of age or older'
    type: individual
  - text: For Service Providers, this means that you, as a current, UK-practising member of the Royal College of Veterinary Surgeons, are legally eligible to provide veterinarian services within the UK
    type: business
  minimum_age:
    text: 'you certify that you: (1) are 18 years of age or older'
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited content
    text: Not to post content or materials that are pornographic, threatening, harassing, abusive, or defamatory, or that contain nudity or graphic violence, incite violence, violate intellectual property rights, or violate the law
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
name: Petsapp
provenance_date: '2026-11-10'
provider_name: Petsapp
provider_slug: petsapp
slug: petsapp-eligibility
source_date: '2026-11-10'
source_filename: petsapp-eligibility.yml
source_heading: Eligibility
source_page: https://petsapp.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Petsapp\naid: petsapp\nurl: https://petsapp.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By accessing and using the PetsApp Service, you certify that you: (1) are 18 years of age or older'\n- type: business\n  text: For Service Providers, this means that you, as a current, UK-practising member of the Royal College of Veterinary\n    Surgeons, are legally eligible to provide veterinarian services within the UK\nrestricted_uses:\n- summary: Unlawful or prohibited content\n  text: Not to post content or materials\
  \ that are pornographic, threatening, harassing, abusive, or defamatory,\n    or that contain nudity or graphic violence, incite violence, violate intellectual property rights, or violate\n    the law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'you certify that you: (1) are 18 years of age or older'\n"
source_yaml_url: https://artifacts.apis.io/petsapp/eligibility/petsapp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Petsapp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Veterinary
- Practice Management
- Client Communication
- Appointments
- Payments
- Messaging
- Software-as-a-Service
- Animal Health
---
