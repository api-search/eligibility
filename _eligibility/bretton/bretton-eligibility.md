---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Not for HIPAA/FISMA-regulated interactions
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: No GLBA-violating use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bretton
provenance_date: '2026-11-09'
provider_name: Bretton
provider_slug: bretton
slug: bretton-eligibility
source_date: '2026-11-09'
source_filename: bretton-eligibility.yml
source_heading: Eligibility
source_page: https://www.bretton.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bretton\naid: bretton\nurl: https://www.bretton.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Not for HIPAA/FISMA-regulated interactions\n  text: The\
  \ Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: No GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/bretton/eligibility/bretton-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bretton's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- RegTech
- Financial Crime Compliance
- AML
- KYC
- AI Agents
- Compliance
- Financial Services
---
