# This is an example checklist of simple registration form. The registration includes the following fields: Name, Lastname, Country, Cell phone, About myself, Photo.
The special parametrs for the fields are the followings:
       
1. Name -  Type: Text field, Mandatory: Yes, Length: 3–30, Rule: Contains English letters and numbers
2. Last name - Type:Text field,  Mandatory:Yes, Length: 5–50, Rule:Contains English letters and numbers
3. Country - Type:Dropdown list, Mandatory:No ,  Length:N/A, Rule:Contains 3 countries: the USA, Australia,and the UK
4. Cell phone - Type:Text field, Mandatory:No,  Length:7–20, Rule:Contains numbers
5. About myself - Type:Text field, Mandatory:No,  Length:Up to 500, Rule:Contains English letters, numbers, and special characters
6. Photo - Type:File field, Mandatory:Yes,  Length:N/A, Rule: Accepts uploads of images in .png or .jpg format with a maximum size of 7 Mb
7. Sign up button - Type:Button


# The acceptance criteria for testing are the following:
1. If a user enters incorrect data, the error message "Please check the entered data" appears,
and the field with incorrect data is highlighted in red.
2. After clicking on the "Cancel" button, all the fields are cleared.
3. After clicking on the "Sign up" button, the following confirmation message appears: "Your
account has been successfully created." The account page opens.
