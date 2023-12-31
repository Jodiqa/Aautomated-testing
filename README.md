Test
- Create a "Base Test" class.
- Create a "Login Page Test" class, which will contain test cases for the page: https://webapi1.srbvoz.rs/ekarta/app/#!/login
*Write the following test cases:
1.Go to the page and verify that the subtitle has the text "PRIJAVA NA SISTEM ILI REGISTRACIJA".
2.Fill in all the fields, but enter an invalid email as email. After clicking on the "Registracija" button, verify that the message "Molimo Vas sačekajte" is displayed 
(note - the application has a bug and this message is not always visible)
3. Click on the first checkbox, then verify that the first checkbox is checked, and that the second checkbox is not checked. 
Then click on the second checkbox and verify that it is checked.

- Create "Home Page" test class for the page https://webapi1.srbvoz.rs/ekarta/app/#!/home
*Write the following test case:
-Enter "be" in the "Stanica OD" field, then select Beograd Centar  from the menu.
-Enter "no" in the "Stanica DO" field, then select Novi Sad from the menu.
- Open the calendar, click on the right arrow, and select day "01" (active date).
-Click on the "Traži" button.
-Click on the first button "Izaberi".
-Click on the "Dalje" button.
- Verify that the message on the next page contains the text "Broj putnika" (there is no need to create a new Page class for that page).
