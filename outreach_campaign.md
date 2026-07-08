# Personalised Outreach Campaign

**Domain:** GTM AI Engineering
**Who this goes to:** people at US GTM AI startups (founders, CTOs, heads of AI, founding engineers, and RevOps or growth leads). Series A to C for role or contract work, seed kept for small project work.
**Goal:** start a real conversation that leads to contract work or a role helping keep their AI agents reliable.
**Channel:** email through SBL, with a LinkedIn note as a backup touch.
**Date:** 06 July 2026

## The one idea behind this campaign

Keep the cold message general and human, because the person on the other end could be anyone in this space and you cannot guess their situation up front. Do not lead with a project or artifact, and do not claim work that does not exist yet. The message introduces who you are and opens a low-friction conversation, nothing more.

The real personalisation is reactive. It happens after someone replies, using two inputs: the tone of their reply (sentiment) and true facts from their LinkedIn profile. That is where to tailor the response to the specific person and, only then, offer something relevant to them. This keeps every cold message honest and broad, and saves the effort of personalising for people who never respond.

Everything is written to read like a person typed it. Short. No filler, no "I hope this finds you well," no long paragraphs.

---

## Message sequence: Technical Founders

The same four messages work across the whole domain. Only the personalisation fields change per person. If a field is empty, the line is dropped, not faked.

### Message 1 - Initial (Day 0)

**Subject:** quick thing about {company}'s agents

> Hi {first_name},
>
> Noticed {company} {trigger}.
>
> I work on the unglamorous side of AI agents: keeping them working in production. Evals, monitoring, cost, the stuff that quietly breaks after the demo.
>
> If keeping agents reliable is on your radar, happy to trade notes for 15 minutes. Or I can send a bit more about how I work. Whichever suits.
>
> Thanks,
> {your_name}

### Follow-up 1 (Day 3, same thread, no new subject)

> Hi {first_name},
>
> One thing I see a lot: an agent works fine, then a model swap or a data change quietly doubles the cost or tanks the quality, with no alert.
>
> Preventing exactly that is my wheelhouse. Happy to share how I'd set it up if it helps.
>
> {your_name}

### Follow-up 2 (Day 7, same thread)

> Hi {first_name},
>
> I help teams get AI from idea to something running in production, and keep it solid once it's there. Building the thing and making it last are the same job to me.
>
> If that's useful for what you're working on, glad to talk.
>
> {your_name}

### Follow-up 3 (Day 12, same thread)

> Hi {first_name},
>
> Last note from me, I don't want to crowd your inbox.
>
> If agent reliability or evals become a priority later, just reply "later" and I'll check back in a few months. If it's not a fit, no problem at all.
>
> Thanks for your time,
> {your_name}

---

## Message sequence: Non-Technical Founders

### Message 1 - Initial (Day 0)

**Subject:** quick thing about {company}'s agents

> Hi {first_name},
>
> Noticed {company} {trigger}.
>
> I work on the unglamorous side of AI: making sure it actually works once it's live, not just in the demo. Keeping it reliable, watching it so it doesn't quietly break, and stopping it from running up costs.
>
> I help teams get their AI from "works in the demo" to "works every day," without it breaking quietly or burning budget.
>
> No pitch. Just offering to help.
>
> Thanks,
> {your_name}

### Follow-up 1 (Day 3, same thread, no new subject)

> Hi {first_name},
>
> One thing I see a lot: a team gets AI working, it looks great at first, then it quietly stops doing its job and nobody catches it until results slip.
>
> Making sure that doesn't happen is most of what I do. Happy to have a quick chat if it's useful.
>
> {your_name}

### Follow-up 2 (Day 7, same thread)

> Hi {first_name},
>
> I help teams get AI from idea to something running in production, and keep it solid once it's there. Building the thing and making it last are the same job to me.
>
> If that's useful for what you're working on, glad to talk.
>
> {your_name}

### Follow-up 3 (Day 12, same thread)

> Hi {first_name},
>
> Last note from me, I don't want to crowd your inbox.
>
> If agent reliability or evals become a priority later, just reply "later" and I'll check back in a few months. If it's not a fit, no problem at all.
>
> Thanks for your time,
> {your_name}

---

## Personalisation fields

The cold sequence uses only a few light, safe fields. Deep personalisation is not done in the cold message; it happens at the reply stage from the reply itself and the person's LinkedIn.

| Field | What it is | Fallback if empty |
|---|---|---|
| `{first_name}` | Recipient's first name | "Hi there," |
| `{company}` | Company name | drop the company reference, keep the sentence general |
| `{trigger}` | Optional, only if true (e.g. "just raised your Series A", "just shipped {product}", "is hiring") | drop the sentence entirely |
| `{your_name}` | Sender name | required |

Note: `{product}`, `{observation}`, and any artifact or benchmark link are not used in the cold messages. They belong to the reply stage, once you know who the person is.

## Which track to send

Two full sequences. Pick the track per contact from one simple read at send time:

- **Technical track** if the title or company signals it: CTO, Head of AI, founding engineer, ML lead, or an engineer-turned-founder.
- **Non-technical track** for everyone else: non-technical founder, RevOps or growth lead, operator, or anyone whose background is not engineering.

