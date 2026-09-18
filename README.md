# Jazital Downloads

Official downloads for software made by **[Jazital](https://jazital.com)** — desktop apps, WordPress themes and plugins, and other software releases.

Every file here is published by Jazital. If you were sent a Jazital installer from anywhere else, get it from this page instead.

## Products

| Product | What it is | Platform | Download |
|---|---|---|---|
| **Rasin POS** | Point of sale for shops and restaurants that keeps selling when the internet goes down — products, staff, receipts and reports across every outlet. | Windows 10 / 11, 64-bit | [Rasin POS releases](https://github.com/Jazital/downloads/releases?q=rasin-pos&expanded=true) |
| **Tempo Push** | Play any loop at any speed without changing its key, and split a song into music and voices — for choirs, worship teams and bands. | Windows 10 / 11, 64-bit | [Tempo Push releases](https://github.com/Jazital/downloads/releases?q=tempo-push&expanded=true) |

Each release page lists the installer under **Assets**. Pick the newest release for the product you want.

## Installing a Windows app

1. Download the `.exe` installer from the product's newest release.
2. Run it. Windows may show **"Windows protected your PC"** for a publisher it does not recognise yet — choose **More info**, then **Run anyway**.
3. Updating? Close the app first, then install over the top. Your data and settings are kept.

Where a release also includes an `.msi`, that is for IT teams deploying to several machines at once. Everyone else should use the `.exe`.

## Installing a WordPress theme or plugin

1. Download the `.zip` from the product's newest release. **Do not unzip it.**
2. In WordPress, go to **Plugins → Add New → Upload Plugin** (or **Appearance → Themes → Add New → Upload Theme**).
3. Choose the `.zip`, install, then activate.

To update, upload the newer `.zip` the same way — WordPress will offer to replace the installed version.

## Support

- Email: **[hello@jazital.com](mailto:hello@jazital.com)**
- Website: **[jazital.com](https://jazital.com)**

Please mention the product name and the version you are running.

---

## For Jazital: publishing a release

This repository holds **released builds only**. Source code lives in each product's own private repository.

Because several products share this one repository, releases must be named so they cannot be confused with each other:

- **Tag:** `<product>-v<version>` — for example `rasin-pos-v1.7.4`, `tempo-push-v3.0.2`. The product slug is the same one used in the Jazital store and licence server.
- **Title:** `<Product Name> v<version>` — for example `Rasin POS v1.7.4`.
- **Assets:** the installer (and `.msi`, `.zip`, `latest.yml` or blockmap where the product uses them) attached to that release only.
- **Notes:** what changed, written for customers.

**Do not rely on "Latest release".** GitHub marks one release as *Latest* for the whole repository, so `/releases/latest` points at whichever product was published most recently — not the newest version of any particular product. Link to a specific release, or to the product's filtered list as the table above does.

## Renamed

This repository was previously `Jazital/tempo-push-downloads`. GitHub redirects the old address here, so older links continue to work.
