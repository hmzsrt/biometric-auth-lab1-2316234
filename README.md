# biometric-auth-lab1-2316234

# Lab 1 - Fingerprint System
Name: Hamza mohammed
Student ID: 2316234
 
## Quiz answers
Q1: C  Q2: B  Q3: D  Q4: B
Q5: A  Q6: C  Q7: D  Q8: A
Q9: B  Q10: B  Q11: A  Q12: D
Q13: C  Q14: A  Q15: B  Q16: D
 
## My results
Genuine average score: 60.4
Impostor average score: 3.4
My threshold for a phone: 10 (FMR 1.11% FNMR 0.0%)
My threshold for a bank vault: 15 (FMR 0.00% FNMR 0.0%)
 
## Reflection (2 sentences each)
1. **What was the most difficult step and how did you solve it?**
   The most difficult step was getting a `NameError` because the `database` variable was not defined when running the comparison loop. I solved it by restarting the kernel and running all cells in order from top to bottom so that the enrolment cell executed first.
2. **Why is a perfect fingerprint system impossible?**
   A perfect fingerprint system is impossible because real-world scans vary every time due to changes in finger position, rotation, pressure, and skin dryness. Additionally, lowering the threshold to accept every genuine user increases false matches (FMR), while raising it to block all impostors increases false rejections (FNMR).
3. **Where could this kind of system be used, and what could go wrong?**
   This system could be used to unlock smartphones or secure office doors. However, if a user has a wet finger or only places half of their finger on the sensor, the system might falsely reject a genuine user, or a low threshold could allow an unauthorized impostor inside.
