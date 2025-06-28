### ✅ NEG01
**Title:** Submit empty city and country fieldsiv  
**Preconditions:** User is on 'Add Widget' page  
**Steps:**
1. Leave 'City' and 'Country' fields empty
2. Click 'Get Informer'
**Expected Result:**  
Validation error is shown or widget is not created


### ✅ NEG02
**Title:** Enter numeric values in city name  
**Preconditions:** User is on 'Add Widget' page  
**Steps:**
1. Enter '123456' into 'City' field
2. Click 'Get Informer'
**Expected Result:**  
System shows validation error or refuses to generate widget

### ✅ NEG03
**Title:** Use special characters in domain input  
**Preconditions:** Final step of widget creation  
**Steps:**
1. Enter '@!$%&*()' into 'Sites' field
2. Click 'Get Code'
**Expected Result:**  
System does not accept input and displays an error

### ✅ NEG04
**Title:** Submit form without agreeing to terms  
**Preconditions:** User has filled all required fields  
**Steps:**
1. Do not check 'I agree' box
2. Click 'Get Code'
**Expected Result:**  
Form is not submitted and warning is displayed

### ✅ NEG05
**Title:** Submit invalid domain names  
**Preconditions:** User is on final steps  
**Steps:**
1. Enter 'invalid_domain' as website
2. Click 'Get Code'
**Expected Result:**  
Error message shown or field marked invalid

### ✅ NEG06
**Title:** Paste JavaScript code in input field  
**Preconditions:** Widget creation page is open  
**Steps:**
1. Enter '<script>alert(1)</script>' in 'City' field
2. Submit form
**Expected Result:**  
Input is sanitized and script is rejected
