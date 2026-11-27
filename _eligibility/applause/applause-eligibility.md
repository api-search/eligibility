---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction of residence or persons who do not have the legal authority to enter into binding contracts.
    type: individual
  - text: By registering to use the Site as a Company, You represent to Applause that You have the authority to agree to these Terms of Use on behalf of Your Company.
    type: business
  minimum_age:
    text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction of residence
    value: null
  restricted_uses:
  - summary: Sensitive personal or regulated data
    text: to receive, send, or otherwise process sensitive personal data such credit card and payment information, or Protected Health Information as defined by the Health Insurance Portability and Accountability Act of 1996 as amended
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Applause shall have absolute discretion as to whether or not it permits a particular User to use or access the Site or any Site Content.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Applause
provenance_date: '2026-11-09'
provider_name: Applause
provider_slug: applause
slug: applause-eligibility
source_date: '2026-11-09'
source_filename: applause-eligibility.yml
source_heading: Eligibility
source_page: https://www.applause.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Applause\naid: applause\nurl: https://www.applause.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction\n    of residence or persons who do not have the legal authority to enter into binding contracts.\n- type: business\n  text: By registering to use the Site as a Company, You represent to Applause that You have the authority to agree\n    to these Terms of Use on behalf of Your Company.\n\
  restricted_uses:\n- summary: Sensitive personal or regulated data\n  text: to receive, send, or otherwise process sensitive personal data such credit card and payment information,\n    or Protected Health Information as defined by the Health Insurance Portability and Accountability Act of 1996\n    as amended\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Applause shall have absolute discretion as to whether or not it permits a particular User to use or access\n    the Site or any Site Content.\nminimum_age:\n  value: null\n  text: The Site and the Site Content are not available to persons that are minors under the laws of their jurisdiction\n    of residence\n"
source_yaml_url: https://artifacts.apis.io/applause/eligibility/applause-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Applause's own page on 2026-11-09.
synthetic: false
tags:
- Software Testing
- Crowdtesting
- AI Testing
- Functional Testing
- Accessibility Testing
- Payment Testing
- Localization
- Security Testing
---
