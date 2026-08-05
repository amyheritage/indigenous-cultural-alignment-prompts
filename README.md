# Indigenous Cultural Alignment

Reviews professional work against Indigenous cultural frameworks across six nations.

## The Problem

People writing policies, products and services that affect Indigenous communities usually want to get it right but cannot tell which frameworks apply to them. That uncertainty produces either delay or shallow engagement, and the gap gets found once the work is already public. The guidance exists, scattered across many sources and written for specialists.

## The Solution

A library of structured review prompts and a web app that runs them, covering Aotearoa New Zealand, Australia, Canada, Fiji, Samoa and Tonga. Each review returns observations, questions worth asking, and a confidence score, with every point traced back to a named source rather than asserted.

## How It Works

1. Pick your region and review type: public frameworks only, or those plus your organisation's own commitments.
2. Answer short intake questions on role, industry and region, then supply the work.
3. The review returns observations and provocations, with the reasoning and sources behind each one.
4. A confidence score marks where the review is least certain, so you know what a person needs to check.
5. Defined categories of sensitive community information are blocked before they reach the model.

Output is a starting point for engagement, not a substitute for it. It does not speak for any community.

## Tech Stack

`Anthropic Claude` `Next.js` `React` `TypeScript` `Node.js` `Tailwind CSS`

## Note

Portfolio project built to demonstrate my work. Not maintained for reuse or contribution.

---

## Running it locally

```bash
cd app
cp .env.example .env   # add your ANTHROPIC_API_KEY
npm install
npm run dev
```

The Anthropic key is used server-side only and is not exposed to the browser.
