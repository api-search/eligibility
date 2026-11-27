---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: If you are using this account on behalf of an organization, then you are agreeing to these terms and conditions for that organization
    type: business
  - text: if you are a government entity, the Commercial Computer Software and Commercial Computer Software Documentation are being licensed to U.S. Government end users
    type: government
  minimum_age:
    text: you represent, acknowledge and agree that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Third-party rights and privacy
    text: You may not view or manipulate, using the Software Application, any material protected by copyright, trademark, or any other proprietary or privacy right without the express permission of the owner
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
name: Sira Medical
provenance_date: '2026-11-10'
provider_name: Sira Medical
provider_slug: sira-medical
slug: sira-medical-eligibility
source_date: '2026-11-10'
source_filename: sira-medical-eligibility.yml
source_heading: Eligibility
source_page: https://siramedical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sira Medical\naid: sira-medical\nurl: https://siramedical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: business\n  text: If you are using this account on behalf of an organization, then you are agreeing to these terms and conditions\n    for that organization\n- type: government\n  text: if you are a government entity, the Commercial\
  \ Computer Software and Commercial Computer Software Documentation\n    are being licensed to U.S. Government end users\nrestricted_uses:\n- summary: Third-party rights and privacy\n  text: You may not view or manipulate, using the Software Application, any material protected by copyright, trademark,\n    or any other proprietary or privacy right without the express permission of the owner\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent, acknowledge and agree that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/sira-medical/eligibility/sira-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sira Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Augmented Reality
- Surgical Planning
- Radiology
- Medical Devices
- Visualization
---
