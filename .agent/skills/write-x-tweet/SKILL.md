---
name: write-x-tweet
description: Writes concise, engaging X.com tweets with a clear call to action. Use when the user asks to create, improve, or research a tweet, including a topic, audience, product, event, or idea.
---

# Write X.com Tweets

## When to use this skill
- The user wants a short tweet for X.com.
- The user provides a topic, idea, product, event, or message.
- The user wants a more click-worthy, clear, or CTA-friendly tweet.
- The user wants a tweet researched before drafting.

## Core rules
- Ask for the topic before drafting unless the topic is already clear from the user's message.
- Keep the final tweet at or below 280 characters, including spaces and URLs.
- Make the first sentence the strongest hook.
- Lead with a concrete benefit, curiosity gap, surprising fact, question, or clear problem.
- Use one clear idea and one primary CTA.
- Use plain language, active voice, and natural punctuation.
- Avoid clickbait, fake urgency, false statistics, exaggerated claims, spammy repetition, and misleading links.
- Prefer specific, verifiable claims over vague hype.
- Do not invent facts, citations, names, dates, quotes, or current events.
- Use an X.com-appropriate tone: direct, readable, and conversational.
- If a result needs a URL, count it as the URL's actual length and keep the remaining copy concise.

## Required workflow

### 1. Clarify the topic
Ask the user for the topic and, when useful, the intended audience, tone, and desired action. Keep the question short.

If the topic is missing, ask:

> What topic, idea, product, or event should the tweet cover?

If the user gives only a broad subject, ask one focused follow-up question before researching. Do not guess.

### 2. Research deeply
Research the topic using available web search tools and authoritative sources. Do not rely on a single source.

Check:
- The latest relevant public information and context.
- The topic's core claim and what makes it meaningful.
- Common questions, misconceptions, and pain points in the audience.
- Reliable examples, statistics, or quotes that can be verified.
- Whether the wording is accurate, current, and appropriate for the intended audience.
- Whether a link is useful and trustworthy.

Use current sources when the topic is time-sensitive. If the sources conflict, state the uncertainty and avoid presenting an unverified claim as fact. If no reliable source is available, write from the user's provided information and label any uncertain wording as a question or opinion.

### 3. Create the positioning
Before writing, identify:
- The audience.
- The problem or opportunity.
- The strongest verified insight.
- The one action the reader should take.
- The shortest compelling opening line.

### 4. Draft and optimize
Draft no more than 280 characters. Then improve it with this checklist:

- Does the opening create immediate interest?
- Is the main message understandable in one read?
- Is the claim specific and verifiable?
- Is the CTA clear and realistic?
- Does the phrase sound natural on X.com?
- Is there any unnecessary or repetitive wording?
- Would a reader understand why the post matters?

Use a direct CTA when appropriate, such as:
- Read more: "Read the full breakdown: [link]"
- Start now: "Try it today: [link]"
- Join the conversation: "What do you think?"
- Get the details: "Get the details: [link]"
- Share your view: "Share your take below."

Avoid vague CTAs such as "learn more" unless the surrounding copy makes the next step obvious.

### 5. Validate
Validate the final result before presenting it:

- Count the characters with the exact final text.
- Confirm that every factual claim is supported by the research.
- Confirm that no misleading or deceptive language was introduced.
- Confirm that the link is relevant and safe.
- Confirm that the tweet contains one clear CTA.
- If it exceeds 280 characters, shorten it until it fits.
- If the topic is sensitive, avoid sensationalism and use neutral wording.

## Output format
Return the result in this exact structure:

### Tweet
[Final tweet only]

### Research summary
- [Key verified finding]
- [Audience or context]
- [Important caveat or uncertainty]

### Character count
[Number of characters]

### CTA
[Primary action the reader should take]

If the user asks for multiple options, provide up to three versions with the same research summary and label them as: "Option 1: Hook-led," "Option 2: Question-led," and "Option 3: Benefit-led."

## Example

User: "Write a tweet about a productivity app update."

Research: Verify the update, its user benefit, and the current release details.

Tweet: "Want to see what changed in our productivity app? Read the update: [link]"

## Validation checklist

- [ ] Topic and audience are confirmed.
- [ ] Relevant sources were checked.
- [ ] Claims were verified.
- [ ] The opening is strong and clear.
- [ ] The message has one primary idea.
- [ ] The CTA is clear and realistic.
- [ ] The tweet is no more than 280 characters.
- [ ] The wording is honest, current, and non-deceptive.
