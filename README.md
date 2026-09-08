# Shein Scraper

Shein Scraper gets you 🎯 accurate, 🔍 detailed Shein data as clean JSON in **Real-Time**.

No selectors, no proxies, no data cleaning. Just the data.

[**Try it now in the playground**](https://www.omkar.cloud/tools/shein-scraper/playground) - See the data quality for yourself in one click, **No sign-up required**.

**Build on it free:** 200 calls every month, no credit card ❤️

[![Shein Scraper API playground — run a live request in your browser, free, no sign-up](https://raw.githubusercontent.com/omkarcloud/shein-scraper/master/playground.png)](https://www.omkar.cloud/tools/shein-scraper/playground)

## What can I get

- 🔎 **Live search across 15,000+ products per query** — 120 per page with price, discount, rating, reviews, stock, images & colour variants; filter by price, sort 5 ways
- 👗 **Full product details** — every colour and size with its own SKU and stock, retail vs sale price, gallery, video, attributes, size guide with measurements, store & brand
- 🗂️ **Category browsing 3,000+ deep** — page through any Shein category the reliable way, same product card as search
- 📈 **Search intelligence** — how Shein interprets a query, trending keywords right now, supported currencies with USD rates & languages

## Why Shein Scraper

Most other Shein APIs fail you in one of four ways:

- 🗄️ **Inaccurate, cached, stale data**
- 🧩 **Low-detail endpoints** — a few fields per call, never the full picture
- 💸 **Pay more to get the same data**
- 🪦 **Works today, breaks next month** — nobody maintains it

Shein Scraper is scraped live on every call, priced honestly, and actively maintained.

## Example: A Full Shein Product

```json
{
  "goods_id": "515174062",
  "sku": "sz260411180786695456573",
  "name": "Pullover Dress, Yarn-Dyed Lightweight Polyester Non-Stretch Fabric, Striped Casual Vacation Dress",
  "link": "https://us.shein.com/product-p-515174062.html",
  "category": { "id": "1727", "name": "Women Dresses", "breadcrumb": ["Women Apparel", "Women Clothing", "Women Dresses"] },
  "pricing": {
    "retail_price": { "amount": 16.39, "currency": "USD", "formatted": "$16.39" },
    "sale_price": { "amount": 13.25, "currency": "USD", "formatted": "$13.25" },
    "discount_percent": 19
  },
  "rating": 3.76,
  "reviews_count": 82,
  "reviews_breakdown": { "five_star": 45.2, "four_star": 14.6, "three_star": 20.7, "two_star": 11.0, "one_star": 8.5 },
  "in_stock": true,
  "stock": 20,
  "images": [
    "https://img.ltwebstatic.com/v4/j/spmp/2026/08/12/fa/1786526082ca7413b788e6d80d97fc6cd3ab31.jpg",
    "https://img.ltwebstatic.com/v4/j/spmp/2026/06/24/31/1782294508ba6ed7e947f7b7ea12b3542fd5f0.jpg"
  ],
  "has_video": true,
  "colors": [
    { "name": "Multicolor", "goods_id": "463749025", "sku": "sz260411180786695444065", "link": "https://us.shein.com/product-p-463749025.html" },
    { "name": "Blue and White", "goods_id": "515174062", "sku": "sz260411180786695456573", "link": "https://us.shein.com/product-p-515174062.html" }
  ],
  "sizes": [
    { "size": "XS", "sku_code": "I6mqrwdksfrsax", "stock": 20, "in_stock": true, "price": { "amount": 13.25, "formatted": "$13.25" } },
    { "size": "L", "sku_code": "I3mqrwdktigqkf", "stock": 20, "in_stock": true, "price": { "amount": 13.25, "formatted": "$13.25" } }
  ],
  "size_guide": {
    "measurements": [
      { "attr_value_name": "XS", "Shoulder ": " 30 cm", "Bust ": " 88 cm", "Waist Size ": " 74 cm", "Length ": " 83 cm" }
    ]
  },
  "attributes": [ { "name": "Details", "value": "Tie Back, Zipper" } ],
  "store": { "code": "8494550432", "name": "jiyifushi", "products_count": 12, "is_choice_store": false },
  "is_returnable": true
}
```

*Trimmed for readability.*

## Get Started with 200 Free Calls

Start in the [playground](https://www.omkar.cloud/tools/shein-scraper/playground) — try any endpoint with one click, no sign-up required.

Once you're happy with the data, start with the free plan for 200 free calls every month:

1. [Sign up on Omkar Cloud](https://www.omkar.cloud/auth/sign-up?redirect=/tools/shein-scraper/playground) — free, no credit card.
2. Open the [Shein Scraper playground](https://www.omkar.cloud/tools/shein-scraper/playground) and search for anything you like. Click **Get Live Data**.
3. Enjoy your data 😎.

## Endpoints

7 endpoints cover everything you need.

| Endpoint | Path | Returns |
|---|---|---|
| Search Products | `/search/products` | 120 products per page with price, discount, rating, stock & variants |
| Product Details | `/products/details` | Everything about one product: every colour, size, stock, price & photo |
| Category Products | `/categories/products` | Any category, 120 per page, same filters and sort as search |
| Search Autocomplete | `/search/autocomplete` | How Shein reads a query: matched categories and product count |
| Trending Keywords | `/products/trending` | The search terms Shein is pushing right now |
| Currencies | `/helpers/currencies` | Every supported currency with symbol and USD exchange rate |
| Languages | `/helpers/languages` | Every supported storefront language |

## Pricing

High value, Low price.

| Plan | Price | Calls / month | Per 1,000 |
|---|---|---|---|
| **Basic** | **Free** | **200** — the most generous free plan | $0 |
| **Pro** | $16/mo | 5,000 | $3.20 |
| **Ultra** | $48/mo | 25,000 | $1.92 |
| **Mega** | $148/mo | 150,000 | $0.99 |

Need a bigger plan? Ask on [WhatsApp](https://api.whatsapp.com/send?phone=918178804274&text=I%20need%20a%20custom%20plan%20for%20the%20Shein%20Scraper%20API.) or [Email](mailto:happy.to.help@omkar.cloud?subject=Custom%20plan%20for%20Shein%20Scraper%20API&body=I%20need%20a%20custom%20plan%20for%20the%20Shein%20Scraper%20API.).

- [**90 Day 2 Click Refund Guarantee**](https://www.omkar.cloud/refund-process)
- This is an excellent API made by Omkar Cloud, which is Rated Excellent — [4.7 based on 30 reviews on Trustpilot](https://www.trustpilot.com/review/omkar.cloud).

👉 [Start with Free Plan](https://www.omkar.cloud/auth/sign-up?redirect=/tools/shein-scraper/playground) — 200 free calls/month

## 💬 Have Questions? We Have Answers.

You're a developer — we know how hard completing a project can be. So we offer full support: just message us and we'll reply ✅ with a solution within 1 working day.

[![Message Us on WhatsApp about Shein Scraper](https://raw.githubusercontent.com/omkarcloud/assets/master/images/whatsapp-us.png)](https://api.whatsapp.com/send?phone=918178804274&text=I%20need%20help%20using%20the%20Shein%20Scraper%20API.)

[![Ask Us by Email about Shein Scraper](https://raw.githubusercontent.com/omkarcloud/assets/master/images/ask-on-email.png)](mailto:happy.to.help@omkar.cloud?subject=Help%20with%20Shein%20Scraper%20API&body=I%20need%20help%20using%20the%20Shein%20Scraper%20API.)

## Popular Scrapers by Omkar Cloud

- [**Google Maps Scraper (3,100+ GitHub Stars)**](https://github.com/omkarcloud/google-maps-scraper) — type "boutiques in Los Angeles", get every business as a ready-to-call lead list: phones, emails, websites & reviews. Up to 100K free leads/month.
- [**AliExpress Scraper**](https://www.omkar.cloud/tools/aliexpress-scraper) — live product details, SKU variants, stock & shipping
- [**Website Email Contact Scraper**](https://www.omkar.cloud/tools/website-email-contact-scraper) — emails, phones & socials from any website
- [**Booking Scraper**](https://www.omkar.cloud/tools/booking-scraper) — Booking.com hotels: prices, ratings, rooms & amenities
- [**IMDb Scraper**](https://www.omkar.cloud/tools/imdb-scraper) — movies, TV, ratings, cast, charts & box office
- [**Rightmove Scraper**](https://www.omkar.cloud/tools/rightmove-scraper) — UK property listings, sold prices & estate agents

👉 [Start with Free Plan](https://www.omkar.cloud/auth/sign-up?redirect=/tools/shein-scraper/playground) — 200 free calls/month
