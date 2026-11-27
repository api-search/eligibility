---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not (a) a resident or national of an Embargoed Country; (b) an entity organized under the laws of an Embargoed Country
  entity_types:
  - text: if you are using our Software on behalf of an organization, entity, or third party (collectively, “Organization”), you represent and warrant that you are an authorized representative of that Organization
    type: business
  minimum_age:
    text: By accessing our application and using our Software and Service, each User affirms that they are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No High Risk Activities
    text: (viii) use the Product with any High Risk Activities or with any activity prohibited by Applicable Laws
  - summary: No Prohibited Data submission
    text: Customer will not (and will not allow anyone else to) submit Prohibited Data to the Product.
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
name: GovSignals
provenance_date: '2026-11-09'
provider_name: GovSignals
provider_slug: govsignals
slug: govsignals-eligibility
source_date: '2026-11-09'
source_filename: govsignals-eligibility.yml
source_heading: Eligibility
source_page: https://www.govsignals.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GovSignals\naid: govsignals\nurl: https://www.govsignals.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not (a) a resident or national of an Embargoed Country; (b)\n    an entity organized under the laws of an Embargoed Country\nentity_types:\n- type: business\n  text: if you are using our Software on behalf of an organization, entity, or third party (collectively, “Organization”),\n    you represent and warrant that you are an authorized representative of that Organization\nrestricted_uses:\n- summary: No High Risk Activities\n\
  \  text: (viii) use the Product with any High Risk Activities or with any activity prohibited by Applicable Laws\n- summary: No Prohibited Data submission\n  text: Customer will not (and will not allow anyone else to) submit Prohibited Data to the Product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing our application and using our Software and Service, each User affirms that they are at least\n    18 years of age\n"
source_yaml_url: https://artifacts.apis.io/govsignals/eligibility/govsignals-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from GovSignals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Procurement
- Government
- Platform
---
