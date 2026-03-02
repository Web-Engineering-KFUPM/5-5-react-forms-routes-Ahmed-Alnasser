# 5-5-react-forms-routes-main — Feedback

## Submission

- **Lab:** 5-5-react-forms-routes-main
- **Deadline (Riyadh / UTC+03:00):** 2026-03-02T20:59:00+03:00
- **Last commit time (from git log):** 2026-03-02T08:52:03+03:00
- **Submission marks:** **20/20** (On time)


## Files Checked

- Repo root (cwd): /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form
- Detected project root: /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form
- App: ✅ /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form/src/App.jsx
- Registration: ✅ /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form/src/pages/Registration.jsx
- Home: ✅ /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form/src/pages/Home.jsx
- About: ✅ /Users/mega/Desktop/Uni Courses/SWE363/Labs/5.5/5-5-react-forms-routes-Ahmed-Alnasser/5-5-react-route-form/src/pages/About.jsx

---

## TODO-by-TODO Feedback

### TODO #1A: Router imports + navbar links (App.jsx) — **20/20**

**Checklist**
- ✅ Imports router primitives (Routes/Route/NavLink) from "react-router-dom"
- ✅ Navbar contains NavLink(s)
- ✅ Has a Home link to "/" (preferably with end)
- ✅ Has an About link to "/about"
- ✅ Has a Registration link to "/registration"

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO #1B: Routes + 404 route (App.jsx) — **20/20**

**Checklist**
- ✅ Defines <Routes> ... </Routes>
- ✅ Route for "/" renders <Home />
- ✅ Route for "/about" renders <About />
- ✅ Route for "/registration" renders <Registration />
- ✅ Has a catch-all 404 route (path="*")

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO #2A: Password + gender fields + errors UI (Registration.jsx) — **20/20**

**Checklist**
- ✅ Has state for password (useState + setPassword)
- ✅ Has state for gender (useState + setGender)
- ✅ Renders a password input (type="password")
- ✅ Renders gender radio inputs (type=radio + name=gender)
- ✅ Shows error message(s) with <p className="error"> ... </p>

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO #2B: Validation + disable button + success-only alert (Registration.jsx) — **20/20**

**Checklist**
- ✅ Builds an errors object (nextErrors) and sets it (setErrors(nextErrors))
- ✅ Email validation checks "@" and ends with ".com" (top-level)
- ✅ Validates password required and gender selected (top-level)
- ✅ Stops submit when errors exist (Object.keys(nextErrors).length > 0 return)
- ✅ Register button is disabled until fields are filled (disabled={...})
- ✅ Shows alert ONLY on success (best-effort: alert occurs after the error guard)

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- JS/JSX comments are ignored (so starter TODO comments do NOT count).
- Checks are intentionally light: they look for key constructs and basic structure.
- Code can be in ANY order; repeated code is allowed.
- Common equivalents are accepted, and naming is flexible.
- Missing required items reduce marks proportionally within that TODO.
