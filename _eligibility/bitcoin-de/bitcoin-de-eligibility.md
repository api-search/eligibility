---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served:
    - DE
    - CH
    - GB
    - AU
    - BR
    - IN
    - JP
    - CA
    - MX
    - SG
    - ZA
    - KR
    text: einen ständigen Wohnsitz in der Bundesrepublik Deutschland oder in einem anderen Staat des Europäischen Wirtschaftsraumes oder in der Schweiz oder im Vereinigten Königreich; US-Bürger, juristische Personen nach dem Recht der USA
  entity_types:
  - text: Volljährigkeit sowohl im Sinne des § 2 BGB als auch gemäß dem Recht des Staates
    type: individual
  - text: Am Handel auf bitcoin.de können natürliche und juristische Personen teilnehmen.
    type: business
  minimum_age:
    text: Volljährigkeit sowohl im Sinne des § 2 BGB als auch gemäß dem Recht des Staates, dem der potentielle Kunde angehört
    value: null
  restricted_uses:
  - summary: Own account only
    text: Der Kunde darf beim Kauf und Verkauf von Kryptoeinheiten auf bitcoin.de nur im eigenen Namen und auf eigene Rechnung handeln.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitcoin.de
provenance_date: '2026-11-09'
provider_name: Bitcoin.de
provider_slug: bitcoin-de
slug: bitcoin-de-eligibility
source_date: '2026-11-09'
source_filename: bitcoin-de-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitcoin.de/de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitcoin.de\naid: bitcoin-de\nurl: https://www.bitcoin.de/de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - DE\n  - CH\n  - GB\n  - AU\n  - BR\n  - IN\n  - JP\n  - CA\n  - MX\n  - SG\n  - ZA\n  - KR\n  excluded:\n  - US\n  text: einen ständigen Wohnsitz in der Bundesrepublik Deutschland oder in einem anderen Staat des Europäischen\n    Wirtschaftsraumes oder in der Schweiz oder im Vereinigten Königreich; US-Bürger, juristische Personen nach dem\n    Recht der USA\nentity_types:\n- type: individual\n  text: Volljährigkeit sowohl im Sinne des § 2 BGB als auch gemäß dem Recht des Staates\n\
  - type: business\n  text: Am Handel auf bitcoin.de können natürliche und juristische Personen teilnehmen.\nrestricted_uses:\n- summary: Own account only\n  text: Der Kunde darf beim Kauf und Verkauf von Kryptoeinheiten auf bitcoin.de nur im eigenen Namen und auf eigene\n    Rechnung handeln.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Volljährigkeit sowohl im Sinne des § 2 BGB als auch gemäß dem Recht des Staates, dem der potentielle Kunde\n    angehört\n"
source_yaml_url: https://artifacts.apis.io/bitcoin-de/eligibility/bitcoin-de-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bitcoin.de's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
