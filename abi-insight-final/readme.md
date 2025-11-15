# ABI Insight
Arena Breakout Infinite Website
Level 5 Full Stack Web Development

---

## 🧪 Feature Validation Log (Commit 40)

### Status: All Core Structures Verified

* **Navigation**: All 6 primary pages link correctly in the navbar.
* **Content Pages**: Weapon, Map, Gear, Intel, and Gallery structures are present.
* **Headers**: H2 and H3 styles are standardized across the site.
* **Tier Badges**: Custom tier badges are implemented and styled.
* **Internal Links**: All anchor links and page-to-page navigation are functional.
* **Homepage**: Card system and hero section load correctly.
* **Bootstrap**: All Bootstrap components (tables, badges, grid) display as intended.

## 🌐 Cross-Browser Test Log (Commit 43)

### Scope: Favicon and Core Layout

* **Chrome/Edge (Desktop)**: failed. favicon/icon/home button displayed.Custom CSS (badges, headers) consistent. Responsive layout not stable yet.
* **Firefox (Desktop)**: failed. favicon/icon/home button displayed.Custom CSS (badges, headers) consistent. Responsive layout not stable yet.
* **Safari/Mobile Simulation**: failed. Not All links and core features are working.

**Conclusion**: The core project structure still needs work and favicon/icon/home button display consistently across major browsers.

# 🧪 Project Testing Plan - ABI Insight

## 1. Scope
This plan covers the validation of all core features, navigation, and stylistic consistency across the ABI Insight website before final submission.

## 2. Test Scenarios (Functional)

| ID | Feature | Test Description | Expected Result |
|----|---------|------------------|-----------------|
| F-01 | **Primary Navigation** | Click all links in Navbar and Footer. | Links navigate to the correct page (`*.html`). |
| F-02 | **Anchors** | Test all internal section links (e.g., weapon jump links). | Page scrolls smoothly to the correct `id`. |
| F-03 | **External Links** | Test Social Media icons and any external links. | Links open correctly (preferably in a new tab). |
| F-04 | **Mobile Menu** | Click the hamburger icon on mobile view. | Menu slides in/out correctly, covering the main content. |

## 3. Test Scenarios (Non-Functional)

| ID | Feature | Test Description | Expected Result |
|----|---------|------------------|-----------------|
| N-01 | **Responsiveness** | Resize browser window from Desktop (>1200px) down to Mobile (<576px). | Layout adapts cleanly with no horizontal scroll or element overlap. |
| N-02 | **Stylistic Consistency** | Check all pages for standardized Headers (H2, H3) and Tier Badges. | Styles match the defined CSS (Commit 37/38). |
| N-03 | **Favicon** | Check browser tab icon. | Favicon.svg displays correctly. |

# 📊 Project Testing Log - ABI Insight Results

## Date: [Current Date]
## Tester: Marcus
## Environment: Chrome Desktop, Firefox Mobile View
---

## 1. Functional Testing Results (F-01 to F-04)

| ID   | Result | Fix Required (Y/N) | Notes      |
|------|--------|--------------------|------------|
| F-01 | PASS |     yes            |All navbar links work correctly. Issue: Footer links (index.html, maps.html, etc.) are currently pointing to # (placeholder) and need to be fixed to the correct path. 
| F-02 | PASS |     yes            |Checked all weapon anchor links (#hk416-carbine) on best-weapons.html. All scroll to the correct section. other pages needs update on paths.
| F-03 | FAIL |     yes            |external links not properly set up yet.
| F-04 | PASS |     no             | Mobile menu toggles open and closed smoothly using the checkbox/label structure.

---

## 2. Non-Functional Testing Results (N-01 to N-03)

| ID   | Result | Fix Required (Y/N) | Notes      |
|------|--------|--------------------|------------|
| N-01 | FAIL |     yes            |All screen sizes working correctly. Issue: cta button overlaping itself on mobile sizes, ultrawide sizes needs best layout adjustment.
| N-02 | PASS |     no             |All styles are consistent with website colour pallet and standardized tags and elements.
| N-03 | PASS |     no             |All navbar links work correctly. Issue: Footer links (index.html, maps.html, etc.) are currently pointing to # (placeholder) and need to be fixed to the correct path. 

---

## 3. HTML/CSS Validation (Future Commits)
Results of W3C validation tests will be logged here.

index.html warning: (/) trailing slash on void elements (img tags) it is not necessary in HTML5 and can cause compatibility issues. fixed on commit 49. Document checking completed. No errors or warnings to show.

best-weapons.html : Document checking completed. No errors or warnings to show.

extraction-maps.html : Document checking completed. No errors or warnings to show.

media-gallery.html : Document checking completed. No errors or warnings to show.

latest-intel.html : Document checking completed. No errors or warnings to show.

tactical-gear.html : Document checking completed. No errors or warnings to show.

style.css : Document checking completed. no errors found.
    Warnings:
    line 226 "Some "background-color" and "border-color" properties
    243 The -webkit-overflow-scrolling property is an unknown proprietary property
    246 ::-webkit-scrollbar is not recognized as a valid proprietary pseudo-element
    250 ::-webkit-scrollbar-track is not recognized as a valid proprietary pseudo-element
    255 ::-webkit-scrollbar-thumb is not recognized as a valid proprietary pseudo-element"""