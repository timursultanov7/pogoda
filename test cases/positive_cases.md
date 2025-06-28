### ✅ TC01
**Title:** Display weather for Tel Aviv  
**Preconditions:** User is on homepage  
**Steps:**
1. Open homepage 
2. Type “Tel Aviv” into the search field
3. Press Enter  
**Expected Result:**  
Weather data for Tel Aviv is shown: temperature, humidity, wind, and icons

### ✅ TC02
**Title:** Display homepage correctly  
**Preconditions:** User is not logged in, has internet connection  
**Steps:**
1. Open https://www.weather-stream.com/ 
**Expected Result:**  
Homepage loads successfully and displays the main header and content blocks

### ✅ TC03
**Title:** Create weather widget – step-by-step flow  
**Preconditions:** Homepage is loaded  
**Steps:**
1. Scroll down
2. Click 'CREATE YOUR WEATHER WIDGET' button
3. Click 'Add Widget' on the next page
**Expected Result:**  
User is taken to widget creation steps

### ✅ TC04
**Title:** Enter valid location  
**Preconditions:** On Add Widget page, City tab active 
**Steps:**
1. Enter 'Tel Aviv' and 'Israel'
2. Click 'Get Informer'
**Expected Result:**  
Widget preview loads correctly with Tel Aviv weather

### ✅ TC05
**Title:** Enter valid website domain  
**Preconditions:** Widget form open 
**Steps:**
1. Enter 'google.com' into 'Sites' field
2. Check the license agreement
3. Click 'Get Code'
**Expected Result:**  
Widget code is generated and shown to user

### ✅ TC06
**Title:** Check 'I agree' checkbox functionality  
**Preconditions:** User is on final step of widget creation 
**Steps:**
1. Try to proceed without checking the box
2. Then check it and click again
**Expected Result:**  
Form only submits when the checkbox is selected

### ✅ TC07
**Title:** Verify widget preview is displayed  
**Preconditions:** Valid city and country entered 
**Steps:**
1. Fill in 'Israel' and 'Tel Aviv'
2. Click 'Get Informer'
**Expected Result:**  
Widget preview is shown below the form

### ✅ TC08
**Title:** Verify site language is English by default  
**Preconditions:** Homepage opened from Israel 
**Steps:**
1. Load site
2. Check language of headers and buttons"
**Expected Result:**  
All text is displayed in English

### ✅ TC09
**Title:** Access widget code without error  
**Preconditions:** Form completed correctly 
**Steps:**
1. Submit widget form
2. Click on 'Get Code'
**Expected Result:**  
Code appears and can be copied
