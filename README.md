# PRIYO APP V-55

Home UI + login gate update.

- Home follows the approved PRIYO APP V37 reference layout.
- No page zoom, horizontal scroll, or vertical home scroll.
- First launch requires login.
- Successful login creates a local PRIYO ID/profile.
- Admin UI is isolated from ordinary users.
- GitHub Actions builds `assembleDebug`.

The verified admin email is intentionally not hard-coded into the source. It must be configured in the deployment/backend before production use.
