# RADEQuiz me AI API Key kaise use karein
### Sr.AI'so (AI Accounts Expert) — poora tutorial

Sr.AI'so app ka AI dost hai — Railway Accounts ke sawalon ke jawab deta hai,
answer explain karta hai aur doubt clear karta hai. Ye tutorial batayega ki
apni **API key** kaise lagayein taaki aap apne pasand ke AI provider
(OpenAI / Gemini / Groq) se jawab pa sakein.

---

## 1. Bina key ke bhi chalta hai

App kholte hi **Free AI** pehle se chalu hota hai. Iske liye **koi key nahi
chahiye** — bas Sr.AI'so se baat karna shuru kar do. Agar aapko Free AI se
kaam chal raha hai to aage padhne ki zaroorat nahi!

Key sirf tab lagayein jab aap tez / behtar jawab chahte ho, ya apna khud ka
AI account use karna chahte ho.

---

## 2. Kaun-kaun se AI provider hain?

| AI | Key zaroori? | Kharach | Key kahan se milegi |
|----|--------------|---------|---------------------|
| **Free AI** | Nahi | Bilkul free | Kuch nahi karna |
| **Gemini** (Google) | Haan | Free limit ke saath | [aistudio.google.com](https://aistudio.google.com) |
| **Groq** | Haan | Free limit ke saath | [console.groq.com](https://console.groq.com) |
| **OpenAI** | Haan | Paid (paisa lagta hai) | [platform.openai.com](https://platform.openai.com) |

> **Naye users ke liye salah:** Pehle **Gemini** ya **Groq** try karo —
> dono free limit dete hain, key banana aasaan hai.

---

## 3. API Key kaise banayein (step-by-step)

### Gemini (Google) — Free
1. Mobile ya computer par kholo: **aistudio.google.com**
2. Apne Google account se **Sign in** karo.
3. **"Get API Key"** par tap karo → **"Create API key"** dabao.
4. Jo lambi key dikhe (jaise `AIza...`), use **Copy** kar lo.
5. Is key ko kahin safe jagah note kar lo — dobara poori nahi dikhegi.

### Groq — Free
1. Kholo: **console.groq.com**
2. Google/GitHub se **Sign up / Log in** karo.
3. Left menu me **"API Keys"** par jao → **"Create API Key"** dabao.
4. Key copy kar lo — ye `gsk_...` se shuru hoti hai.

### OpenAI — Paid
1. Kholo: **platform.openai.com**
2. Account banao, **Billing** me payment method add karo (bina paise ke key
   kaam nahi karegi).
3. **API Keys** → **"Create new secret key"** → key copy kar lo.
4. Ye key `sk-...` se shuru hoti hai.

> **Zaroori:** API key password jaisi hoti hai — kisi ke saath share mat karo,
> screenshot me mat bhejo, public jagah paste mat karo.

---

## 4. App me key kaise daalein

1. RADEQuiz app kholo.
2. Neeche right corner me **Sr.AI'so ka gol button (FAB)** dabao — AI chat
   khul jayegi.
3. Chat header me **🔑 (key)** button dabao — **"AI API Keys"** sheet khulegi.
4. **"Select AI"** me apna provider chuno (OpenAI / Gemini / Groq).
   - **Free AI** chunne par key ki zaroorat nahi — field band rahega.
5. Key wale box me apni key **paste** karo.
   - Hint me likha hoga: OpenAI ke liye `sk-...`, Gemini ke liye AI Studio
     key, Groq ke liye `gsk_...`
6. **Save** dabao. Bas! Ab Sr.AI'so aapke provider se jawab dega.

**Key pehchanne ka shortcut:** `sk-` se shuru hone wali key OpenAI ki hoti
hai, `gsk_` se shuru hone wali Groq ki — app inhe khud pehchan leta hai.

---

## 5. Jawab kaun dega? (Fallback order)

Agar aapne koi provider chuna hai to Sr.AI'so is order me koshish karta hai:

1. **Aapka chuna hua provider** (agar uski key save hai)
2. **Gemini** (agar uski key save hai)
3. **Groq** (agar uski key save hai)
4. **Free AI** (hamesha backup — kabhi khaali haath nahi lautata)

Har jawab ke neeche **"Powered by ..."** badge batata hai ki jawab kis AI ne
diya. Agar ek provider fail ho jaye (jaise quota khatm), to Sr.AI'so khud
agle provider par chala jata hai — aapko kuch karne ki zaroorat nahi.

> **Note:** Agar aapne **Free AI** select kiya hai to sirf Free AI use hoga,
> fallback nahi chalega.

---

## 6. Token usage aur daily limit (💲 button)

Chat header me **💲** button dabane par dikhta hai:

- **Last 24 hours** me kitna use hua
- **Total** use
- **Daily limit** — aap khud per-provider roz ki limit laga sakte ho
  (Remaining + progress bar ke saath)

Daily limit lagane se aapka paid quota achanak khatm nahi hoga. Limit
poori hone par wo provider us din skip ho jayega aur fallback chalega.

---

## 7. Privacy — aapki key surakshit hai

- Key **sirf aapke phone me** save hoti hai (app ke private storage me).
- Key **kahin upload nahi hoti** — na server par, na kisi aur device par.
- App key ko sirf us AI provider ko bhejta hai jise aapne chuna hai, jawab
  lane ke liye. Iske alawa key kahin nahi jaati.

---

## 8. Dikkat aaye to (Troubleshooting)

| Dikkat | Wajah / Hal |
|--------|-------------|
| "Invalid key" / jawab nahi aa raha | Key galat paste hui hai — poori key dobara copy-paste karo, aage-peeche space na ho |
| Pehle chalti thi, ab nahi | Provider ka free quota khatm ho sakta hai — nayi key banao ya doosra provider try karo |
| "Daily limit reached" | 💲 me limit badhao ya kal tak wait karo; fallback se Free AI phir bhi chalega |
| Key save nahi ho rahi | Sahi provider select kiya hai na? Free AI me key field band rehta hai — ye normal hai |
| OpenAI key kaam nahi kar rahi | Billing me payment method add hai? Bina balance ke OpenAI key kaam nahi karti |

---

## 9. Quick FAQ

**Q. Kya bina key ke sab features chalenge?**
Haan — Free AI par chat, answer explanation, doubt box sab chalta hai.

**Q. Ek se zyada keys daal sakte hain?**
Haan — teeno providers ki key ek saath save kar sakte ho. Fallback order
se best available use hoga.

**Q. Key badalni / hatani ho to?**
Wapas 🔑 sheet kholo, nayi key paste karke Save karo. Hatane ke liye field
khaali karke Save karo.

**Q. Kya key doosre phone me chalegi?**
Key aapke account ki hai, phone ki nahi — doosre phone ke app me wapas
paste karni hogi. Ek key ek se zyada jagah use ho sakti hai.

**Q. Paise katne ka dar hai?**
Gemini aur Groq ke free limit me paise nahi lagte. Sirf OpenAI paid hai —
usme 💲 daily limit zaroor laga lo.

---

*Ye tutorial RADEQuiz app ke liye hai. App update hone par steps me halka
badlav ho sakta hai.*
