---

title: "Reels Tab and Profile Reels Partial Outage"
date: 2026-08-15 17:25:00
resolved: false
severity: disrupted
componentStatus: partial_outage
incidentStatus: identified
affected:

* "Reels Tab"
* "Profile Reels"
* "Profile Media"
* "Reel Publishing"
* "Reel Interactions"
* "Reel Discovery"
* "Creator Tools"
  section: issue

---

The Reels Tab and Profile Reels experiences are currently operating with a partial outage.

The local and on-device portions of the Reel experience remain available, including portions of Reel playback, navigation, presentation, and interface behavior. However, the complete online and cross-device workflows required for a fully connected Reel system are not yet available.

The affected areas include profile media, Reel publishing, Reel interactions, Reel discovery, and creator tools. These areas may have functioning local interfaces or partial on-device behavior while their complete online workflows remain unavailable or incomplete.

### Profile Media

Profile media functionality related to Reels is partially available. Local Reel media and profile-based viewing can function, but the complete online media workflow required for reliable synchronization, persistence, and availability across devices has not yet been completed.

### Reel Publishing

The Reel publishing experience is under active development. Local publishing interfaces and portions of the creation workflow may be available, but the complete online publishing pipeline and associated server-side workflow are not yet fully implemented.

### Reel Interactions

Interaction features such as likes, comments, saves, reposts, shares, and related Reel actions may be available within the local interface or prototype environment. Their complete online persistence, synchronization, and cross-device behavior remain incomplete.

### Reel Discovery

The Reels Tab and discovery functionality are partially available. The interface and local recommendation/feed presentation can operate, but the infrastructure required for a complete connected discovery workflow is still being developed.

### Creator Tools

Creator-facing Reel tools and management workflows are partially implemented. Local interfaces may be accessible, but the complete online creator workflow, including connected media management and persistent account-level behavior, remains unavailable or incomplete.

### Current impact

This is a partial outage rather than a complete loss of the Reel experience. Users may be able to open the Reels Tab, access Profile Reels, view locally available media, navigate Reel content, and use portions of the existing interaction and creator interfaces.

The primary limitation is that the underlying online services and cross-device workflows are not yet complete. As a result, functionality that depends on backend infrastructure, persistent synchronization, online publishing, discovery services, or connected creator workflows may be unavailable, incomplete, or behave differently from the intended production experience.

### Status

The missing infrastructure and workflow requirements have been identified.

Development remains active across profile media, Reel publishing, interactions, discovery, and creator tools. The incident will remain open until the required connected functionality is implemented, integrated, and verified across both the Reels Tab and Profile Reels experiences.

No resolution is currently available.
