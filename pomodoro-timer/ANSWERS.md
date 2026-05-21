## 1. How to Run
Open `index.html` in any browser:
open index.html
Or run locally:
npx serve .
# visit http://localhost:3000

No install or dependencies needed.

---
Deployed URL: https://pomodoro-timer-npng.vercel.app/

## 2. Stack & Design Choices

**Stack:** Vanilla HTML, CSS, and JavaScript.

I used vanilla JS because this is a small app and frameworks were unnecessary.

**Design choices:**

* Large circular timer keeps focus on the countdown.
* Different background colors for focus, break, and pause modes make states easy to recognize.

---

## 3. Responsive & Accessibility

**Responsive:**

The layout scales properly on both mobile and desktop using flexible sizing.

**Accessibility:**

* Buttons have `aria-labels`
* Timer uses `role="timer"`
* Screen readers announce mode changes
* Keyboard shortcuts:

  * `Space` → start/pause
  * `R` → reset

**Skipped:**

I didn’t add custom focus ring styles for keyboard navigation.

---

## 4. AI Usage

I used Claude to help create the Web Audio API chime.

The original version caused clicking sounds at the end of notes, so I added a smoother fade-out using a gain ramp. I also used different note orders for focus and break completion sounds.

---

## 5. Honest Gap

Timer settings are not saved after closing the tab.

This could be fixed easily using `localStorage` to save focus and break durations.
