# ADMISSIONS PAGE - ADMIN UPDATE GUIDE

## 📋 What Admin Needs to Update Yearly

This guide shows you exactly what to update on the Admissions page each year.

---

## ⚠️ SECTIONS TO UPDATE EVERY YEAR:

### 1. IMPORTANT DATES (Line ~230)
Look for: `<!-- ⚠️ ADMIN: UPDATE THESE DATES EVERY YEAR -->`

**What to update:**
- Application Opens date
- Application Deadline date
- Term Begins date

**Example:**
```html
<p class="date">January 15, 2026</p>  <!-- Change year -->
<p class="date">August 30, 2026</p>   <!-- Change year -->
<p class="date">September 2026</p>    <!-- Change year -->
```

---

### 2. FEES OVERVIEW (Line ~260)
Look for: `<!-- ⚠️ ADMIN: UPDATE FEES IF THEY CHANGE -->`

**What to update:**
- O-Level enrollment fee
- A-Level enrollment fee

**Example:**
```html
<p class="fee-amount">55,000 RWF</p>  <!-- Update if fee increases -->
<p class="fee-amount">65,000 RWF</p>  <!-- Update if fee increases -->
```

---

### 3. FAQs DATES (Line ~310)
Look for: `<!-- ⚠️ ADMIN: UPDATE FAQ DATES IF THEY CHANGE -->`

**What to update:**
- Dates mentioned in the first FAQ answer

**Example:**
```html
<p>Applications open on January 15, 2026 and close on August 30, 2026...</p>
```

---

## 🔒 SECTIONS THAT STAY THE SAME:

- Navbar
- Hero Section
- Why Choose Us
- Programs Overview
- Admission Requirements
- Required Documents
- Admission Process (6 steps)
- Apply Now Buttons
- Contact Information
- Footer

---

## 📝 HOW TO UPDATE:

1. Open file: `/src/admissions/admissions.html`
2. Search for: `⚠️ ADMIN:`
3. Update the dates/fees as needed
4. Save the file
5. Upload to website

---

## 💡 TIPS:

- Look for `<!-- ⚠️ ADMIN: -->` comments - they mark what needs updating
- Update all 3 sections at the same time (dates appear in multiple places)
- Keep the same format (don't change HTML structure)
- Only change the text/numbers inside the tags

---

## ❓ QUESTIONS?

If you need to update something else (like contact info, programs, etc.), contact the web developer.
