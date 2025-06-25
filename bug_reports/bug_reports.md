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
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_1.txt)



<--------------------------------------------------------------------------------------------------------->

# 🐞 Bug Report №2 
On Advertising feedback page - Form Submission Fails with error "Captcha is not found" - When submiting advertising order form 

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- English version of website is opened
- Home page is opened

# Steps
1. Go to: https://www.weather-stream.com
2. Scroll down and click the ""ORDER ADVERTISING"" button
3. On the advertising page, scroll to the price table, and click any option
4. In the popup carousel, click ""Order Service"" to proceed
5. On the feedback form page, fill in the required fields (name, email)
6. Click the ""SEND"" button"" 


# Expected result
The form submits successfully

# Actual Result
- The form does not submit
- The error appears in the bottom left corner: ""Captcha is not found
# Screenshots
[Open to see Screenshot of bug 2](../screenshots/bug_2.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_2.txt)


<--------------------------------------------------------------------------------------------------------->

# 🐞 Bug Report №3 
On the Home Page - Header logo image missing - only title text appears

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- French version of website is opened
- Home page is opened

# Steps
1. Go to: https://www.pogoda.fr/
2. Observe the header section (top-left)

# Expected result
The logo image should be displayed in the header

# Actual Result
- The logo image is not displayed
- Instead, only the title or alt text is visible in the header
# Screenshots
[Open to see Screenshot of bug 3](../screenshots/bug_3.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_3.txt)



<--------------------------------------------------------------------------------------------------------->

# 🐞 Bug Report №4 
In the header -  Profile image missing - only title text appears (french website)

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- French version of website is opened
- Home page is opened

# Steps
1. Go to: https://www.pogoda.fr/
2. Observe the header section (top-right)

# Expected result
- The profile image is not displayed
- Instead, only the title or alt text is visible in the header

# Actual Result
- The logo image is not displayed
- Instead, only the title or alt text is visible in the header
# Screenshots
[Open to see Screenshot of bug 4](../screenshots/bug_4.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_4.txt)


<--------------------------------------------------------------------------------------------------------->

# 🐞 Bug Report №5 
In the header -  Profile image missing - only title text appears (spanish website))

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- Home page is opened
- Spanish version of website is opened

# Steps
1. Go to: https://www.pogoda.es/ 
2. Observe the header section (top-right).

# Expected result
The profile image should be displayed in the header

# Actual Result
- The profile image is not displayed
- Instead, only the title or alt text is visible in the header
# Screenshots
[Open to see Screenshot of bug 5](../screenshots/bug_5.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_5.txt)


<--------------------------------------------------------------------------------------------------------->

# 🐞 Bug Report №6 
In the header -  Profile image missing - only title text appears (russian website)

# Environment
macOS: Sequoia 15.2 (24C101),  Browser: Chrome Version 137.0.7151.104 (Official Build) (x86_64)
# Preconditions 

- User is logged in  
- Home page is opened
- Russian version of website is opened

# Steps
1. Go to: https://www.pogoda.com.ru/ 
2. Observe the header section (top-right)

# Expected result
The profile image should be displayed in the header

# Actual Result
- The profile image is not displayed
- Instead, only the title or alt text is visible in the header
# Screenshots
[Open to see Screenshot of bug 6](../screenshots/bug_6.jpeg)
# Logs
[Open to see log.txt of bug 1](../logs/www.weather-stream.com-bug_6.txt)




