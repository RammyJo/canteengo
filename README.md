# CanteenGo

A mobile-first school canteen ordering and operations prototype. This repository contains the latest canteen-style project package.

## Download and run

1. Download `canteengo-canteen-style.zip` from this repository.
2. Extract the ZIP.
3. Open the extracted `canteengo-mvp` directory.
4. Double-click `START CANTEENGO.bat`.

The first launch installs npm dependencies and starts the Vite development server. Keep the terminal window open while testing.

## Current areas

- Parent food menu and pre-orders
- Seller order queue
- Packaged-snack inventory and restock/sale tracking
- Date-based daily menu management
- Manual GCash payment reference review
- Finance and reporting prototype
- Supabase schema/functions and Google Apps Script reporting scaffold
- Canteen-inspired warm visual theme with dark mode

## Important

This is still a prototype. Inventory, menu and order data shown in local demo mode are not yet a production shared database. Before school-wide use, connect Supabase, run the included migrations, configure authentication and review access policies. Manual GCash transfers must be checked in the actual GCash account; a submitted reference is not proof of payment.

Do not commit real student data, GCash credentials, service-role keys, email credentials, or other secrets to GitHub. Use environment variables and secret settings.
