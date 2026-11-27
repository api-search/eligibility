---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Website and may not accept these Terms if you are a person barred from using the Website under the laws of the country in which you are a resident or from which you use the Website.
  entity_types:
  - text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent and warrant that you have full legal authority to bind your employer or such entity to these Terms.
    type: business
  minimum_age:
    text: You declare that by acceptance of these Terms and/or by using the Website, you are of legal age to form a binding contract with Dot Compliance.
    value: null
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
name: Dot Compliance
provenance_date: '2026-11-09'
provider_name: Dot Compliance
provider_slug: dot-compliance
slug: dot-compliance-eligibility
source_date: '2026-11-09'
source_filename: dot-compliance-eligibility.yml
source_heading: Eligibility
source_page: https://www.dotcompliance.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dot Compliance\naid: dot-compliance\nurl: https://www.dotcompliance.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Website and may not accept these Terms if you are a person barred from using the Website\n    under the laws of the country in which you are a resident or from which you use the Website.\nentity_types:\n- type: business\n  text: If you are agreeing to be bound by these Terms on behalf of your employer or other entity, you represent\n    and warrant that you have full legal authority to bind your employer or such entity to these\
  \ Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You declare that by acceptance of these Terms and/or by using the Website, you are of legal age to form\n    a binding contract with Dot Compliance.\n"
source_yaml_url: https://artifacts.apis.io/dot-compliance/eligibility/dot-compliance-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Dot Compliance's own page on 2026-11-09.
synthetic: false
tags:
- eQMS
- Quality Management
- Life Sciences
- Pharmaceuticals
- Biotechnology
- Medical Devices
- Compliance
- Salesforce
---
