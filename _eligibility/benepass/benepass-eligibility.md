---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is controlled and operated from facilities in the United States. You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked or denied by the United States government.
  minimum_age:
    text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Embargoed countries and blocked persons
    text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked or denied by the United States government.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Benepass may require identity, sanctions, employment, eligibility, tax, banking, fraud, or compliance checks before enabling or continuing access to features such as reimbursements, payment cards, account funding, investment-related features, or regulated partner services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Benepass
provenance_date: '2026-11-09'
provider_name: Benepass
provider_slug: benepass
slug: benepass-eligibility
source_date: '2026-11-09'
source_filename: benepass-eligibility.yml
source_heading: Eligibility
source_page: https://benepass.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Benepass\naid: benepass\nurl: https://benepass.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is controlled and operated from facilities in the United States. You may not use the Service\n    if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked\n    or denied by the United States government.\nentity_types: []\nrestricted_uses:\n- summary: Embargoed countries and blocked persons\n  text: You may not use the Service if you are a resident of a country embargoed by the United States or are a\
  \ foreign\n    person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Benepass may require identity, sanctions, employment, eligibility, tax, banking, fraud, or compliance checks\n    before enabling or continuing access to features such as reimbursements, payment cards, account funding, investment-related\n    features, or regulated partner services.\nminimum_age:\n  value: '18'\n  text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/benepass/eligibility/benepass-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Benepass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Employee Benefits
- Human Resources
- Payroll
- Benefits Administration
- Health Savings Account
- Lifestyle Spending Account
---
