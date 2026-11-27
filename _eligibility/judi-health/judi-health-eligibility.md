---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: YOU ARE A RESIDENT OF THE UNITED STATES AND ITS TERRITORIES. WE WILL REDIRECT ANY VISITORS TO THE SITE FROM THE EUROPEAN UNION TO A MESSAGE NOTIFYING SUCH VISITORS THAT THEY CANNOT REGISTER FOR OR USETHE SITE OR SERVICES.
  minimum_age:
    text: YOU ARE LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Lawful, legitimate prescription information only
    text: You may only use the Site to view information for which you are authorized and to search for legitimate prescription medication information.
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
name: Judi Health
provenance_date: '2026-11-09'
provider_name: Judi Health
provider_slug: judi-health
slug: judi-health-eligibility
source_date: '2026-11-09'
source_filename: judi-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.judi.health/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Judi Health\naid: judi-health\nurl: https://www.judi.health/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: YOU ARE A RESIDENT OF THE UNITED STATES AND ITS TERRITORIES. WE WILL REDIRECT ANY VISITORS TO THE SITE FROM\n    THE EUROPEAN UNION TO A MESSAGE NOTIFYING SUCH VISITORS THAT THEY CANNOT REGISTER FOR OR USETHE SITE OR SERVICES.\nentity_types: []\nrestricted_uses:\n- summary: Lawful, legitimate prescription information only\n  text: You may only use the Site to view information for which you are authorized and to search for legitimate\n    prescription\
  \ medication information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/judi-health/eligibility/judi-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Judi Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy Benefits
- PBM
- Health Benefits
- Benefits Administration
- Health Tech
- Medicare
- Insurance
---
