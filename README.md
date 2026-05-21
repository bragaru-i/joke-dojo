# Joke Dojo

> AI comedy practice — train your humor like a skill. Pick a style, set a goal, and get coached by AI through jokes, roasts, and improv.

📱 **[Download on App Store](https://apps.apple.com/us/app/joke-dojo-ai-comedy-practice/id6748906815)**

---

## What it is

Joke Dojo is a daily training app for people who want to get funnier — at work, on stage, on dates, or just in group chats. Unlike generic AI joke generators, it focuses on **practice and feedback**: the user picks the humor styles they want to master, sets goals, and works through AI-driven scenarios that score their wit and show them how to sharpen it.

- **Pick your style** — dark humor, dad jokes, puns and wordplay, satire, self-deprecating, corny, adult humor, and more
- **Set a humor goal** — what you want to get better at
- **AI-driven practice** — joke writing, roasts, improv scenes with conversational AI feedback
- **Iterate fast** — streaming responses keep practice sessions snappy

## My role

Lead engineer on a small team. Built the React Native app, the AI integration layer, and the App Store release flow alongside the team.

## Stack

| Layer        | Tech                                                                |
|--------------|---------------------------------------------------------------------|
| Mobile       | React Native, Expo, EAS Build                                       |
| Backend      | Node.js, Convex                                                     |
| AI           | OpenAI APIs — streaming responses, prompt-engineered comedy scenarios |
| Monetization | RevenueCat (subscriptions, in-app purchases)                        |
| Observability| Sentry, PostHog                                                     |
| Distribution | iOS App Store                                                       |

## Hard problems I worked on

- **Streaming OpenAI responses in React Native** — keeping the UI smooth while tokens stream, handling cancellation, and tuning inference cost so a free tier is viable
- **Prompt design for comedy** — getting models to give *useful* feedback on jokes (not vague "great!" responses) and to generate scenarios that actually challenge users
- **Style-conditioned generation** — switching humor registers (dark vs. dad vs. satire) reliably without breaking moderation
- **Free-tier economics** — letting users get real value before paywalling, while keeping per-user inference cost sustainable
- **App Store review for AI + comedy content** — moderation pipelines and category positioning to pass review

## Team context

Built at [English Nanny Intellectual Solutions](https://lovatar.org/#about-company), a Singapore-based studio. The team has shipped three iOS apps in ~12 months on a shared React Native + Convex foundation:

- **[Lovatar AI](https://apps.apple.com/us/app/lovatarai-ai-dating-chat/id6759549964)** — AI-powered dating
- **[Memes League](https://apps.apple.com/us/app/memes-league-card-battle/id6759237829)** — multiplayer card battle
- **Joke Dojo** — this app

---

## About me

Senior software engineer, 7+ years. React, React Native, Node.js, TypeScript.

📍 Georgia, EU work eligible · 🌐 Open to remote roles · 📬 bragaruion@gmail.com

[LinkedIn](https://linkedin.com/in/bragaru-ion) · [GitHub](https://github.com/bragaru-i)
