# Day 28 — pin these repositories

Profile pins are a GitHub website setting. The account owner has to save them. This repository change does not pin anything.

GitHub's GraphQL API can **read** `pinnedItems` on a user profile. It does not provide a supported mutation to pin or reorder those repositories. Do not add a script, Action, or unofficial pin call for this. Use **Customize your pins** below.

Official steps: [Pinning items to your profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/pinning-items-to-your-profile).

## Where to click

1. Sign in as **Birra3324**.
2. Open [github.com/Birra3324](https://github.com/Birra3324) (profile picture → **Your profile**).
3. At the top of the **Pinned** section — it may still be labeled **Popular repositories** — click **Customize your pins**.
4. Next to **Show**, leave **Repositories** selected. You do not need gists.
5. Select the repositories in the table, drag them into that order, and click **Save pins**.

GitHub allows six pins. These four portfolio repositories are the pin set. Leave the other slots empty.

## Pin in this order

| Order | Repository | What a visitor should see |
| --- | --- | --- |
| 1 | [ai-intake-demo](https://github.com/Birra3324/ai-intake-demo) | FastAPI intake validation, optional LLM, SQL, n8n routing, CI |
| 2 | [customer-operations-agent](https://github.com/Birra3324/customer-operations-agent) | FastAPI ops agent, mock KB/CRM/Slack tools, handoff UI, n8n bridge |
| 3 | [company-rag-assistant](https://github.com/Birra3324/company-rag-assistant) | Local knowledge assistant, hybrid retrieval, extractive answers, offline eval |
| 4 | [visionmusicapp](https://github.com/Birra3324/visionmusicapp) | Flutter listener; live at [www.visionmusic.et](https://www.visionmusic.et); built under Vision Entertainment LLC ([vision-ent.com](https://vision-ent.com/)), which ended mid-2026 |

## Slots five and six

Leave them empty.

[visionmusic-site](https://github.com/Birra3324/visionmusic-site) is public and is not part of this pin list. [Birra3324](https://github.com/Birra3324/Birra3324) is this profile README. It already renders above the pins, so pinning it does not add a project.

Do not pin private repositories.

## What is pinned today

Checked on 2026-09-24 with a public `pinnedItems` read (three pins):

1. ai-intake-demo
2. company-rag-assistant
3. visionmusicapp

After **Save pins**, the order should be ai-intake-demo, customer-operations-agent, company-rag-assistant, visionmusicapp.

## Check

Open https://github.com/Birra3324 in a private window. Confirm those four titles, in that order, and confirm no private repository is pinned or linked from the profile README.
