---
title: "Test Post - এটা একটা পরীক্ষা"
published: 2025-11-20
description: "এই post টা test করার জন্য। homepage এ দেখা যাবে কিনা check করছি।"
tags: [Test, Example, First Post]
category: Personal
draft: false
---

# 🎉 এই Post টা Homepage এ দেখা যাচ্ছে?

যদি আপনি এই post টা দেখতে পাচ্ছেন, মানে সব ঠিকঠাক কাজ করছে!

## ✅ কি কি হওয়া উচিত:

1. **Homepage এ দেখা যাবে** - Latest post হিসেবে
2. **Archive page এ আছে** - 2025 > November section এ
3. **Category page এ আছে** - Personal category তে
4. **Tag pages এ আছে** - Test, Example, First Post tags এ
5. **নিজস্ব page আছে** - /posts/test-post-example

## 🔍 কিভাবে Check করবেন:

### Homepage Check:
```
http://localhost:4321/
```
প্রথম post হিসেবে দেখা যাবে (newest post)

### Archive Check:
```
http://localhost:4321/archive
```
2025 এর নভেম্বর section এ থাকবে

### Direct Post URL:
```
http://localhost:4321/posts/test-post-example
```
এই page টা open হবে

## 📝 Important Notes:

- ✅ **No manual work needed** - সব automatic!
- ✅ **Date controls order** - `published` date দেখে sort হয়
- ✅ **Draft = false** করলেই show হবে
- ✅ **Save করলেই update** হবে (dev mode এ)

## 🎨 Post Visibility Rules:

```yaml
draft: false  ← Homepage এ show হবে ✅
draft: true   ← Show হবে না ❌
```

## 🚀 এখন কি করুন:

1. Development server চালু করুন: `pnpm dev`
2. Browser এ open করুন: `http://localhost:4321`
3. এই post টা homepage এ দেখুন
4. Archive page (`/archive`) check করুন
5. এই post delete করতে চাইলে file টা delete করুন!

---

**Test successful হলে এই post টা delete করে দিতে পারেন!**

File location: `src/contents/posts/test-post-example.md`
