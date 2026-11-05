Hospital Management System – Test Cases

1. Patient Registration Module

Test ID| Test Scenario| Input| Expected Output
TC01| Valid patient registration| Valid patient details| Registration successful
TC02| Empty patient name| Blank name| Error message
TC03| Invalid email| abc@| Invalid email message
TC04| Duplicate patient ID| Existing patient ID| Duplicate ID error
TC05| Valid phone number| Valid phone number| Number accepted

2. Doctor Management Module

Test ID| Test Scenario| Input| Expected Output
TC06| Add doctor| Valid doctor details| Doctor added
TC07| Empty doctor name| Blank name| Error message
TC08| Update doctor| Modified details| Details updated
TC09| Delete doctor| Existing doctor ID| Doctor deleted
TC10| Search doctor| Existing doctor name| Doctor details displayed

3. Appointment Management Module

Test ID| Test Scenario| Input| Expected Output
TC11| Book appointment| Valid appointment details| Appointment booked
TC12| Empty appointment date| Blank date| Error message
TC13| Unavailable time slot| Occupied slot| Unavailable message
TC14| Cancel appointment| Existing appointment| Appointment cancelled
TC15| View appointments| Valid patient ID| Appointment history displayed

4. Medical Records Module

Test ID| Test Scenario| Input| Expected Output
TC16| Add medical record| Valid medical details| Record saved
TC17| Search patient record| Existing patient ID| Record displayed
TC18| Invalid patient ID| Unknown patient ID| Record not found
TC19| Update medical record| Modified details| Record updated
TC20| View medical history| Existing patient ID| History displayed

5. Billing Management Module

Test ID| Test Scenario| Input| Expected Output
TC21| Generate bill| Valid billing details| Bill generated
TC22| Calculate total| Valid charges| Correct total
TC23| Empty billing details| Blank fields| Validation error
TC24| View bill| Existing bill ID| Bill displayed
TC25| Invalid bill ID| Unknown bill ID| Bill not found

Conclusion

These test cases are designed to verify the functionality of the Hospital Management System. Actual output and Pass/Fail status should be recorded after executing each test case.
