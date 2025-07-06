# workingmechanism
---
## Key Code Features:

- Initializes the LCD and keypad

- Monitors button presses to accept user PIN

- Compares entered PIN with predefined PIN

- Controls relay and buzzer based on validation

- Allows reset and verification commands through keypad

---

##  Working 

1. **System Initialization**
  
2. **PIN Entry & Validation**  
   - User is prompted to enter a 4-digit PIN using the keypad.
   - The system compares the input with the predefined PIN (`"1111"` by default).
     
3. **Feedback Mechanism**  
   - If the PIN is correct:
     - LCD displays "Successful"
     - Buzzer beeps once
   - If the PIN is incorrect:
     - LCD displays "Wrong PIN!"
     - Buzzer beeps 3 times
       
4. **Command Functions**  
   - Clear the entered PIN using a specific key (`D`)
   - Submit/verify PIN using another key (`C`)

5. **Security Enhancements**  
   - PIN input resets automatically after validation
   - Optional: You can add features like attempt limits, lockout time, or logs
