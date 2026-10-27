# LoanShield

**Their threats are your evidence.** A Social & Sustainability project on illegal loan-app harassment in India (SDGs 1, 8, 10 and 16).

Other tools try to block the threats. LoanShield turns each threat into a fact for the victim and evidence against the operator.

## What the website does

- **Do it yourself or get assistance**: paste, speak or upload a screenshot; or turn on helper mode, or ask a volunteer to call back.
- **Fear → Fact**: each threat is answered with what is actually true and the law it may break (English, Tamil, Hindi, read aloud).
- **Protect me in one tap**: seals the message as tamper-proof evidence (SHA-256 hash chain), links the operator, and prepares the contact warning and complaint.
- **Follow the money**: reports that share a UPI ID or phone number join into one operator, made public only after 3 different people report it.
- **Leaked photo help**: takedown request per platform, StopNCII, and a counsellor call-back. The photo is never uploaded.

The website is one part of a five-stage system: Prevent, Detect, Protect, Respond, Reform, run with SHGs, cyber-safety NGOs and legal-aid clinics.

## Files

| Path | What it is |
|---|---|
| `index.html` | The built website (served by GitHub Pages) |
| `src/core.js` | Logic: threat scanner, rights map, evidence hash chain, scam graph, complaint packet |
| `src/data.js` | Fictional sample reports and the 50-message test set |
| `src/app.js` | The website interface |
| `src/index.src.html` | Page layout and styles |
| `src/build.js` | Builds the website from the files above |
| `src/test.js` | Tests (prints recall and precision) |
| `presentation/` | The final deck (.pptx) and the script that builds it |
| `downloads/` | The deck as PDF, linked from the website |

## Run it

Open `index.html` in a browser, or:

```
cd src
node test.js
node build.js   # writes src/site/index.html; copy it to the repo root
```

Sample app names, UPI IDs and phone numbers are fictional. The law mapping is a guide, not legal advice.

**Team:** Karthik J (23BRS1191) · K Annu Prasath (24BCE5409) · Pasunuru Sai Vivek (24BCE1239) · Srinidhi Vishal Chejarla (24BCE1493)
