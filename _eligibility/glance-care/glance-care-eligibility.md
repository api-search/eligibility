---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By registering to use the Site as a Company, you represent to Buglance that you have the authority to agree to these Terms of Use on behalf of your Company.
    type: business
  - text: The Site is available only to individuals and entities which can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction of residence
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Buglance shall have absolute discretion as to whether or not it permits a particular User to use or access the Site or any Site Content.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Buglance
provenance_date: '2026-11-09'
provider_name: Buglance
provider_slug: glance-care
slug: glance-care-eligibility
source_date: '2026-11-09'
source_filename: glance-care-eligibility.yml
source_heading: Eligibility
source_page: https://buglance.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buglance\naid: glance-care\nurl: https://buglance.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By registering to use the Site as a Company, you represent to Buglance that you have the authority to agree\n    to these Terms of Use on behalf of your Company.\n- type: individual\n  text: The Site is available only to individuals and entities which can form legally binding contracts under applicable\n    law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Buglance\
  \ shall have absolute discretion as to whether or not it permits a particular User to use or access\n    the Site or any Site Content.\nminimum_age:\n  value: null\n  text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction\n    of residence\n"
source_yaml_url: https://artifacts.apis.io/glance-care/eligibility/glance-care-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Buglance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software Testing
- Quality Assurance
- Crowdsourced Testing
- Bug Reporting
- Mobile Testing
- Test Management
---
