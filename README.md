# Propedge Broker System

Complete 3-part broker platform (Landing + Trading App + Admin Dashboard)

## Files Included

- `landing.html` — Public registration website (traders register here)
- `trading.html` — Client trading platform (where users trade after login)
- `admin.html` — Owner/Admin dashboard (manage all users, reset accounts, etc.)

## How to Use

1. Open `landing.html` in your browser
2. Register a new account (or use one of the demo accounts)
3. Click "Open Trading Platform" — it will open `trading.html` with your account loaded
4. To manage users: Open `admin.html` and login with:
   - Email: admin@propedge.com
   - Password: admin123

## Important Notes

- All data is stored in your browser's localStorage (per-user isolation)
- Each user has completely unique balance, positions, history, etc.
- Works 100% offline after first load
- Mobile responsive on all devices
- Ready to host on Vercel, Netlify, or any static hosting

## Demo Accounts (pre-created)

| Account Type     | Email                    | Password   | Starting Balance |
|------------------|--------------------------|------------|------------------|
| Demo Trader      | trader@propedge.com      | demo123    | $50,000         |
| Demo Pro         | pro@propedge.com         | demo123    | $100,000        |
| Demo Whale       | whale@propedge.com       | demo123    | $250,000        |
| Demo Risk Taker  | risk@propedge.com        | demo123    | $15,000         |

## Next Steps (Optional)

- Add Stripe/Paystack payment integration (I can add this)
- Deploy to Vercel/Netlify (just upload these 3 HTML files)
- Later: Connect to Supabase when you have more projects available

**All data is stored locally in your browser with complete per-user isolation** — every user has their own balance, positions, history, etc.

**Latest Improvements:**
- Mobile-first design (works great on phones)
- Real TradingView chart (changes with symbols)
- Binance symbols + AFEC30 with advanced algorithm
- Custom toast notifications (no basic browser alerts)
- Better text contrast in inputs
- Leverage + Margin system
- Clean homepage (index.html)

Made with ❤️ for Dear Trader

---

**To download:** Right-click the "Propedge-Broker-System" folder and download it as ZIP.