---
layout: default
title: GadgetJuara
description: Review tech & gadget Shopee Indonesia — smartphone, laptop, audio, smart home. Spec breakdown jujur dan rekomendasi based on real use case.
permalink: /
---

# GadgetJuara

Hub review tech & gadget. Hanya produk yang lulus standar performa-vs-harga.

## Review Terbaru

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})** — {{ post.description | truncate: 100 }}
{% endfor %}

## Kategori

- 📱 [Smartphone](#) — HP Android, iPhone second
- 💻 [Laptop](#) — kerja, gaming, budget
- 🎧 [Audio](#) — TWS, headphone, IEM
- 🏠 [Smart Home](#) — bulb, plug, CCTV, vacuum
- 🔌 [Aksesoris](#) — power bank, charger, kabel

## Tentang Gadgetjuara

Site review oleh community builder berbasis Yogyakarta. Fokus pada gadget tech yang worth it secara value-for-money.

[Baca selengkapnya tentang penulis →](/tentang/)

---

**Disclosure:** Beberapa link di situs ini adalah affiliate Shopee. Klik membantu support situs ini, tanpa biaya tambahan dari sisi Anda. [Detail disclosure →](/disclosure/)
