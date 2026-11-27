---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, the Services are intended for adult use in the United States of America.
  minimum_age:
    text: No information should be submitted to or posted to any of the Services by users under 18 years of age without the consent of their parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: Unlicensed medical reliance
    text: THE CONTENT MAY NOT BE RELIED UPON IN ANY WAY IN CONNECTION WITH YOUR PERSONAL HEALTH CARE, RELATED DECISIONS AND TREATMENT.
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
name: Axena Health
provenance_date: '2026-11-09'
provider_name: Axena Health
provider_slug: axena-health
slug: axena-health-eligibility
source_date: '2026-11-09'
source_filename: axena-health-eligibility.yml
source_heading: Eligibility
source_page: https://axenahealth.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axena Health\naid: axena-health\nurl: https://axenahealth.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, the Services are intended for adult use in the United States of America.\nentity_types: []\nrestricted_uses:\n- summary: Unlicensed medical reliance\n  text: THE CONTENT MAY NOT BE RELIED UPON IN ANY WAY IN CONNECTION WITH YOUR PERSONAL HEALTH CARE, RELATED DECISIONS\n    AND TREATMENT.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: No information\
  \ should be submitted to or posted to any of the Services by users under 18 years of age without\n    the consent of their parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/axena-health/eligibility/axena-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Axena Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Medical Devices
- Women's Health
- Digital Therapeutics
- Pelvic Health
- Medical Software
- Telehealth
---
