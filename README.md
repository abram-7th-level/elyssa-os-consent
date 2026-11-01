# elyssa-os-consent

The OAuth consent page for the Elyssa OS household connector, published from the private
`elyssa-os` repository (`web/consent.html`, `scripts/consent-publish.sh`). It contains no secrets:
a Supabase project URL and its publishable key, which every browser client of that project holds.
Only the household's existing accounts can sign in; self-signup is off.
