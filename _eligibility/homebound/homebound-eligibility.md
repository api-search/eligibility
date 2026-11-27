---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable;
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You may be required to sign up for a Homebound account using an email address and password of your choosing
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Homebound
provenance_date: '2026-11-09'
provider_name: Homebound
provider_slug: homebound
slug: homebound-eligibility
source_date: '2026-11-09'
source_filename: homebound-eligibility.yml
source_heading: Eligibility
source_page: https://www.homebound.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homebound\naid: homebound\nurl: https://www.homebound.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable;\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: false\n  text: You may be required to sign up for a Homebound account using an email address and password of your choosing\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/homebound/eligibility/homebound-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Homebound's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction Technology
- Homebuilding
- Real Estate
- PropTech
- Home Construction
- Disaster Rebuild
---
