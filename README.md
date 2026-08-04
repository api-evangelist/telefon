# Telefon (telefon)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Telefon is a cloud-based programmable communications platform providing voice calling, SMS messaging, number management, and call recording APIs for developers and enterprises. The platform enables applications to make and receive phone calls, send SMS and MMS messages, manage phone number inventories, and record calls for compliance and quality assurance purposes. Telefon supports global coverage across 180+ countries with competitive per-minute and per-message pricing.

**APIs.json:** [https://www.telefon.com](https://www.telefon.com)

## Scope

- **Type:** Index

## Tags

- Call Recording
- Communications
- CPaaS
- Global Coverage
- Messaging
- Number Provisioning
- SMS
- Telephony
- Voice
- VoIP

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Telefon Voice API

Programmable voice API for building call-based applications. Make outbound calls, handle inbound calls with webhooks, build IVR menus, perform call transfer and conferencing, and control calls in real-time. Supports SIP trunking, WebRTC, text-to-speech, speech recognition, and call recording.

- **Human URL:** [https://developers.telefon.com/voice](https://developers.telefon.com/voice)
- **Base URL:** `https://api.telefon.com/v1/voice`

#### Tags

- Calls
- Communications
- IVR
- SIP Trunking
- Telephony
- TTS
- Voice
- WebRTC

#### Properties

- [Documentation](https://developers.telefon.com/voice)
- [OpenAPI](openapi/telefon-voice-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefon-voice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefon-voice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefon.com/authentication)
- [Getting Started](https://developers.telefon.com/getting-started)
- [Pricing](https://www.telefon.com/pricing/voice)
- [Rate Limits](https://developers.telefon.com/rate-limits)

### Telefon SMS API

Send and receive SMS and MMS messages globally. Supports A2P (Application-to-Person) messaging, two-way conversational SMS, delivery receipts, inbound webhooks, message queuing for high throughput, and unicode character sets for international languages. Compliant with TCPA (US), GDPR (EU), and other regional regulations.

- **Human URL:** [https://developers.telefon.com/sms](https://developers.telefon.com/sms)
- **Base URL:** `https://api.telefon.com/v1/sms`

#### Tags

- A2P Messaging
- Communications
- Messaging
- MMS
- SMS
- Two-Way SMS
- Unicode

#### Properties

- [Documentation](https://developers.telefon.com/sms)
- [OpenAPI](openapi/telefon-sms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefon-sms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefon-sms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefon.com/authentication)
- [Pricing](https://www.telefon.com/pricing/sms)
- [Rate Limits](https://developers.telefon.com/rate-limits)

### Telefon Number Management API

Search, provision, configure, and manage phone numbers worldwide. Supports local, national, mobile, toll-free, and short code numbers across 70+ countries. Configure voice and SMS routing, manage number pools, and handle number portability requests. Supports regulatory compliance requirements including address verification for regulated number types.

- **Human URL:** [https://developers.telefon.com/numbers](https://developers.telefon.com/numbers)
- **Base URL:** `https://api.telefon.com/v1/numbers`

#### Tags

- DID
- Number Management
- Number Portability
- Number Provisioning
- Phone Numbers
- Short Codes
- Toll-Free

#### Properties

- [Documentation](https://developers.telefon.com/numbers)
- [OpenAPI](openapi/telefon-numbers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefon-numbers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefon-numbers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefon.com/authentication)
- [Pricing](https://www.telefon.com/pricing/numbers)

### Telefon Call Recording API

Record, store, transcribe, and retrieve call recordings. Supports on-demand and automatic recording, dual-channel recording for separate caller/callee audio, AI-powered transcription in 30+ languages, PII redaction, storage management, and compliance archiving with configurable retention policies.

- **Human URL:** [https://developers.telefon.com/recording](https://developers.telefon.com/recording)
- **Base URL:** `https://api.telefon.com/v1/recording`

#### Tags

- AI Transcription
- Audio
- Call Recording
- Compliance
- Dual Channel
- PII Redaction
- Storage
- Transcription

#### Properties

- [Documentation](https://developers.telefon.com/recording)
- [OpenAPI](openapi/telefon-recording-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefon-recording.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefon-recording.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefon.com/authentication)
- [Privacy Policy](https://www.telefon.com/privacy)
- [Compliance](https://www.telefon.com/compliance)

## Common Properties

- [Getting Started](https://developers.telefon.com/getting-started)
- [Authentication](https://developers.telefon.com/authentication)
- [S D Ks](https://www.telefon.com/sdks)
- [Status Page](https://status.telefon.com)
- [Terms of Service](https://www.telefon.com/terms)
- [Privacy Policy](https://www.telefon.com/privacy)
- [Support](https://www.telefon.com/support)
- [Blog](https://blog.telefon.com)
- [Changelog](https://developers.telefon.com/changelog)
- [Pricing](https://www.telefon.com/pricing)
- [Git Hub](https://github.com/telefon-api)
- [L L Ms Txt](https://telefon.com/llms.txt)

## Maintainers

**Email:** api@telefon.com
