---
layout: post
title: Why I'm looking at PrestaShop
---

I have always been a big fan of WordPress so when I needed ecommerce software I looked at WooCommerce naturally. This year I finally decided to look at PrestaShop after reading an article which summarised all the new features due in PrestaShop 1.7, the next major version.

### 1. It's open source

It's a french software so I heard about it a long time ago but I always preferred WordPress.
I believe WordPress has a much better open source approach, but still, PrestaShop is open source.

### 2. They're moving to Symfony

They recently moved to Symfony. I believe it's the best way to focus on ecommerce features and business logic. Plus I love Symfony.

The quick wins are obvious: component like `Finder`, `FileSystem`, `PropertyAccess` are now available anywhere.

Another long-term improvement is testing. Using dependency injections and all, PrestaShop is a lot more testable.

### 3. New theme framework

When I tried PrestaShop about 1 year and a half ago, I tried to customise the default theme. It's usually why I do first when  I try any CMS software.

**This was hell!**

It was literally impossible to use. JavaScript code was shit. CSS code was a massive joke. Template held most of the logic. Absolutely nothing was consistent.

The new major version (not released at the time of writing) they introduced a new theme framework called StarterTheme. It's to PrestaShop what *_s* is to WordPress. It seems really interesting and I think now, it's reasonable to create a theme.
