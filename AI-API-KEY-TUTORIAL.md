# How to Use an AI API Key in RADEQuiz
### Sr.AI'so (AI Accounts Expert) — Complete Tutorial

Sr.AI'so is the app's AI companion — it answers Railway Accounts questions,
explains answers and clears your doubts. This tutorial shows you how to add
your own **API key** so you can get answers from the AI provider of your
choice (OpenAI / Gemini / Groq / GitHub AI).

---

## 1. It works without a key too

The app starts with **Free AI** already enabled. **No key is needed** for it —
just start chatting with Sr.AI'so. If Free AI is enough for you, you don't
need to read further!

Add a key only if you want faster / better answers, or prefer using your own
AI account.

---

## 2. Which AI providers are available?

| AI | Key required? | Cost | Where to get the key |
|----|---------------|------|----------------------|
| **Free AI** | No | Completely free | Nothing to do |
| **Gemini** (Google) | Yes | Free tier included | [aistudio.google.com](https://aistudio.google.com) |
| **Groq** | Yes | Free tier included | [console.groq.com](https://console.groq.com) |
| **GitHub AI** (GitHub Models) | Yes | Free tier included | [github.com/settings/tokens](https://github.com/settings/tokens) |
| **OpenAI** | Yes | Paid | [platform.openai.com](https://platform.openai.com) |

> **Recommendation for new users:** Try **Gemini**, **Groq** or **GitHub AI**
> first — all three offer a free tier and the key is easy to create.

---

## 3. How to create an API key (step-by-step)

### Gemini (Google) — Free
1. Open **aistudio.google.com** on your mobile or computer.
2. **Sign in** with your Google account.
3. Tap **"Get API Key"** → **"Create API key"**.
4. **Copy** the long key shown (looks like `AIza...`).
5. Note it down somewhere safe — the full key won't be shown again.

### Groq — Free
1. Open **console.groq.com**.
2. **Sign up / Log in** with Google or GitHub.
3. Go to **"API Keys"** in the left menu → **"Create API Key"**.
4. Copy the key — it starts with `gsk_`.

### GitHub AI (GitHub Models) — Free
1. Open **github.com** and sign in (create a free account if needed).
2. Go to **Settings** → **Developer settings** → **Personal access tokens**
   → **Fine-grained tokens** → **"Generate new token"**.
3. Under **Account permissions**, find **"Models"** and set it to
   **Read-only**, then **Generate token**.
4. Copy the token — it starts with `github_pat_`.

### OpenAI — Paid
1. Open **platform.openai.com**.
2. Create an account and add a payment method under **Billing** (the key
   won't work without it).
3. Go to **API Keys** → **"Create new secret key"** → copy the key.
4. The key starts with `sk-`.

> **Important:** An API key is like a password — never share it with anyone,
> don't send it in screenshots, and don't paste it in public places.

---

## 4. How to add the key in the app

1. Open the RADEQuiz app.
2. Tap the round **Sr.AI'so button (FAB)** at the bottom-right — the AI chat opens.
3. Tap the **🔑 (key)** button in the chat header — the **"AI API Keys"** sheet opens.
4. Under **"Select AI"**, choose your provider (OpenAI / Gemini / Groq / GitHub AI).
   - If you select **Free AI**, no key is needed — the field stays disabled.
5. **Paste** your key into the key box.
   - The hint tells you the format: `sk-...` for OpenAI, AI Studio key for
     Gemini, `gsk_...` for Groq, `github_pat_...` for GitHub AI.
6. Press **Save**. Done! Sr.AI'so will now answer using your provider.

**Shortcut to recognise keys:** keys starting with `sk-` belong to OpenAI,
keys starting with `gsk_` belong to Groq, and keys starting with
`github_pat_` belong to GitHub AI.

---

## 5. Who will answer? (Fallback order)

If you selected a provider, Sr.AI'so tries them in this order:

1. **Your selected provider** (if its key is saved)
2. **Gemini** (if its key is saved)
3. **Groq** (if its key is saved)
4. **GitHub AI** (if its token is saved)
5. **Free AI** (always the backup — you never get an empty reply)

Every answer shows a **"Powered by ..."** badge telling you which AI replied.
If one provider fails (e.g. quota exhausted), Sr.AI'so automatically moves to
the next one — you don't have to do anything.

> **Note:** If you selected **Free AI**, only Free AI is used — no fallback runs.

---

## 6. Token usage & daily limit (💲 button)

Tapping the **💲** button in the chat header shows:

- Usage in the **last 24 hours**
- **Total** usage
- **Daily limit** — you can set a per-provider daily cap yourself
  (shown with Remaining + progress bar)

Setting a daily limit protects your paid quota from running out suddenly.
Once the limit is reached, that provider is skipped for the day and the
fallback takes over.

---

## 7. Privacy — your key is safe

- Your key is stored **only on your phone** (in the app's private storage).
- The key is **never uploaded anywhere** — not to any server, not to any
  other device.
- The app sends the key only to the AI provider you selected, just to fetch
  the answer. It goes nowhere else.

---

## 8. Troubleshooting

| Problem | Cause / Fix |
|---------|-------------|
| "Invalid key" / no answer | Key was pasted incorrectly — copy-paste the full key again, with no extra spaces |
| It worked before, not now | The provider's free quota may be over — create a new key or try another provider |
| "Daily limit reached" | Raise the limit under 💲 or wait till tomorrow; Free AI still works via fallback |
| Key won't save | Did you select the right provider? The key field stays disabled for Free AI — that's normal |
| OpenAI key doesn't work | Is a payment method added under Billing? OpenAI keys don't work without balance |

---

## 9. Quick FAQ

**Q. Do all features work without a key?**
Yes — chat, answer explanations, and the doubt box all work on Free AI.

**Q. Can I save more than one key?**
Yes — you can save keys for all four providers at once. The fallback order
picks the best available one.

**Q. How do I change or remove a key?**
Reopen the 🔑 sheet, paste the new key and press Save. To remove, clear the
field and press Save.

**Q. Will my key work on another phone?**
The key belongs to your account, not your phone — you'll need to paste it
again in the app on the other phone. One key can be used in multiple places.

**Q. Worried about charges?**
Gemini, Groq and GitHub AI free tiers cost nothing. Only OpenAI is paid — do set a 💲
daily limit for it.

---

*This tutorial is for the RADEQuiz app. Steps may change slightly as the app
is updated.*
