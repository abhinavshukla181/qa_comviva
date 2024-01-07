Test id: TC001
Description: verifying WhatsApp messaging functuinality

        steps:
            1) Open whatsApp web link by "https://web.whatsapp.com/" in browser.
            2) Login to whatsapp by valid mobile number using opt verification.
            3) Select a saved contact and open messeging section.
            4) Click on new message block and enter some text message.
            5) click on send button 
        Expected outputs step wise:
            1) Whats app web page will displayed on browser which asks for login
            2) Successful login will show  recent chats section on screen.
            3) Chat section will open for that particular contact.
            4) Cursor will change from arrow to blinking straight line.
            5) new message will be displayed with double tick in chat section.


Prerequsites: 
            1) valid and active mobile number which can recieve authentication otp.
            2) stable and fast internet connection.
            3) saved contact number in device.

Test Result: Message should be sent successfuly to another contact.
Test Resul Status: Passed

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Test id: TC002
Description: verifying WhatsApp Status functuinality
        steps:
            1) Open whatsApp web link by "https://web.whatsapp.com/" in browser.
            2) Login to whatsapp by valid mobile number using opt verification.
            3) Click on Status option on top of chat section
            4) Click any saved contact.
            5) click on back arrow on top left hand side to go back to chat section.
        Expected outputs step wise:
            1) Whats app web page will displayed on browser which asks for login
            2) Successful login will show  recent chats section on screen.
            3) Status section will displayed on screen which has multiple saved contact names.
            4) Status of selected contact will be shown on screen.
            5) whats home screen will be displayed.

Prerequsites: 
            1) valid and active mobile number which can recieve authentication otp.
            2) stable and fast internet connection.
            3) saved contact number in device.
            4) saved contact should have posted a story in whatsapp status.

Test Result: contact story should displayed.
Test Result Status: Passed

