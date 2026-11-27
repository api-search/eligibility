---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: represent you are of legal age in your jurisdiction of residence to form a binding contract
    type: individual
  - text: if applicable, on behalf of any company, organization or other legal entity on whose behalf you use the Services
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: USE OF THE SERVICES IS NOT FOR MEDICAL EMERGENCIES.
  - summary: No use after prior removal or ban
    text: You agree not to create an Account or use the Services if you have been previously removed by Happier Meditation, or if you have been previously banned from any of the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: HAPPIER MEDITATION MAY, BUT IS NOT OBLIGATED TO, CONDUCT CRIMINAL BACKGROUND CHECKS OR EVALUATE THE CREDENTIALS OF ANY END USER OR COACH.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 10percenthappier
provenance_date: '2026-11-09'
provider_name: 10percenthappier
provider_slug: 10percenthappier-com
slug: 10percenthappier-com-eligibility
source_date: '2026-11-09'
source_filename: 10percenthappier-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.meditatehappier.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 10percenthappier\naid: 10percenthappier-com\nurl: https://www.meditatehappier.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: represent you are of legal age in your jurisdiction of residence to form a binding contract\n- type: business\n  text: if applicable, on behalf of any company, organization or other legal entity on whose behalf you use the\n    Services\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: USE OF THE SERVICES IS NOT FOR MEDICAL EMERGENCIES.\n- summary: No\
  \ use after prior removal or ban\n  text: You agree not to create an Account or use the Services if you have been previously removed by Happier Meditation,\n    or if you have been previously banned from any of the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: HAPPIER MEDITATION MAY, BUT IS NOT OBLIGATED TO, CONDUCT CRIMINAL BACKGROUND CHECKS OR EVALUATE THE CREDENTIALS\n    OF ANY END USER OR COACH.\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/10percenthappier-com/eligibility/10percenthappier-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from 10percenthappier's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mindfulness
- Meditation
- Health Tech
- Subscription
---
