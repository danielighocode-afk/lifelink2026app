LIFELINK APP SHELL - changed files only

HOW TO USE
1. Copy every file in this folder into your LifeLink project root (the folder that has home.html).
   Say yes to replace when asked.
2. Run:  npm run prepare:www
3. Push / host as you normally do.
4. On a phone, open  your-address/app.html  once (customers)
   or  your-address/provider-app.html  once (providers).
   After that, signing in lands in the app shell.
5. To switch it off: open app.html?off=1  or  provider-app.html?off=1

NEW FILES
  app.html            customer shell
  provider-app.html   provider shell
  ll-shell.js         the shell code (customer and provider)

CHANGED FILES
  lifelink.js, ll-app.js, page-home.js, page-profile.js,
  page-provider-profile.js, page-provider-dashboard.js, settings.html

NOT TOUCHED: ll-api.js, supabase-*.js, payments, push.
NOT TESTED: real phones, the Android app, iPhone, Paystack, live location, real Supabase data.
