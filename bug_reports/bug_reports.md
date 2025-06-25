# 🐞 Bug Report №1 
On Weather Widgets Page - Form Submission Fails with error "Captcha is not found"  - When submiting "Get Informer Code" form

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- English version of website is opened
- Home page is opened

# Steps
1. Go to https://www.weather-stream.com/ 
2. Scroll down and click the ""CREATE YOUR WEATHER WIDGET"" button
3. On Weather Widgets Page click on ""Add Widget"" button
4. Click the ""City"" tab from the tabs 
5. Type Country - ""Israel"" and City -  ""Tel Aviv"" in the input fields
6. Click the ""Get Informer Code"" button
7. In the form, type website address:  www.google.com  into the ""Sites"" input 
8. Select  ""I agree with license to use the widget"" checkbox
9. Click the button ""Get Code"" 


# Expected result
The form submits successfully

# Actual Result
- The form does not submit
- The error appears in the bottom left corner: ""Captcha is not found
# Screenshots
[Open to see Screenshot of bug 1](../screenshots/bug_1.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_2.txt)
