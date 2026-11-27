---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use in the United States only.
  minimum_age:
    text: The Site is not directed at children under the age of eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or inaccurate-information use
    text: You will not use the Site for unlawful purposes. You will not submit inaccurate, incomplete, or out-of-date information via the Site, commit fraud or falsify information in connection with your use of the Site.
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
name: Apricot
provenance_date: '2026-11-09'
provider_name: Apricot
provider_slug: apricot
slug: apricot-eligibility
source_date: '2026-11-09'
source_filename: apricot-eligibility.yml
source_heading: Eligibility
source_page: https://www.apricothealth.ai/disclosures/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apricot\naid: apricot\nurl: https://www.apricothealth.ai/disclosures/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use in the United States only.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or inaccurate-information use\n  text: You will not use the Site for unlawful purposes. You will not submit inaccurate, incomplete, or out-of-date\n    information via the Site, commit fraud or falsify information in connection with your use of the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: The Site is not directed at children under the age of eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/apricot/eligibility/apricot-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Apricot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Post-Acute Care
- Clinical Documentation
- Artificial Intelligence
- HIPAA
- OASIS
---
