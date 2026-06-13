# VideoSDK

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
