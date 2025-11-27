# Liferay Dynamic Fragments Showcase

This repository contains a set of resources demonstrating content mapping, dynamic display features, and custom fragments for Liferay DXP.

## Repository Contents

- 🧩 Custom Editable Fragments

  - A library of custom editable fragments, so you can map content to them.

- 📄 Display Page Templates

  - A dedicated Display Page Template specifically for Blog Entries, using mapped fragments.

- 🏠 Dynamic Home Page

  - A demonstration of a fully dynamic landing page structure:

    - **Collection Display:** The page utilizes the _Collection Display_ fragment to iterate over a dynamic list of blog entries.

    - **Field Mapping:** Inside the Collection Display, the fragments' fields are **mapped dynamically** to the specific item in the loop (e.g., _image_, _title_).

---

## Usage

- Clone this repo: `git clone https://github.com/gabsprates/liferay-dynamic-fragments.git`

- Enter the cloned directory: `cd liferay-dynamic-fragments`

- Setup Liferay server: `blade server init`

- Start Liferay server: `blade server run`

- Login with user `test@liferay.com` and password `test`

- Open http://localhost:8080

- If you don't see any content:

  - Go to `Global Menu > Control Panel > Search > Index Actions` and click on `Reindex` for `All Search Indexes`

  - Go back to http://localhost:8080
