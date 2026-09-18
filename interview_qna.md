# Interview Questions & Answers

**1. What is the purpose of if-elif-else?**[span_13](start_span)[span_13](end_span)
**Answer:** `if-elif-else` statements ka use program mein decision making ke liye hota hai. Yeh allow karta hai ki multiple conditions check ki jayein, aur jo pehli condition `True` ho, uske corresponding code block ko execute kiya jaye.

**2. How would you handle invalid marks?**[span_14](start_span)[span_14](end_span)
**Answer:** Invalid marks (jaise negative numbers ya 100 se zyada) ko handle karne ke liye main grading logic ke shuru mein hi ek `if` condition lagaunga: `if marks < 0 or marks > 100: return "Invalid"`. Isse galat data aage process nahi hoga.

**3. Can conditional statements be used while processing datasets?**[span_15](start_span)[span_15](end_span)
**Answer:** Haan, bilkul. Hum loops (jaise `for` loop) ka use karke dataset ke har ek row ya element par iterate kar sakte hain aur unke andar conditional statements laga kar specific rules ya logic (jaise grading, filtering, formatting) apply kar sakte hain.
