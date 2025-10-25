# Duolingo Local
### *Bridging the gap between in-app practice and real-world confidence*

<p align="center">
  <a href="https://jad-takieddin.github.io/DuolingoLocal-Jad/">
    <img src="https://img.shields.io/badge/🎮_LIVE_PROTOTYPE-58CC02?style=for-the-badge&logoColor=white" alt="Live Prototype" height="40"/>
  </a>
  &nbsp;&nbsp;
  <a href="./Jad-Duolingo-APM-Deck.pdf">
    <img src="https://img.shields.io/badge/📊_FULL_DECK-1CB0F6?style=for-the-badge&logoColor=white" alt="Full Deck" height="40"/>
  </a>
</p>

---

## Overview

Language learners face a common challenge: they practice vocabulary and grammar in apps like Duolingo, but freeze up when trying to use their skills in real conversations. **Duolingo Local** addresses this by transforming cities into interactive language classrooms, where users complete location-based missions at local businesses.

This feature creates a new engagement loop that drives retention for at-risk users while establishing valuable partnerships with local merchants.

---

## The Opportunity

Analysis of Duolingo's user data reveals that **most churn happens within the first few weeks** as motivation declines. The Growth Model shows that increasing Current User Retention Rate (CURR) by just 2% month-over-month has the highest impact on daily active users. 

This feature targets at-risk weekly active users with a fresh engagement mechanic that creates tangible, real-world value.

---

## User Experience Flow

**1. Home Screen** → Users discover the feature through a new "Local" tab in the main navigation, marked with a notification badge showing available missions nearby.

**2. Discover Map** → An interactive map displays mission locations with distance indicators. Users can browse different challenges at various local venues like restaurants, cafes, and shops.

**3. Mission Details** → Each mission provides clear instructions, contextual hints, and shows rewards upfront. For example: *"Find 'pollo' on the menu at Luigi's Pizzeria"* with a hint that pollo means chicken in Spanish.

**4. Photo Verification** → Users verify completion by taking a photo. The interface guides them with visual indicators and provides clear feedback.

**5. Rewards** → Upon completion, users earn XP toward personal goals, unlock progress on location-based badges, and receive coupons from participating businesses.

---

## Success Metrics

<div align="center">

| Metric | Target | Success Criteria |
|:-------|:------:|:-----------------|
| **At-Risk WAU Retention** | +3% vs. control | Primary metric demonstrating retention impact |
| **Feature Participation Rate** | >20% of variant group | Validates product-market fit |
| **Mission Completion Rate** | >60% once started | Indicates appropriate difficulty calibration |
| **Merchant Partner Satisfaction** | >4.0/5.0 avg. rating | Ensures sustainable partnership model |

</div>

These thresholds align with Duolingo's growth targets and demonstrate meaningful business impact. The metric selection reflects where the company sees highest leverage: retaining users on the verge of churning.

---

## Validation Roadmap

```
Week 0-1         Week 1-2              Week 3-8                Week 9+
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Discovery    →   Intent Survey    →    Pilot Launch      →    Optimization
                                        (NYC & Toronto)         Loop
```

### Phase 1: Discovery (Weeks 0-1)
Interview 20 learners per pilot city to understand motivation patterns and preferences around in-person language practice. Conduct usability testing on mission types to identify what feels achievable versus overwhelming.

### Phase 2: Intent Survey (Weeks 1-2)
Survey 3,000-5,000 at-risk users to gauge interest. If 40% or more show positive intent, proceed to pilot.

### Phase 3: Pilot (Weeks 3-8)
Launch in two high-density markets (NYC and Toronto) with 5,000 learners per city. Run a controlled A/B test to measure retention impact and participation rates. Monitor for any negative effects on core learning metrics.

### Phase 4: Post-Launch Optimization
Establish a continuous optimization loop: analyze user funnels, identify friction points, adjust mission difficulty and rewards, then re-test. This iterative approach ensures we're maximizing retention impact over time.

---

## Technical Architecture

<div align="center">

| **Component** | **Implementation** | **Details** |
|:--------------|:-------------------|:------------|
| **Map Integration** | Mapbox SDK | Flexible styling, real-time mission updates, smooth interactions |
| **Photo Verification** | Extended ML infrastructure | OCR for menu text, 3 retry attempts + manual fallback |
| **Location Services** | Native iOS/Android SDKs | Opt-in geolocation with privacy-first approach |
| **Merchant Dashboard** | Web portal | Track completions, manage coupons, real-time analytics |

</div>

---

## Edge Cases & Solutions

| Scenario | Solution |
|:---------|:---------|
| **Rural users with no nearby missions** | Offer "virtual missions" with online menus; show clear "No missions nearby" message |
| **Business closes or changes hours** | Google Business API auto-expires missions; users can report issues |
| **Photo verification fails** | Allow 3 attempts, then escalate to 24-hour manual review |
| **Notification overload concerns** | Make Local notifications toggleable (default off); target at-risk users only |
| **XP inflation worries** | Local XP counts toward personal goals only, not leaderboards |

---

## What This Demonstrates

This case study showcases **end-to-end product thinking**:

- ✓ Identifying a high-impact problem through data analysis
- ✓ Designing a solution grounded in user needs
- ✓ Planning a rigorous validation approach
- ✓ Defining technical requirements with feasibility in mind
- ✓ Anticipating operational challenges before launch
- ✓ Creating stakeholder-ready documentation

The result is a concrete proposal ready for engineering scoping and executive review.

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white" alt="Mapbox"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
</p>

**Interactive Prototype:** React, Tailwind CSS, Lucide Icons  
**Proposed Production:** Mapbox SDK, TensorFlow Lite, Native Mobile SDKs

---

<div align="center">

### 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jad-takieddin/)

---

*This is a conceptual case study created for portfolio purposes and is not affiliated with Duolingo.*

</div>