If you cannot tell, default to the non-technical track. It reads fine to a technical person, whereas the technical one can lose a non-technical reader.

## Reply personalisation (the part that does the real work)

When someone replies, craft the response from two inputs.

1. **Sentiment of their reply.** Read whether it is positive, neutral, or negative, and match your tone and next step to it. A warm reply gets a warm, specific next step. A lukewarm reply gets a lighter touch. A negative reply gets a polite exit.
2. **Facts from their LinkedIn profile.** Pull one or two true things to tap on: their role, background, company stage, or a recent post. This is where the message gets personal, using real facts rather than guesses.

Then tailor the response to who they actually are:

- **Engineer turned founder:** talk shop. Offer to look at their setup or share a relevant piece of technical work.
- **Founder with no tech background:** skip the jargon. Talk in outcomes (ship faster, fewer things breaking, lower cost) and offer a short call.
- **Recruiter working a candidate ICP:** position yourself as the candidate. Offer your CV or a short portfolio and state how you fit the roles they place.
- **Anyone else:** ask one simple question to learn what they need before pitching anything.

Only at this point do you share a specific piece of work, because now it can be relevant. If you do not have one that fits yet, offer to put a short one together for their specific case.

## Campaign rationale

**Why two tracks, both general.** The prospect set is unpredictable, so each track stays broad within its audience rather than tailored to one company. The technical track speaks to people who own the agents; the non-technical track speaks in outcomes. Both let the person self-identify, and the real tailoring waits for the reply.

**Why the recipient has a reason to reply.** Message 1 makes one easy choice (a quick chat, or send more), not a hard commitment. Each follow-up adds a bit more, a concrete failure they recognise, then how you think about building and keeping AI solid, so there is a reason to open the next one.

**Fields used in the cold message.** first_name, company, and an optional true trigger. Nothing that pretends to know the person. The knowing happens after they reply.

**Expected reply rate and the basis for it.** Estimate: 5 to 9 percent any reply, 2 to 4 percent positive, across the four messages. A general message replies a bit lower than a tightly personalised one. Basis: plain cold email lands 1 to 5 percent positive; a clean sequence to a focused domain lifts that, while general wording caps the top. The design trades cold-message sharpness for coverage, and makes it back by personalising hard at the reply stage. Replace this with real numbers after the first 100 sends.

### What counts as each response type

- **Positive:** asks for a chat, asks what you do, asks for your work or CV, forwards it internally, replies "send it".
- **Neutral:** "not now", "check back later", a like or acknowledgement with no action, or an out-of-office.
- **Negative:** a clear no, "stop", an unsubscribe, or an annoyed reply.

### What changes if it underperforms (under 5 percent any reply after 100 sends)

Change one thing at a time:

1. The subject line and first line, since they drive opens.
2. Add one light, true trigger to Message 1 so it feels less cold, without faking it.
3. Tighten who receives each track (for example, only founders and hiring managers).
4. Send timing.

Also lean harder on the reply-stage personalisation, since converting the replies you get matters more than squeezing the cold rate.

## SBL configuration

SBL sources the leads, so no separate list is needed.

**Messaging and personalisation.** Load both tracks as two sequences. Tag each contact technical or non-technical on import, and route to the matching track. Map the light fields and set fallbacks so nothing sends with a blank tag. Turn on the rule that drops a sentence when its field is empty.

**Follow-up sequence.** Message 1 on day 0, Follow-up 1 on day 3, Follow-up 2 on day 7, Follow-up 3 on day 12. All follow-ups send in the same thread, no new subject. Keep a contact on one track for the whole thread so it reads like one person.

**Sending schedule and settings.** Send Tuesday to Thursday, in the recipient's mid-morning (US Eastern or Pacific by their location, which is evening in India). Cap at 20 to 30 emails per day per sending address while the domain warms, then raise slowly. Spread sends across the hour. Use a verified sending domain with SPF, DKIM, and DMARC set up.

**Stop conditions.** Stop the sequence the moment a contact replies, books a meeting, opts out, or hard bounces. Stop automatically after Message 4 if there is no reply. Never re-add anyone who opted out.

### Reply handling

- On any reply, pause the sequence and route to the reply step: read the sentiment, pull one or two LinkedIn facts, identify the prospect type, and craft the tailored response for you to review before sending.
- **Positive:** respond personally within a few hours with a specific next step, and a relevant piece of work if you have one.
- **Neutral:** tag "later", stop the sequence, and set a reminder to check back in about three months.
- **Negative:** honour it at once, remove them from the list, and do not contact again.

## Safety checklist (read before launch)

- Read all messages in both tracks once more before turning the campaign on.
- Do not claim work that does not exist. The cold messages describe what you do and can do, not a track record you have not built. No artifact or benchmark link is in the cold sequence, so nothing is a bluff.
- Only share a specific piece of work once someone replies and it is genuinely relevant. If you do not have one yet, offer to build a short one for their case rather than linking something empty.
- Follow the rules: include your real name and a physical mailing address, and a clear opt-out in every email (CAN-SPAM). For contacts in the EU or UK, make sure you have a lawful basis to email them (GDPR). Honour every opt-out straight away.
- Never invent a personalisation fact, in the cold message or the reply. Use only true details from the reply and the person's public profile.
