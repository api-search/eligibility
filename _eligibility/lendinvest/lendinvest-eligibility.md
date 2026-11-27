---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Save as set out to the contrary in the Local Country Specific Addendum, the Information on the Site and the Platform is not intended for use outside the UK
  minimum_age:
    text: solicit personal information from anyone under 18
    value: '18'
  restricted_uses:
  - summary: No use in unlawful jurisdictions
    text: The Site and the Platform is not intended for distribution to, or use by, any person or entity in any jurisdiction where such distribution or use would be contrary to Applicable Law.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: you must provide us with all information requested during the application process and comply with all our identification and anti-money laundering requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LendInvest
provenance_date: '2026-11-09'
provider_name: LendInvest
provider_slug: lendinvest
slug: lendinvest-eligibility
source_date: '2026-11-09'
source_filename: lendinvest-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendinvest.com/terms-and-conditions/user-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LendInvest\naid: lendinvest\nurl: https://www.lendinvest.com/terms-and-conditions/user-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Save as set out to the contrary in the Local Country Specific Addendum, the Information on the Site and\n    the Platform is not intended for use outside the UK\nentity_types: []\nrestricted_uses:\n- summary: No use in unlawful jurisdictions\n  text: The Site and the Platform is not intended for distribution to, or use by, any person or entity in any jurisdiction\n    where such distribution or use would be contrary to Applicable Law.\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: you must provide us with all information requested during the application process and comply with all our\n    identification and anti-money laundering requirements\nminimum_age:\n  value: '18'\n  text: solicit personal information from anyone under 18\n"
source_yaml_url: https://artifacts.apis.io/lendinvest/eligibility/lendinvest-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LendInvest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Mortgage
- Property Finance
- Real Estate
- Financial Services
- United Kingdom
---
