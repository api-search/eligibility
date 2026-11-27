---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access and use this Site outside the United States you are responsible for complying with your local laws and regulations.
  entity_types:
  - text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent that you are at least 18 years old.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No unlawful, misleading, malicious or discriminatory use
    text: access the Services for anything unlawful, misleading, malicious or discriminatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will need to register with One Health Company to become a Customer. You agree to provide accurate, complete registration information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fidocure
provenance_date: '2026-11-09'
provider_name: Fidocure
provider_slug: fidocure
slug: fidocure-eligibility
source_date: '2026-11-09'
source_filename: fidocure-eligibility.yml
source_heading: Eligibility
source_page: https://fidocure.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fidocure\naid: fidocure\nurl: https://fidocure.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access and use this Site outside the United States you are responsible for complying with your local\n    laws and regulations.\nentity_types:\n- type: individual\n  text: By accessing or using the Site, and/or using a Service, (i) you agree to these Terms and (ii) you represent\n    that you are at least 18 years old.\nrestricted_uses:\n- summary: No unlawful, misleading, malicious or discriminatory use\n  text: access the Services for anything unlawful, misleading,\
  \ malicious or discriminatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will need to register with One Health Company to become a Customer. You agree to provide accurate, complete\n    registration information\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/fidocure/eligibility/fidocure-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fidocure's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Precision Medicine
- Veterinary
- Genomics
- Oncology
- Healthcare
- Pets
- Diagnostics
---
