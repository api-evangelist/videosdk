# VideoSDK

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

Real-time voice, video, and AI agent platform for developers. VideoSDK provides REST and WebSocket APIs for building video conferencing, live streaming, interactive broadcast applications, and real-time AI agent integrations.

**Website:** https://www.videosdk.live  
**API Docs:** https://docs.videosdk.live  
**GitHub Org:** https://github.com/videosdk-live  

## APIs

### Real-Time Communication API

Base URL: `https://api.videosdk.live`

The VideoSDK REST API covers:

- **Rooms** — Create and validate video rooms
- **Sessions** — Retrieve session data, participant lists, and quality statistics
- **Recordings** — Start/stop meeting recordings, participant recordings, track recordings, and merged recordings
- **Live Streams (RTMP-Out)** — Start and stop RTMP streams to external destinations
- **HLS Streaming** — Manage HLS streams and capture thumbnails

Authentication uses JWT access tokens passed in the `Authorization` header, generated from an API key and secret obtained from the VideoSDK dashboard.

## SDKs

VideoSDK provides client SDKs for:

- JavaScript / React
- React Native (Android / iOS)
- Flutter (Android / iOS)
- Android (Kotlin)
- iOS (Swift / Objective-C)
- Python (AI Agents framework)

## Pricing

VideoSDK uses usage-based participant-minute billing:

| Service | Rate |
|---|---|
| Audio Call | $0.0006 / participant-minute |
| HD Video (720p) | $0.003 / participant-minute |
| Full HD Video (1080p) | $0.007 / participant-minute |
| 2K / 2K+ Video | $0.007 / participant-minute |

The Free plan includes 10,000 participant-minutes per month. See [plans/videosdk-plans-pricing.yml](plans/videosdk-plans-pricing.yml) for full plan details.

## Links

- [Documentation](https://docs.videosdk.live)
- [API Reference](https://docs.videosdk.live/api-reference/realtime-communication/intro)
- [Pricing](https://www.videosdk.live/pricing)
- [Blog](https://www.videosdk.live/blog)
- [GitHub](https://github.com/videosdk-live)
- [LinkedIn](https://www.linkedin.com/company/video-sdk)
- [X / Twitter](https://x.com/video_sdk)
- [Support](https://www.videosdk.live/support)

## Maintainers

**Kin Lane** — kin@apievangelist.com
