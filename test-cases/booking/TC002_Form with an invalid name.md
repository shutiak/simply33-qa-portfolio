### Test Case ID: TC002  
**Target Description**: Attempt to submit reservation form with an invalid name  
**Suite**: Booking  
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en 
2. Reservation form is visible and active  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click the "Reserve Now" button | The page scrolls smoothly to the reservation section located on the same page | ✅ | |
| 2 | Input the following data into the reservation form:<br>• Name: "@@@123"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: any future date<br>• Time: available time<br>• Guests: 4<br>• Note: optional | The "Name" field is marked as invalid (e.g., highlighted in red or a validation message appears) | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |
| 3 | Click the "Reserve" button | The form is not submitted. User is prompted to correct the invalid "Name" field | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
