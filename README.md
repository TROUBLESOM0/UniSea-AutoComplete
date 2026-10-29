# UniSea Checklist Automation

:heavy_exclamation_mark: <i>Currently in early stages of development and may have bugs/issues.</i>

## Overview

This is a Puppeteer application powered by Node.js that automatically fills out repetitive checklist forms, saving hours of manual data entry every week.  The application provides a web form to store login credentials and the criteria used to complete the checklists.   All information is stored on the user's device.  The app was made portable to allow multiple users to run it from the same machine or from a thumbdrive.
<br><br>

## User Preferences

Language: English <br>
Style: Simple
<br><br>

## Usage

###  Initial Log-in <br>
<img width="480" height="427" alt="unisea_login" src="https://github.com/user-attachments/assets/18536fa6-ee33-4a54-8052-1c5da1535b81" />


<br>
<br>

  **Root Address**  
      Enter the root URL for the UniSea web address (e.g. "unisea.choues.com", "192.169.60.40").  
      :information_source: The script should be able to handle any string placed here but,  
      :eight_spoked_asterisk: For best results leave off any trailing "/" (backslashes).

  **Username**  
      The username used to sign-in.

  **Password**  
      The password used to sign-in.
  
###  User Inputs <br>
<img width="480" height="618" alt="data_form" src="https://github.com/user-attachments/assets/a205f72b-6414-4cc9-9b84-9f85eb683f3a" />



<br>
<br>

   Data required to complete the form.  
   <i>Anything that can be typed in the normal checklist can be typed here</i> <br>
   > :NOTE: <br>
   > Typing "UHD123" will fail because it can not be referenced in the drop-down on the web form. <br>
   > It must be typed as **UHD-123**.  You can also type "123" as long as only (1) reference exists.
   
   <br><br>

## Closure <br>

   The application will not submit the form, so, you will have a chance to review before sending.  
   <!-- A license agreement is attached for information on what you CAN and CAN NOT do with the software. -->
   I will try to provide updates for security purposes and fixes as they come up.
   <br>
   Eventually, I hope to package all the checklists into One App.
   
