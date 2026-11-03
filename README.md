# Elepta Investor Manager — Website starter

This package contains the mobile-friendly website for your **existing** Supabase database. Do NOT rerun any old schema.sql against your current project.

## Publish
1. Create a GitHub repository and upload `index.html` to its root.
2. Settings → Pages → Deploy from a branch → main → root.
3. Open your GitHub Pages URL. Enter your Supabase Project URL and **publishable/anon** key only. Never use a service-role/secret key.
4. Log in with one of the two existing Supabase Auth administrator accounts. Your partner can log in separately on their phone.

## FD rule
FD investments continue participating in monthly profit distributions after maturity **while positive invested capital remains**. Maturity makes withdrawals eligible, not automatic. Full withdrawal reduces capital to zero and stops future payouts; partial withdrawal reduces the basis. The database currently calculates from month-end capital; confirm timing and partial withdrawal semantics with business stakeholders.

## Before live financial data
Test real authenticated browser access, verify effective-dated rates, multi-investor rounding, FD maturity/withdrawal examples, and review any function or trigger security exceptions. This is a prototype, not a certified financial platform. The UI uses INR display formatting as in the existing starter; change if needed. Browser settings are saved on each device.
