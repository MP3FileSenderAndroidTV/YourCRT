# YourCRT

**YourCRT: What video playback was meant to be in 2009.**

[Polski](README_pl-PL.md) | [Русский](README_ru-RU.md)

**YourCRT** is a native YouTube client specifically designed for the **Sony Ericsson Xperia X10 Mini (E10i/E10a)** running **stock Android 1.6 (Donut)**. 

No **custom ROMs**, **no kernels**—just **pure**, functional legacy hardware support for the "Robyn."

# 2009 Reconstruction

Authentic Discovery: Feeds prioritized for "Most Viewed" and "Related" content, mimicking the pre-algorithmic era of 2009.

Streamlined UI: Modern **"Stars"** replaced with clean, raw **Like/Dislike** counts to balance 2009 aesthetics with modern API data.

V1 Signing Exclusive: Specifically JAR-signed to pass the strict requirements of the **Android 1.6 Package Manager**.

Direct Render Bridge: Bypasses Donut's lack of modern TLS support via a custom HTTP bridge on **Render** to access the **YouTube Data API v3**.

# Technical Specs & Optimization

API Key Powered: **Direct-to-Google** architecture. Users provide their own API key for a private, stable, and TOS-compliant connection.

High-Capacity Storage: Optimized to leverage **64GB MicroSDXC cards** on original 2010 firmware, enabling massive metadata and thumbnail caching.

Hardcoded Playback: Forced **144p/240p streams** (itag 17/36) to ensure the **600MHz ARMv6** hardware decoder remains fluid and responsive.

# Deployment & Development

Lead Dev Device: **Xiaomi 22126RN91Y (Redmi 12C)**.

Build Toolchain: **MT Manager** (Smali/DEX surgery).

Base: Gutted code of **notPipe**. All **scrapers (Invidious, YT2009, S60Tube, etc.)** and download logic have been removed for a lean, stable, and "handmade" build.

# Licenses

YourCRT: Apache 2.0 License

NNJSON: MIT License


# Credits

Gohoski: made the [notPipe](https://github.com/gohoski/notPipe) project which I'm making TOS safe cause notPipe breaks the Google and YouTube TOS. What a dumbass.

Lyano Community: made the [Market Reborn](https://market.lyano.ovh) app store.

NNJSON: some code uses NNJSON code but I don't fucking know what.
# _**Hand-crafted for the Robyn community on a Redmi 12C.**_