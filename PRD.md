# Saga — Product requirements document

**Status:** Hackathon prototype  
**Tagline:** Make room for knowledge.  
**Product type:** Self-paced learning and discovery companion

## 1. Summary

Saga helps curious people make time for learning without turning it into homework. A user brings a question, practical goal or interest—or takes a quiz when they are not sure where to begin. Saga turns that curiosity into a welcoming, flexible path made of books, podcasts, articles, activities, games and people to follow. Users can dip in at their own pace, keep notes and save what they want to return to. Friends can share interests and discover topics in common.

Saga is educational, pluralistic and transparent about perspective. It gives people context and tools to form their own views; it does not tell them what to believe.

## 2. Problem

People in their late 20s and early 30s want to learn, revive hobbies and spend less time directionlessly scrolling, but often do not know where to start. Useful resources are scattered, overly academic, demanding or hard to assess. Busy people need accessible ways into a subject that do not require a course commitment or an uninterrupted weekend. They also want to retain a sense of independent curiosity in a world where feeds and AI can make passive consumption easy.

## 3. Audience and needs

**Primary audience:** Curious adults, initially people in their late 20s and early 30s, looking for accessible learning or a way back into personal interests.

Typical needs:
- “I want to learn about X, but I don’t know where to start.”
- “I miss having hobbies and interests of my own.”
- “I want a more useful alternative to doomscrolling.”
- “Help me understand enough to ask better questions and make my own decisions.”

Topics may be practical, intellectual or creative: finance, business, health literacy, political ideas, culture, photography, cycling and more.

## 4. Product principles

1. **Leisure, not homework:** self-paced, no deadlines, streaks or guilt.
2. **A friendly first step:** make broad or unfamiliar topics approachable, then offer optional depth.
3. **More than one way in:** use stories, practical material, audio, articles, games, offline activities and reflection where they fit.
4. **Pluralistic education:** separate evidence from interpretation, show relevant context and disagreement, and let users draw conclusions.
5. **Human-reviewed curation:** AI may assist research and drafting, but cannot publish unreviewed resources or curricula.
6. **Social by choice:** support sharing and discovery without making community participation necessary.
7. **Empowering language:** warm, clear and respectful; never infantilising or cutesy.

## 5. Core journey

1. **Discover:** browse themes and categories, search, continue a curriculum or take a quiz.
2. **Choose a theme:** select a specific question or interest, such as how political ideas shape popular culture, understanding hormonal health, finance or photography.
3. **Choose a pace:** select a bimonthly curriculum with 4 touchpoints or a quarterly curriculum with 7 touchpoints. Both cover the same core material at different depths and include optional prompts to go further.
4. **Explore:** start with a suggested resource or dip into the menu in any order.
5. **Reflect:** mark resources explored, keep private notes and see progress without a deadline.
6. **Continue or share:** celebrate completion, share with friends and receive an invitation to a related theme.

## 6. Requirements

### Discovery
- Provide two entry points: **Explore themes** for users with a topic in mind and **Take a quiz and find a theme** for users who want help choosing.
- The quiz narrows an interest into a specific, approachable theme.
- Provide categories, search, trending themes/resources, recommendations and save-for-later actions.

### Curricula and resources
- Offer only **Bimonthly curriculum — 4 touchpoints** and **Quarterly curriculum — 7 touchpoints**.
- Give each path a clear starting point, but make the rest explorable in any order.
- Include a relevant mix where suitable: a starting resource; two books (ideally one fiction/leisure read and one practical/contextual read); a podcast; an article; an activity or game; an optional prompt; and people to follow.
- Games and offline activities appear only when a good fit.
- Every resource has a distinct information page, clear type, purpose, time estimate and appropriate access buttons (for example bookshop/Kindle/audiobook, Spotify/Apple Podcasts/YouTube).
- Users can mark each resource explored, save resources and write private notes.
- Make progress visible, useful and non-competitive.

### Profiles and community
- Provide current curriculum, past curriculums, and saved resources/themes views.
- Let users share a public library, follow friends, browse their resources and save their topics.
- Show a profile match near the top, highlighting shared topics and explaining the overlap in plain language.
- Sharing is user-initiated; notes remain private.

### Contributor and editorial model
- AI can suggest topics, draft structures and find candidate sources.
- A human reviewer must approve published curricula/resources against Saga’s standards for evidence, source quality, accessibility, rights, conflicts and safety.
- Community members may apply as Saga ambassadors/curators; their curricula require platform approval before publication.
- Label sources, significant perspectives, uncertainty and sponsorship clearly. Do not accept undisclosed sponsorship.

### Health topics
- Health curricula provide general education and help users prepare questions for a qualified clinician.
- They may help users observe and record experiences such as energy, sleep or cycle patterns.
- They must not diagnose, prescribe, replace clinical care or treat tracking as proof of a condition.
- Use reputable, reviewable sources and state limits clearly.

## 7. Editorial standard

Prefer primary sources, established experts, reputable publishers, high-quality journalism and responsible expert newsletters (including Substack when appropriate). Assess expertise, evidence, conflicts, harmful claims and correction practices before recommending creators or social accounts. Do not recommend content solely because an algorithm or language model selected it. For contested themes, explain how viewpoints, history and culture relate; do not manufacture false balance. Explain why each resource is included and provide a way to flag concerns. Review content periodically.

## 8. MVP scope

**Hackathon prototype:** responsive discovery, categories and quiz; one example curriculum with two depths; differentiated resource cards and information pages; saved themes/resources; progress and notes; illustrative profile tabs, shared-topic match and resource filters; local browser storage.

**Out of scope for this prototype:** account creation, cross-device sync, production database, real friend search/following, messaging or moderation, production AI recommendations, community publishing workflow, payments, diagnosis or clinical advice. The current experience is a static demo; data stored in the browser does not sync across devices.

## 9. Success measures for a future pilot

- New visitors choosing a theme or completing the quiz.
- Visitors opening a curriculum and exploring at least one resource.
- Return-to-curriculum, completion, saves, notes and voluntary shares (without relying on streaks).
- Users’ reported confidence about where to begin and ability to make time for an interest.
- Editorial review coverage, user flags, correction time and representation of relevant perspectives.
- Accessible and usable experience across desktop and mobile.

## 10. Risks and mitigations

| Risk | Mitigation |
| --- | --- |
| Learning feels like more work | Short, flexible paths; optional depth; no deadline or streak. |
| AI returns poor or harmful resources | AI is assistive; humans review sources and published curricula. |
| Political content seems partisan or falsely neutral | State goals, label interpretations, cite sources and contextualise disagreement. |
| Health education is mistaken for medical advice | Expert review, clear limits and clinician-conversation framing; no diagnosis. |
| Social comparison discourages users | Optional profiles and sharing; no rankings or competitive scores. |
| Users assume prototype data syncs | Explain that the demo stores progress locally in the browser. |

## 11. Open questions

- Which themes and communities should Saga prioritise?
- What training, standards and support should approved curators receive?
- How should regional availability, language and accessibility variants work?
- What review cadence is appropriate for political and health curricula?
- What data is needed for real accounts, and what should remain private by default?
- What sustainable business model, if any, fits Saga’s principles?
