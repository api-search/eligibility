---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Through the App, individuals can book appointments with licensed healthcare practitioners
    type: individual
  minimum_age:
    text: is sixteen (16) years of age or older to identify him/herself.
    value: '16'
  restricted_uses:
  - summary: Account transfer prohibited
    text: may not be utilised by, or transferred to, another person.
  - summary: Recording consultations prohibited
    text: It is, among other things, not allowed to record any consultations with healthcare personal
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Signing of agreement, registering an Account and signing into the App require that the patient has a BankID and is sixteen (16) years of age or older to identify him/herself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KRY | LIVI
provenance_date: '2026-11-09'
provider_name: KRY | LIVI
provider_slug: kry-livi
slug: kry-livi-eligibility
source_date: '2026-11-09'
source_filename: kry-livi-eligibility.yml
source_heading: Eligibility
source_page: https://www.kry.se/en/legal/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KRY | LIVI\naid: kry-livi\nurl: https://www.kry.se/en/legal/eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Through the App, individuals can book appointments with licensed healthcare practitioners\nrestricted_uses:\n- summary: Account transfer prohibited\n  text: may not be utilised by, or transferred to, another person.\n- summary: Recording consultations prohibited\n  text: It is, among other things, not allowed to record any consultations with healthcare personal\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: Signing of agreement, registering an Account and signing into the App require that the patient has a BankID\n    and is sixteen (16) years of age or older to identify him/herself.\nminimum_age:\n  value: '16'\n  text: is sixteen (16) years of age or older to identify him/herself.\n"
source_yaml_url: https://artifacts.apis.io/kry-livi/eligibility/kry-livi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from KRY | LIVI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- Primary Care
- Mental Health
- Europe
- Sweden
- United Kingdom
---
