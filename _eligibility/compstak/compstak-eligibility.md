---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are operated from the United States and are directed solely to users located in the United States. CompStak does not target, market, or offer the Services to individuals located in the European Economic Area or the United Kingdom.
  entity_types:
  - text: BY ACCESSING THE SERVICES, YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST 18 YEARS OLD, ARE LEGALLY QUALIFIED TO ENTER INTO AND FORM CONTRACTS UNDER APPLICABLE LAW
    type: individual
  - text: If you are using the Services on behalf of a company, entity, or organization
    type: business
  minimum_age:
    text: The Services are not targeted to, and should not be used by, persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Competitor use prohibited
    text: For, at the direction of, or on behalf of (directly or indirectly) any company whose primary business to provide an online commercial real estate analytics platform
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to become a CompStak member (“Member”), you are required to complete a registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Compstak
provenance_date: '2026-11-09'
provider_name: Compstak
provider_slug: compstak
slug: compstak-eligibility
source_date: '2026-11-09'
source_filename: compstak-eligibility.yml
source_heading: Eligibility
source_page: https://compstak.com/legal#TermsOfUse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compstak\naid: compstak\nurl: https://compstak.com/legal#TermsOfUse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are operated from the United States and are directed solely to users located in the United\n    States. CompStak does not target, market, or offer the Services to individuals located in the European Economic\n    Area or the United Kingdom.\nentity_types:\n- type: individual\n  text: BY ACCESSING THE SERVICES, YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST 18 YEARS OLD, ARE LEGALLY QUALIFIED\n    TO ENTER INTO AND FORM CONTRACTS\
  \ UNDER APPLICABLE LAW\n- type: business\n  text: If you are using the Services on behalf of a company, entity, or organization\nrestricted_uses:\n- summary: Competitor use prohibited\n  text: For, at the direction of, or on behalf of (directly or indirectly) any company whose primary business to\n    provide an online commercial real estate analytics platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to become a CompStak member (“Member”), you are required to complete a registration process.\nminimum_age:\n  value: '18'\n  text: The Services are not targeted to, and should not be used by, persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/compstak/eligibility/compstak-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Compstak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commercial Real Estate
- Real Estate Data
- CRE
- Lease Comps
- Sale Comps
- Property Data
- Market Intelligence
- Data
---
