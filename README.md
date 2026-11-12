# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `trend-scout`

Finds what your product's audience is talking about right now and turns it into content ideas you can make this week. Every idea comes with the source it was found in and the date, so nothing is "trending" just because an AI said so.

Most "what should I post" tools hand you a list of generic ideas. This one starts from where good content actually comes from: questions your audience keeps asking, and moments they already care about. It then throws out anything that doesn't honestly fit your product.

**How it works**

1. **Ask first.** Your product, who it's for, where they live, and the channels you post on.
2. **Search two ways.**
   - **Questions:** what your audience keeps asking, in their own words. These ideas stay useful for months.
   - **Moments:** the calendar for the next four weeks, recent news in your topic, current post formats, and what similar products are doing.
3. **Filter.** An idea is dropped if it fails any of five checks:

| Check | What it means |
|---|---|
| Fit | The product is a natural part of the post, not an ad stapled to a meme |
| Fresh | Live ideas are dated within the last 30 days |
| Safe | Nothing a student would regret having on a public account |
| Rights | Borrow the format, not someone else's video, character or music |
| Doable | You can make it this week with what you have |

4. **Trend cards.** Five cards, ranked. Each one has what's happening, the source and date, why your audience cares, your angle, what to make, a hook, and what you need to supply.

It also tells you its top pick and one idea it rejected, with the reason. Seeing what got cut teaches the filter faster than a rule does.

**In class**

Give it several teams at once and it returns three cards per team, short enough to put on screen. Cards hand off to [ig-poster-studio](https://github.com/BuiltYoung/ig-poster-studio) for posters and [build-in-public](https://github.com/BuiltYoung/build-in-public) for founder posts.

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/trend-scout.git ~/.claude/skills/trend-scout
```

Restart Claude Code. The skill loads automatically when you ask what to post or want content ideas for a product.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `trend-scout` folder.

Trend Scout works best with web search turned on. Without it, the skill says so and works from the school calendar and posts you bring in.

---

## Using it

Describe your product and ask. No command needed:

> *"We built an app that turns photos of class notes into quizzes, for Grade 11 students in Ontario. We post on Instagram and TikTok. What should we post this week?"*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
