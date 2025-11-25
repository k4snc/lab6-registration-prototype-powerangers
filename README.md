# About Prototype
A high-fidelity web prototype for **ElekSure**, a platform designed to promote transparency in Barangay elections, was created to feature a complete Sign-In and Sign-Up user journey with role-based access for Voters and Candidates.

# Team Roles

**Gerong**: Lead Developer & UI Designer
  * Implemented the core JavaScript logic for user authentication, input validation, and dynamic screen navigation.
  * Designed the visual interface using CSS3, including the color scheme, typography, and the mobile phone simulation frame to ensure high-fidelity realism.

**Jabien**: Documentation Lead
  * Managed the GitHub repository structure, and documented the setup instructions to ensure the prototype runs locally.
  * Managed file directory organization to ensure proper linking of external resources.
    
**Moneva**: Quality Assurance (Functionality)
  * Conducted a trial usability testing to verify all navigation flows and button interactivity.
  * Verified that the "Success" state correctly redirects to the Dashboard.

**Patlonag**: Quality Assurance (Error Handling)
  * Validated error message triggers, ensuring invalid credentials and password mismatches block registration as intended.

**Roble**: User Experience Tester
  * Tested the responsiveness of the phone frame layout and ensured the "Show Password" toggles function correctly across different screens.

# Technology Stack
* **HTML5:** Used for the semantic structure of the application, including form elements and container layouts.
* **CSS3:** Utilized for high-fidelity styling, including:
    * **Flexbox:** For centering the phone frame and responsive layout alignment.
    * **CSS Variables:** To maintain a consistent color theme.
    * **Keyframe Animations:** For the smooth slide-up effects when switching screens.
* **Vanilla JavaScript (ES6):** Handles all client-side logic without external frameworks:
    * **DOM Manipulation:** Dynamically switching between Login, Sign-Up, and Dashboard screens.
    * **Form Validation:** Real-time checking of email formats and password matching.
    * **LocalStorage API:** Simulates a backend database to persist user registration data locally in the browser.
      
# Methods in Accessing Locally
### 1. Download the Zip file (Recommended)
*   Scroll to the top of this repository and click the green **< > Code** button.
*   Select **Download ZIP**.
*   Locate the downloaded file and extract it.
*   Open the folder and double-click **index.html**.
*   The prototype will then launch in your default browser.

### 2. Clone the repository
```bash
   #Clone link
   git clone https://github.com/k4snc/lab6-registration-prototype-powerangers.git 
   #Locate the folder using the code below then open index.html
   cd lab6-registration-prototype-powerangers
```
# Additional Notes
### Commit Contribution
> During the development phase, our team utilized external coding websites such as OnlineGDB and OneCompiler.
>
> Because we've consolidated our code externally before deploying to GitHub, the repository's **commit history** reflects the upload of the final, polished prototype rather than the line-by-line changes.
>
> Please refer to the **Team Roles** section above for the accurate and detailed breakdown of each member's specific contributions to the project logic, design, and testing.
