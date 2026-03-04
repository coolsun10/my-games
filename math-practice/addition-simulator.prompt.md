Create a complete single-file HTML game called **Addition Simulator**.

Requirements:
1. The app must display one addition question at a time in **vertical format** (stacked numbers), like:
 [c] [c] [c]
   A
 + B
 ----
   ?
2. Randomly generate `A` and `B` as whole numbers from 0 to 20 (Kindergarten and 1st grade friendly).
3. The user answers by typing into an input field and pressing **Enter** or clicking a **Submit** button.
4. Keep and display these live stats:
   - Total questions attempted
   - Total correct answers
   - Current streak (consecutive correct answers)
   - Best streak
5. If the answer is correct:
   - Show positive feedback
   - Increase current streak
   - Immediately load the next question
6. If the answer is wrong:
   - Show: `Correct answer: <value>`
   - Reset current streak to 0
   - Wait 3 seconds
   - Then automatically show the next question
7. Add an **End Game** button:
   - Stops new questions
   - Disables input/submission
   - Shows a final summary (attempted, correct, accuracy %, best streak)
8. Use only plain HTML, CSS, and JavaScript (no external libraries).
9. Make the UI clean and centered, with clear readable text and mobile-friendly spacing.
10. Output only the final HTML code.

Behavior details:
- Ignore empty input (do not count as attempt).
- Accept only non-negative integers (whole numbers).
- While waiting the 3 seconds after a wrong answer, prevent submitting another answer.
- Keep the vertical addition layout visually clear and easy for early learners to read.
- Add **carryover input boxes by place value** above the vertical problem:
  - ones carry box always visible
  - tens carry box when a tens column is present
  - hundreds carry box when a hundreds column is present
- Carryover boxes are for practice visuals only: do **not** use them in calculations, validation, scoring, or answer checking.
