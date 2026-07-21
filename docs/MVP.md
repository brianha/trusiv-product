# MVP.md

> **Trusiv Minimum Viable Product**
>
> Status: Draft v1
> Owner: Product

---

# Purpose

The purpose of the MVP is not to build a complete review platform.

The purpose is to validate Trusiv's core hypothesis.

> **People prefer a simple recommendation percentage from real users over traditional review systems when making purchase decisions.**

Everything included in Version 1 exists to test this hypothesis.

Everything else is deliberately postponed.

---

# Success Criteria

Version 1 succeeds if users can:

- Find a product within seconds.
- Understand whether people would recommend it.
- Understand why.
- Contribute their own recommendation in less than 20 seconds.

The goal is not engagement.

The goal is better purchasing decisions.

---

# Core User Journey

Every user follows the same journey.

```
Find Product
      ↓
Understand Recommendation
      ↓
Make Decision
      ↓
Contribute Experience
```

Every feature in Version 1 supports this journey.

---

# Product Principles

The MVP follows the principles defined in `PRODUCT.md`.

In particular:

- Trust over engagement.
- Simplicity over features.
- Evidence over interpretation.
- Neutrality over persuasion.
- Remove before adding.

Version 1 should feel fast, calm and trustworthy.

---

# Included Features

## 1. Product Search

### Goal

Allow users to quickly find the product they are considering.

### Includes

- Search by product name
- Search by brand
- Search results with product image
- Open Product Page

### Excludes

- AI search
- Voice search
- Advanced filtering
- Categories

---

## 2. Barcode Scan

### Goal

Allow users to identify a product instantly.

### Includes

- Camera barcode scanning
- Product lookup
- Open Product Page

### Excludes

- QR code scanning
- Continuous scanning
- Scan history
- Offline mode

---

## 3. Product Page

### Goal

Answer the user's buying question within a few seconds.

Every Product Page should answer four questions.

1. What product is this?
2. Would people recommend it?
3. Why?
4. Should I buy it?

### Includes

- Product image
- Product name
- Brand
- Recommendation percentage
- Number of recommendations
- Date of latest recommendation
- Short recommendation comments

Example

```
91% would recommend

Based on 427 recommendations

Last recommendation 2 days ago
```

The interface should present evidence rather than conclusions.

### Excludes

- Star ratings
- Review scores
- AI summaries
- Advertisements
- Discussion threads

---

## 4. Submit Recommendation

### Goal

Allow users to contribute with minimal effort.

### Recommendation Question

Every recommendation is based on one simple question.

> **Would you recommend this product to a friend or family member?**

Inspired by the simplicity of the Net Promoter Score (NPS), Trusiv uses a binary recommendation instead of a numerical rating.

### Flow

Step 1

Would you recommend this product?

- Yes
- No

Step 2

(Optional)

Explain why.

Maximum 200 characters.

### Excludes

- Star ratings
- Numerical scores
- Long reviews
- Replies
- Media uploads

---

## 5. Authentication

### Goal

Protect trust while keeping friction low.

### Includes

- Register
- Sign in
- Password reset

Social login may be introduced later.

---

## 6. Add Missing Product

### Goal

Allow the catalogue to grow naturally.

### Includes

- Request new product
- Upload product image (optional)
- Barcode (if available)

Products require moderation before publication.

---

## 7. Moderation

### Goal

Protect trust.

Moderation removes abuse.

It does not moderate opinions.

### Includes

- Report recommendation
- Remove spam
- Remove offensive content
- Remove unrelated content

---

## 8. Administration

### Goal

Operate the platform.

### Includes

- Product approval
- Recommendation moderation
- Basic user management

Administrative reporting is intentionally minimal in Version 1.

---

# Explicitly Out of Scope

The following ideas are intentionally postponed.

Not because they are bad.

Because they do not validate the MVP hypothesis.

- OCR
- Helpful votes
- AI summaries
- Messaging
- Following users
- Notifications
- Social profiles
- Gamification
- Personalized feeds
- Expert reviews
- Company pages
- Price comparison
- Price history
- ESG ratings
- Discussion forums

---

# Release Criteria

Version 1 is ready when a first-time user can:

- Search for a product.
- Scan a barcode.
- Understand the recommendation percentage.
- See how many people contributed.
- See when the latest recommendation was made.
- Read short recommendation comments.
- Submit their own recommendation.

Without needing instructions.

---

# MVP Principles

Every screen has one primary purpose.

Every interaction should feel obvious.

Every feature should reduce uncertainty before buying.

Whenever possible, show evidence instead of interpretation.

If a feature does not help someone make a better purchasing decision, it belongs in a future version—not in the MVP.

---

# MVP Hypothesis

Version 1 is not trying to become the world's largest review platform.

It is trying to answer one question.

> **Will consumers trust and use a simple recommendation model enough to influence their purchasing decisions?**

If the answer is yes, Trusiv has earned the right to grow.