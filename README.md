# Halavar Desert Retreat (demo website)

A demo hotel website with working online booking. Halavar is a made-up hotel; the photos were generated with AI.

- `index.html`: the public site. The booking calendar reads live availability and sends real booking requests.
- `admin.html`: the owner dashboard. The owner signs in with a password, then confirms or declines requests.
- Data lives in Supabase (project `halavar-demo`). The browser only calls the database functions `availability`, `request_booking` and the `owner_*` functions. The tables themselves are locked.

Hosted on GitHub Pages. No build step: edit the HTML files and push.
