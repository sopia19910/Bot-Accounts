# Bot Accounts

**In Whose Name Does an AI Act?**

*Starting from the familiar device of the account, this book examines the identity and memory of AI, its work and delegation, its permissions and responsibility.*

- Author: **Ha Woo Sung (Ryo Ha)** — sopia19910@gmail.com
- Date: October 28, 2026
- Books in this repository:
  - 📄 [English — Bot Accounts](%5BEN%7D%20Bot%20Accounts.pdf)
  - 📄 [한국어 — Bot Accounts](%5BKR%7D%20Bot%20Accounts.pdf)

---

> **Before we settle what an AI is inside, we must be able to explain within what relationships the work we entrust to it is carried out.**

A program that answers a question is judged by the quality of its answer. A bot that reads your files, resumes last week's work and reaches into other services needs more than that. *Which bot is acting now? Whose request is it carrying out? How far into my data may it look? If I stop it, do its pending requests stop too?*

This book proposes the **bot account** as the concept for managing those relationships. It is not completed by a human-like voice, a distinctive name or a long conversation history. A criterion for identifying the bot must be set, and to that identity must be linked an **operator**, **permissions**, **work** and a **record of activity** — not by putting everything into one database, but by making relationships scattered across many systems verifiable.

## Why Start from Accounts

Names, identifiers, authenticators and accounts are easy to blur at a login screen, but they answer different questions:

| Concept | What it does |
|---|---|
| **Name** | lets people call and remember a counterpart; need not be unique |
| **Identifier** | distinguishes an object *within a defined scope* (a number means nothing without its issuing system) |
| **Authentication** | confirms the party controls an authenticator linked to the claimed identity |
| **Authorisation** | decides whether a particular action is permitted — a separate judgement from authentication |
| **Account** | the unit by which a system distinguishes a counterpart, links its information and access relationships, and manages the state of that relationship |

The book reads four institutions side by side — state registration, bank accounts, internet services and bot operating systems — to find their shared questions of identification, record-keeping and relationship management, while insisting that their legal status is **not** the same.

## The Minimum Structure of a Bot Account

The core proposal (Chapter 21) — a starting point for design, not an established standard:

- **Identity** — a distinguishable identifier and an account state
- **Operating relationship** — operator, purpose, reviewer
- **Permissions & approvals** — target, action, conditions; changes and withdrawal
- **Tasks & runs** — what remains, why it is waiting, what action comes next
- **Memory & common context** — sources, decisions, the currently valid version
- **Activity & result records** — request, policy decision, tool call, actual external result
- **Budget & resource ledger** — optional, linked as the work requires

Records are linked, not copied: `account → task → run → event` relate one-to-many, while grants and context versions are referenced by many runs. Raw secret keys stay out of this structure entirely.

### Design principles

- **A model's proposal never becomes execution authority by itself.** Understanding a goal well and being permitted to pay are evaluated separately.
- **Permission checks apply even to reads**, not only to external actions.
- **Credentials are separated from model input** — not stuffed into a long prompt.
- **Failure leaves a state to check**, never overwritten as complete.
- **Start small:** first make one piece of work explainable end to end, then extend approval, result-confirmation and recovery as purchases or external contact are added.

## What the Book Does Not Claim

- That an account makes an AI a person. Being the subject of an identification scheme and having personhood are separate matters.
- That technical attribution settles legal responsibility. Linking an action to an identity and a run is distinct from judging who is legally responsible under the applicable law and facts.

It asks instead that we not confuse **the technically distinguishable subject**, **the unit responsible for work** and **the party whose legal responsibility is to be judged**.

## Contents

| Part | Chapters |
|---|---|
| **I. The Human World, Read through Accounts** | names, numbers and accounts · how the state registers people · how banks record money · who I am after logging in |
| **II. The Moment an AI Needs an Account** | from AI that answers to AI that acts · model, bot, account · is yesterday's bot the same as today's? · birth and end of a bot account |
| **III. How Memory Becomes Work** | what a bot should remember · working together through a common context · where unfinished work remains · how bots recognise one another |
| **IV. In Whose Name, and How Far** | those who build, operate and commission a bot · entrusting a goal vs granting authority · proving what a bot did · where responsibility goes |
| **V. Work and the Economy with Bot Accounts** | bots individuals keep · how organisations take bots in · when a bot spends money · who keeps the door of a bot account |
| **VI. Questions for Designing a Society of Bot Accounts** | the minimum structure · hijacked or vanished accounts · does an account create a person? · what should we entrust to AI? |

A fictional publishing house runs through the chapters: an editor assigns a research bot and an editing bot that may share one language model yet differ in what they may read, what they are assigned and who approves their results. The case is constructed for explanation and does not represent any real company.

## Sources Consulted

The book grounds its distinctions in existing standards and law, including NIST digital identity guidance, SCIM (RFC 7643), OAuth 2.0 (RFC 6749), W3C DID Core, W3C PROV, the A2A agent protocol and ISO 13616-1. Laws and standards describe distinctions that already exist; the bot-account structure built by connecting them is the book's own thesis.

## License

Released under the [MIT License](LICENSE).

---

*The relationship must remain changeable: one must be able to entrust new work, correct wrong memories, reduce permissions and, if necessary, stop or move to another service. Gaining convenience is no reason to lose the ability to correct and to object.*
