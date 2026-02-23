# duolb.com

**Beauty & Wellness directory for Germany.**  
Find salons by city and service category.

---

# duolb – Directory Schema Snapshot

This repository documents the public, sanitized data structure behind  
[duolb.com](https://duolb.com), a Germany-focused Beauty & Wellness directory platform.

duolb enables structured discovery of salons across Germany by **city** and **service category**.

---

## 🎯 Purpose

This repository exists to:

- Provide a high-level overview of the directory data model  
- Document the structural architecture  
- Offer transparency without exposing private infrastructure  

> No sensitive data, API keys, environment variables, or internal configuration are included.

---

## 🗂 Core Data Model

The directory platform is structured around the following core entities:

- `cities`
- `business_categories`
- `salons`
- `city_category_pages`

These entities power:

- City browsing pages  
- Category browsing pages  
- City × Category SEO landing pages  
- Individual salon profile pages  

---

## 🏗 Architecture Context

Production platform stack:

- **Astro** (frontend + server routes)
- **Supabase** (PostgreSQL)
- Structured SEO-focused routing system

This repository contains documentation only.
