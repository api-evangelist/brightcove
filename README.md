# Brightcove (brightcove)

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
