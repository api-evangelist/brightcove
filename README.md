# Brightcove (brightcove)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Brightcove is an online video platform providing REST APIs for uploading and managing videos, encoding, CDN delivery, player configuration, analytics, and live streaming management. Its Video Cloud platform serves media companies, broadcasters, marketers, and OTT providers globally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/brightcove/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/brightcove/refs/heads/main/apis.yml)

## Tags

- Video
- Media
- Streaming
- Live Streaming
- Analytics
- CDN
- OTT
- Player
- Ad Insertion

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Brightcove CMS API

Delivers uncached access to all media data within your Video Cloud library, enabling full CRUD operations on videos, playlists, and assets.

- **Human URL:** [https://apis.support.brightcove.com/cms/](https://apis.support.brightcove.com/cms/)
- **Base URL:** `https://cms.api.brightcove.com/v1`

#### Tags

- CMS
- Video Management
- Media

#### Properties

- [Documentation](https://apis.support.brightcove.com/cms/)
- [OpenAPI](https://apis.support.brightcove.com/cms/references/cms-api-swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Graph Q L](graphql/brightcove-graphql.md)

### Brightcove Dynamic Ingest API

Handles ingestion of videos and media assets into Video Cloud, supporting remote URL ingestion and upload from local files.

- **Human URL:** [https://apis.support.brightcove.com/dynamic-ingest/](https://apis.support.brightcove.com/dynamic-ingest/)
- **Base URL:** `https://ingest.api.brightcove.com/v1`

#### Tags

- Ingest
- Video Upload
- Encoding

#### Properties

- [Documentation](https://apis.support.brightcove.com/dynamic-ingest/)

### Brightcove Analytics API

Retrieves analytics data programmatically for Video Cloud accounts, including dimensions like device type, geography, player, and video performance metrics.

- **Human URL:** [https://apis.support.brightcove.com/analytics/](https://apis.support.brightcove.com/analytics/)
- **Base URL:** `https://analytics.api.brightcove.com/v1`

#### Tags

- Analytics
- Reporting
- Metrics

#### Properties

- [Documentation](https://apis.support.brightcove.com/analytics/)

### Brightcove Playback API

Fetches video and playlist data for players and mobile apps, providing optimized delivery of media metadata and playback URLs.

- **Human URL:** [https://apis.support.brightcove.com/playback/](https://apis.support.brightcove.com/playback/)
- **Base URL:** `https://edge.api.brightcove.com/playback/v1`

#### Tags

- Playback
- Video Delivery
- Player

#### Properties

- [Documentation](https://apis.support.brightcove.com/playback/)

### Brightcove Player Management API

Creates, edits, and manages Brightcove players as publishable resources with full configuration control.

- **Human URL:** [https://apis.support.brightcove.com/player-management/](https://apis.support.brightcove.com/player-management/)
- **Base URL:** `https://players.api.brightcove.com/v2`

#### Tags

- Player
- Configuration
- Management

#### Properties

- [Documentation](https://apis.support.brightcove.com/player-management/)

### Brightcove Live API

Creates and manages live streams with comprehensive streaming controls including RTMP, RTP, RTP-FEC, and SRT input protocols and HLS output delivery.

- **Human URL:** [https://apis.support.brightcove.com/live-api/](https://apis.support.brightcove.com/live-api/)
- **Base URL:** `https://api.bcovlive.io/v1`

#### Tags

- Live Streaming
- Broadcasting
- HLS

#### Properties

- [Documentation](https://apis.support.brightcove.com/live-api/)

### Brightcove OAuth API

Implements OAuth 2.0 client credentials flow for managing credentials and obtaining access tokens for all Brightcove REST APIs.

- **Human URL:** [https://apis.support.brightcove.com/oauth/](https://apis.support.brightcove.com/oauth/)
- **Base URL:** `https://oauth.brightcove.com/v4`

#### Tags

- OAuth
- Authentication
- Security

#### Properties

- [Documentation](https://apis.support.brightcove.com/oauth/)

### Brightcove SSAI API

Enables server-side ad stitching directly into video streams, supporting VOD and live stream monetization with seamless ad insertion.

- **Human URL:** [https://apis.support.brightcove.com/ssai/](https://apis.support.brightcove.com/ssai/)
- **Base URL:** `https://ssai.api.brightcove.com/v1`

#### Tags

- Ad Insertion
- Monetization
- SSAI

#### Properties

- [Documentation](https://apis.support.brightcove.com/ssai/)

### Brightcove Ingest Profiles API

Manages profiles that define video processing during ingestion, controlling encoding settings and rendition creation.

- **Human URL:** [https://apis.support.brightcove.com/ingest-profiles/](https://apis.support.brightcove.com/ingest-profiles/)
- **Base URL:** `https://ingestion.api.brightcove.com/v1`

#### Tags

- Encoding
- Ingest Profiles
- Transcoding

#### Properties

- [Documentation](https://apis.support.brightcove.com/ingest-profiles/)

### Brightcove Delivery Rules API

Customizes media delivery to meet specific business objectives, enabling conditional logic for rendition selection and CDN routing.

- **Human URL:** [https://apis.support.brightcove.com/delivery-rules/](https://apis.support.brightcove.com/delivery-rules/)
- **Base URL:** `https://delivery-rules.api.brightcove.com`

#### Tags

- Delivery
- CDN
- Rules Engine

#### Properties

- [Documentation](https://apis.support.brightcove.com/delivery-rules/)

### Brightcove Cloud Playout APIs

Manages cloud-based linear channel playout with EPG (Electronic Programming Guide) and Channels APIs for scheduled programming.

- **Human URL:** [https://apis.support.brightcove.com/cloud-playout-apis/](https://apis.support.brightcove.com/cloud-playout-apis/)
- **Base URL:** `https://cm.cloudplayout.brightcove.com`

#### Tags

- Cloud Playout
- Linear TV
- EPG
- Channels

#### Properties

- [Documentation](https://apis.support.brightcove.com/cloud-playout-apis/)

### Brightcove Audience API

Retrieves viewing event and lead data for marketing automation workflows, enabling integration with MAP and CRM platforms.

- **Human URL:** [https://apis.support.brightcove.com/audience/](https://apis.support.brightcove.com/audience/)
- **Base URL:** `https://audience.api.brightcove.com/v1`

#### Tags

- Audience
- Marketing Automation
- Lead Data

#### Properties

- [Documentation](https://apis.support.brightcove.com/audience/)

### Brightcove Social API

Retrieves social sharing status and history for videos distributed to social media platforms.

- **Human URL:** [https://apis.support.brightcove.com/social/](https://apis.support.brightcove.com/social/)
- **Base URL:** `https://edge.social.api.brightcove.com/v1`

#### Tags

- Social Media
- Distribution
- Sharing

#### Properties

- [Documentation](https://apis.support.brightcove.com/social/)

### Brightcove Playback Restrictions API

Provides scalable playback management including DRM, concurrency controls, and geographic and domain restrictions.

- **Human URL:** [https://apis.support.brightcove.com/playback-restrictions/](https://apis.support.brightcove.com/playback-restrictions/)
- **Base URL:** `https://playback-auth.api.brightcove.com`

#### Tags

- DRM
- Playback Restrictions
- Security
- Concurrency

#### Properties

- [Documentation](https://apis.support.brightcove.com/playback-restrictions/)

## Common Properties

- [Website](https://www.brightcove.com)
- [Documentation](https://apis.support.brightcove.com/)
- [Git Hub Org](https://github.com/brightcove)
- [LinkedIn](https://www.linkedin.com/company/brightcove)
- [Blog](https://www.brightcove.com/en/blog/)
- [Pricing](https://www.brightcove.com/en/contact/)
- [Status Page](https://status.brightcove.com/)
- [X (Twitter)](https://x.com/brightcove)
- [Plans](plans/brightcove-plans-pricing.yml)
- [Rate Limits](rate-limits/brightcove-rate-limits.yml)
- [Fin Ops](finops/brightcove-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
