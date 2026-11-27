---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction in which the provision of the Services, software, or other components is prohibited under U.S. or other applicable laws or regulations
  entity_types:
  - text: if applicable, the entity you represent
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: GLBA
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  - summary: FISMA and similar industry regulations
    text: The Site is not tailored to comply with industry-specific regulations (Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Strella
provenance_date: '2026-11-10'
provider_name: Strella
provider_slug: strella
slug: strella-eligibility
source_date: '2026-11-10'
source_filename: strella-eligibility.yml
source_heading: Eligibility
source_page: https://www.strella.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strella\naid: strella\nurl: https://www.strella.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction\n    in which the provision of the Services, software, or other components is prohibited under U.S. or other applicable\n    laws or regulations\nentity_types:\n- type: business\n  text: if applicable, the entity you represent\nrestricted_uses:\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\n\
  - summary: FISMA and similar industry regulations\n  text: The Site is not tailored to comply with industry-specific regulations (Federal Information Security Management\n    Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/strella/eligibility/strella-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Strella's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Research
- User Research
- Market Research
- Qualitative Research
- AI Interviews
- Insights
---
