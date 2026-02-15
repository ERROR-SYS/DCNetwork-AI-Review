# DCNetwork AI Platform - Review | 15th February 2026
_Please open an issue if you have any suggestions._
- **Categories**:
  - AI Improvements.
  - UX Improvements.
  - UI Improvements.
  - Bug Fixes.

___
## UX Improvements:
   **_1._** The title only covers the last request, not the whole conversation.<br><br>
      <img width="709" height="669" alt="image" src="https://github.com/user-attachments/assets/94bee7a2-68f7-4594-ba2f-9847d2adbe2b" />
___
   **_2._** Instead of showing a short description of the conversation, the UI shows the last request made by the user.<br><br>
     <img width="701" height="672" alt="image" src="https://github.com/user-attachments/assets/937d69e4-232c-448c-aaf6-a029798c28fa" />
___
   **_3._** The wallet’s profile doesn’t change when the connected wallet changes. <br>
     _**Suggestion:** Use the same profile shown in the menu it will fix the bug and it’s good to quickly recognise the wallet._ <br><br>
      <img width="915" height="513" alt="image" src="https://github.com/user-attachments/assets/f62f0b0d-f4d8-479e-aebd-d450eb6d42ef" />
___
   **_4._** The model's icon doesn’t change when using a profile different from Lucy. <br><br>
     <img width="918" height="339" alt="image" src="https://github.com/user-attachments/assets/740fbbb6-bb77-458d-9c4e-95e4c360c517" />
___
   **_5._** Add “Export conversation” to the chat's options.<br>
     <img width="280" height="147" alt="image" src="https://github.com/user-attachments/assets/2d8d7176-f011-4a62-99fd-7b6b02c0dff0" />
___
## UI Improvements:
   **_1._** Align the learning center’s main container.<br><br>
     <img width="787" height="706" alt="image" src="https://github.com/user-attachments/assets/698422f6-e718-47a7-9eb7-92497827260a" /><br><br>
     It should look like this: <br><br>
     <img width="794" height="715" alt="image" src="https://github.com/user-attachments/assets/4b453991-aca3-4e1e-b1f9-035394aeea89" /><br><br>
     Style used to fix the alignement:<br>
     `.h-screen.overflow-hidden .text-foreground.min-h-screen { width: 100vw }`
___
   **_2._** We don’t need to have two links for the app, and the docs link is useless since it’s linked to the same page.<br><br>
     <img width="668" height="758" alt="image" src="https://github.com/user-attachments/assets/f0d477ce-fc75-4ce2-8571-e6cda88dbf06" /><br><br>
___
   **_3._** Move the ‘info’ icon next to the subtitle “Switch Profile”.<br><br>
     <img width="712" height="673" alt="image" src="https://github.com/user-attachments/assets/330860ba-e247-4fb2-a5b4-773d4c9b1e7b" />
___
## Bug Fixes:
   **_1._** Fix the logo when the side menu is closed.<br>
     _**Suggestion:** Remake the menu's structure as in the screenshot, make an upper part that contains the logo, profile and wallet (shown in green) and a left part that contains the settings, untoggle menu and learning center link (shown in blue)._ <br><br>
     <img width="824" height="559" alt="image" src="https://github.com/user-attachments/assets/394264cc-6783-4ab1-bf31-bd5e0a96f9cd" /><br><br>
   **_2._** This button shouldn’t disappear when clicked.<br><br>
     <img width="284" height="367" alt="image" src="https://github.com/user-attachments/assets/cba25df7-66cd-4ec6-bf80-4f0d7b9465fc" />
___
## Previous Suggestions:
_These are suggestions made in the previous review that were not applied to the new version of the platform. I'm listing them here in case they were overlooked._<br>
___
   **_1._** Unify the website's language, the wallet's menu adapts to the user's region while the rest of the platform is in English.<br><br>
     _**Note:** I think it's better to set the menu's language to English instead of translating the whole platform into different languages because adding them requires a new paging system and high quality translations for each of them._
___
   **_2._** Remove the hover animation that makes the wallet button grow and decrease the `border-radius` to `5px` because it doesn't match the rest of the platform.<br><br>
   <img width="829" height="718" alt="image" src="https://github.com/user-attachments/assets/1068e36d-6320-4c8f-8fa3-b5801b649ad1" />
___

This review is based on the functions I tested, once these changes are applied, I will do more testings and will update if I find anything.<br><br>
_**Note:** I recommend adding IDs to the containers I mentioned and to apply the styles using them instead of the classes because they could affect other components, styles can also be directly applied on the HTML elements._
