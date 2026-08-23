# 🚀 Setup Instructions (Hinglish mein)

Ye ek **special GitHub repo** hai jiska naam tumhare username jaisa hi hona chahiye — matlab:

```
its-sky-2628/its-sky-2628
```

GitHub is repo ko automatically tumhari **profile README** bana deta hai. Neeche steps follow karo 👇

---

## Step 1 — Repo banao (agar already nahi hai)

1. GitHub par jao → **New Repository**
2. Repository name **exactly** yeh rakho: `its-sky-2628`
3. **Public** rakho
4. "Add a README file" tick mat karo (hum apna khud daalenge)
5. Create Repository

Agar repo already bana hua hai (kyunki special repo already exist karta hai profile pe), toh bas usko clone kar lo.

---

## Step 2 — Files upload karo

Is zip mein 3 cheeze hain:

```
README.md                          → tumhari nayi modern profile README
.github/workflows/snake.yml        → snake animation banane wala GitHub Action
SETUP_INSTRUCTIONS.md              → yehi file jo tum abhi padh rahe ho
```

Sab files ko apne `its-sky-2628` repo mein upload/push kar do, folder structure same rakhna (`.github/workflows/snake.yml` wahi path pe rehna chahiye).

### Terminal se karna ho to:

```bash
git clone https://github.com/its-sky-2628/its-sky-2628.git
cd its-sky-2628
# ab zip ki saari files is folder mein copy paste kar do
git add .
git commit -m "Modern profile + snake animation"
git push
```

---

## Step 3 — README mein apni details daalo

`README.md` file kholo aur ye cheeze apne hisaab se badlo:

- `your-email@example.com` → apna real email
- `your-linkedin`, `your-twitter`, `your-instagram` → apne social links
- "Currently working on..." wali lines → apne actual projects/skills

---

## Step 4 — Snake Action ko chalao (IMPORTANT)

1. Repo ke andar **Actions** tab pe jao
2. Agar workflow disabled dikhaye toh "I understand my workflows, enable them" pe click karo
3. Left side mein **"Generate Snake Animation"** workflow dikhega → usko click karo
4. **"Run workflow"** button dabao (manual trigger)
5. 1-2 minute wait karo — ye ek naya branch `output` banayega jisme snake ki SVG file save hogi

Ye action **daily automatically bhi chalega** (cron job set hai), toh snake animation apne aap fresh contributions ke hisaab se update hoti rahegi. 🐍

---

## Step 5 — Enjoy! 🎉

Ab apni profile pe jao → `github.com/its-sky-2628` → tumhe dikhega:

- ✨ Animated typing header
- 📊 Live GitHub stats + top languages
- 🔥 Streak stats
- 📈 Contribution activity graph
- 🐍 Snake animation eating your contribution graph
- 📌 Pinned project cards
- 🌐 Social badges

---

## ⚠️ Common Issues

- **Snake nahi dikh rahi?** → Actions tab check karo, workflow run hui ya nahi. Agar fail hui hai toh "permissions" check karo: Settings → Actions → General → Workflow permissions → **"Read and write permissions"** select karo, phir dubara run karo.
- **Stats cards blank/error dikha rahe?** → Kabhi kabhi `github-readme-stats` server slow hota hai, thodi der baad refresh karo.
- **Repo name galat rakha?** → Special profile README sirf tabhi kaam karta hai jab repo name **exactly tumhare username jaisa** ho.

Bas itna hi — modern look + snake effect dono ready! 🔥
