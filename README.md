# InsightfulPipe Email Marketing Skills

**20 free Claude skills for email marketing: lifecycle strategy, welcome, nurture and win-back sequences, deliverability, list cleaning, RFM segments, newsletters and Klaviyo flow audits.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/email-marketing-skills
/plugin install insightfulpipe-email-marketing@insightfulpipe-email-marketing
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/email-marketing-skills
```

Add `--skill email-deliverability-auditor` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (20)

| Skill | What it does | |
|---|---|---|
| [Churn Risk and Win-back Planner](skills/churn-risk-winback-planner/) | Finds lapsed and at-risk customers from Shopify, WooCommerce, Magento or BigQuery orders by each product line's repurchase gap, then plans margin-capped win-back… |  |
| [Competitor Email Teardown](skills/competitor-email-teardown/) | Benchmarks rival email programs from inbox exports, measuring welcome speed, frequency, signup offers, discounts, subject lines and sale timing against your Klaviyo or… |  |
| [Customer Retention Cohort Analyst](skills/retention-cohort-analyst/) | Builds customer retention cohorts from Shopify, WooCommerce, Magento or subscription orders, with repeat rate, days to second order and refill reminder delays. |  |
| [Email Campaign Analyst](skills/email-campaign-analyst/) | Analyses Klaviyo or Mailchimp email campaigns for clicks, revenue, deliverability, subject lines, send times and list growth, with a monthly report. |  |
| [Email Deliverability Auditor](skills/email-deliverability-auditor/) | Audits email deliverability, checking SPF, DKIM and DMARC alignment, Gmail, Yahoo and Microsoft bulk-sender rules, and bounces and complaints by mailbox provider, then… |  |
| [Email Lifecycle Strategy](skills/email-lifecycle-strategy/) | Writes an email and lifecycle marketing strategy, setting customer stages from Shopify or WooCommerce reorder gaps, mapping Klaviyo or Mailchimp flows, SMS, push and… | [Page](https://insightfulpipe.com/marketing-claude-skills/email/email-lifecycle-strategy) |
| [Email List Cleaner](skills/email-list-cleaner/) | Cleans an email contact CSV, Excel file or Google Sheet before import, flagging bad syntax, duplicates, typo and throwaway domains, dead mail servers, role addresses… |  |
| [Email List Growth Optimizer](skills/email-list-growth-optimizer/) | Grades every popup, flyout, embedded form and checkout opt-in on sign-ups per 1,000 sessions from Klaviyo or Mailchimp, GA4 and Shopify data, then writes paste-ready… |  |
| [Email Marketing Calendar and Send Frequency Planner](skills/email-campaign-calendar/) | Plans a quarter of Klaviyo or Mailchimp email broadcasts, setting send frequency per engagement tier from the list's own unsubscribes, complaints and revenue, then… |  |
| [Email Platform Setup and Migration Planner](skills/email-platform-setup-migration/) | Plans an email platform migration such as Mailchimp to Klaviyo, or a first setup, with inventory, field and consent mapping, suppressions imported first, store event… |  |
| [Email Send Check](skills/email-send-check/) | Proofs a finished Klaviyo or Mailchimp campaign or flow email before it sends, checking links, UTM tags against GA4, merge tag fallbacks, alt text, Gmail clipping… |  |
| [Email Sequence Builder](skills/email-sequence-builder/) | Plans and writes Klaviyo or Mailchimp email sequences and flows, from welcome, onboarding and nurture to abandoned cart, winback, back in stock and replenishment, plus… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/email-sequence-builder) |
| [HTML Email Template Builder](skills/html-email-template-builder/) | Codes responsive HTML email templates for Gmail, Outlook, Apple Mail and dark mode from copy, a design or a broken email, with plain text and a 15-point check, saved to… |  |
| [Klaviyo Flow Auditor](skills/klaviyo-flow-auditor/) | Audits Klaviyo and Mailchimp flows for missing or weak automations, unengaged profiles and abandoned cart recovery measured from Shopify orders. | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/klaviyo-flow-auditor) |
| [Loyalty and VIP Program Designer](skills/loyalty-vip-program-designer/) | Designs or reviews a points and VIP tier loyalty program from Shopify, WooCommerce or Magento orders, placing tiers on real spend, sizing rewards to gross margin and… |  |
| [Newsletter](skills/newsletter/) | Writes email newsletter issues from your published posts, GA4 or Search Console traffic and past Klaviyo or Mailchimp clicks, with subject lines and preview text. | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/newsletter) |
| [Push Notification and In-App Message Planner](skills/push-inapp-message-planner/) | Plans push notifications and in-app messages for iOS, Android and web, setting the permission ask, caps from the app's opt-outs, quiet hours and copy, using GA4 and App… |  |
| [RFM Analysis and Segmentation](skills/customer-segmentation-rfm/) | Scores every buyer by RFM from Shopify, WooCommerce, Magento, BigQuery or CSV orders, names segments with revenue shares, and sets each segment's offer and email… |  |
| [SMS and WhatsApp Marketing Planner](skills/sms-whatsapp-planner/) | Plans SMS and WhatsApp marketing for Klaviyo or any SMS platform, picks text or email per moment, writes opt-ins and every text with segment counts and cost per send… |  |
| [Subscription Cancel Flow and Dunning Planner](skills/cancel-flow-dunning-planner/) | Plans subscription cancel flows and dunning from Stripe, Chargebee, Paddle or Recharge exports, splitting churn into cancellations and failed payments, and writes save… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
