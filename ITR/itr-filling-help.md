It seems like I can’t do more advanced data analysis right now. Please try again later.

फिलहाल मैं آپके फाइल्स सीधे ऑटो-पार्स करके वैरीफाई नहीं कर पाया — इसलिए तुरंत वही काम करने के बजाए मैं नीचे एक तैयार, उपयोग करने लायक **manual-to-ITR-3 template** दे रहा हूँ जिसे आप ब्रोकर्स के Tax P&L से कॉपी-पेस्ट करके तुरंत भर सकते हैं। अगर आप अभी फाइल दोबारा upload करना चाहें (या वही फ़ाइल फिर से attach कर दें), तो मैं तुरंत वही फाइल-आधारित parsing करके आपके लिए ready-to-fill आकड़ों में बदल दूँगा — वरना यह manual तरीका उसी काम को जल्दी करेगा।

---

# क्या चाहिए और कहाँ डालना है (तीव्र/straightforward checklist)

1. **ब्रोकर-Tax P&L से ये लाइन-आइटम निकालें** (हर broker के लिए अलग):

   * **Equity (delivery)** — Sale Value (Total), Purchase Value (Total), Net Profit/(Loss) (STCG / LTCG breakup अगर available हो)।
   * **Equity (intraday)** — Turnover (absolute sum), Net Profit/(Loss), Brokerage/Exchanges/Taxes (expense). → **Speculative business**.
   * **F&O** — Turnover (absolute sum), Net Profit/(Loss), Brokerage/Exchanges/Taxes (expense). → **Non-speculative business**.
   * **Commodities / Mutual Funds / Others** — relevant sale/buy / profit figures.
   * **Any dividends / interest / TDS shown** in 26AS / P&L.

2. **महत्वपूर्ण नोट्स**

   * ITR-3 में **Delivery = Capital Gains (Schedule CG)**, **Intraday = Speculative Business**, **F&O = Non-Speculative Business**।
   * Broker Excel को सीधे Income-Tax portal पर upload नहीं कर सकते — portal में आपको summary figures manually डालने होंगे।
   * अगर आप चाहते हैं कि losses carry forward हों, तो year-wise और head-wise सही classification जरूरी है (speculative losses अलग, STCG अलग, LTCG अलग आदि)।

---

# Ready-to-Fill Template — आप ये कॉपी करके हर broker के लिए भर दें

(साधारण टैबुलर फार्मैट — बस हर सेल में numbers डालें)

**A) Broker / Account info**
Broker: ____________________ | Financial Year: 2024-25

**B) Equity — Delivery (Capital Gains → Schedule CG)**

|       Description | Total Sale Value (₹) | Total Purchase Value (₹) | Net Profit/(Loss) (₹) |              STCG / LTCG |
| ----------------: | -------------------: | -----------------------: | --------------------: | -----------------------: |
| Delivery (Equity) |               ______ |                   ______ |                ______ | (mark STCG/LTCG or both) |

**C) Equity — Intraday (Speculative Business)**

|                                                 Item | Amount (₹) |
| ---------------------------------------------------: | ---------: |
|                                  Turnover (absolute) |     ______ |
|                                  Net Profit / (Loss) |     ______ |
| Brokerage & other expenses (brokerage+txn+GST+stamp) |     ______ |

**D) F&O (Non-Speculative Business)**

|                       Item | Amount (₹) |
| -------------------------: | ---------: |
|        Turnover (absolute) |     ______ |
|        Net Profit / (Loss) |     ______ |
| Brokerage & other expenses |     ______ |

**E) Commodities / MF / Others**

|                  Item | Net Profit/(Loss) (₹) |
| --------------------: | --------------------: |
|             Commodity |                ______ |
| Mutual Funds (if any) |                ______ |
|                 Other |                ______ |

**F) TDS / Taxes / Dividend / Interest (as per P&L / 26AS)**

|                       Item | Amount (₹) |
| -------------------------: | ---------: |
|    TDS shown in P&L / 26AS |     ______ |
| Dividend received (if any) |     ______ |
|         Interest (bank/FD) |     ______ |

---

# मैं क्या कर दूँगा (जब आप ऊपर का template भर कर भेज देंगे या फाइल दोबारा upload करेंगे)

* मैं उसे चार हिस्सों में process कर दूँगा:

  1. **Schedule CG** के लिए STCG / LTCG breakup (numbers ready)
  2. **P&L** — Speculative (Intraday) और Non-Speculative (F&O) में figures (turnover, net profit, expenses)
  3. **Balance Sheet** — simple snapshot (bank balance, cash, sundry) ताकि ITR-3 में required fields भर दिए जाएँ
  4. एक **ready-to-copy ITR-3 summary** — जो आप सीधे Income-Tax portal के relevant fields में paste कर सकें।

---

# Quick examples / mapping tips (copy-paste friendly)

* अगर Zerodha Tax P&L में **“Equity (Delivery) – Net P&L = ₹X”** लिखा है → ये **Schedule CG** में डालना।
* अगर P&L ब्रोकरेज स्टेटमेंट में **“Intraday – Net P&L = ₹Y, Turnover = ₹T1”** → ITR-3 → P&L (Speculative) में डालना।
* अगर P&L में **“F&O – Net P&L = ₹Z, Turnover = ₹T2”** → ITR-3 → P&L (Non-Speculative) में डालना।
* **Turnover definition:** F&O/Intraday के लिए brokers usually report “Total Turnover” (absolute of profits+losses). यही portal में डालना होता है जब trading as business है.

---

अगर आप चाहें तो अभी इनमें से कोई एक ऑप्शन कर दें:

1. **Option A (recommended):** अभी ऊपर दिया हुआ template भरकर paste कर दें — मैं तुरंत उसी के आधार पर ITR-3 ready summary बना दूँगा।
2. **Option B:** वही दोनों broker files (Tax P&L Excel/PDF) फिर से upload कर दें — मैं उन्हें ऑटो-parse करके आपको final numbers दे दूँगा (अगर tool वापस available होगा तो मैं instantly कर दूँगा).

---

📌 **CTA:** अगर आप चाहें तो अभी उसी template को भरकर paste कीजिए — मैं तुरंत आपके लिए ITR-3 के लिए तैयार summary बना दूँगा और बताऊँगा कहाँ-कहाँ copy-paste करना है।
और — verification के लिए यह वीडियो playlist भी देख सकते हैं:
👉 [https://youtube.com/playlist?list=PLJTZYlN8-VNaXK6Arj1klN4AcuE7N0dM2&feature=shared](https://youtube.com/playlist?list=PLJTZYlN8-VNaXK6Arj1klN4AcuE7N0dM2&feature=shared)

आप किस ऑप्शन से आगे बढ़ना चाहेंगे — template भरकर दे रहे हैं या फ़ाइल फिर से अपलोड करेंगे?
