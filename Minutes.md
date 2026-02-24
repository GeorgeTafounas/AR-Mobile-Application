
# 📅 Project Timeline & Sprints

## Upcoming Deadlines

* **23/04:** Submission
* **21/04:** (Open)
* **14/04:** Easter Break
* **07/04:** Easter Break — Create presentation
* **31/03:** (Open)
* **24/03:** Start Sprint 4 (Finalise product)
* **17/03:** (Open)
* **10/03:** Start Sprint 3 (Develop dynamics)
* **03/03:** (Open)

---

## 24/02 — Start Sprint 2: Initialise Product

**Completed Tasks**

* Add AR camera
* Created two branches: one for UI and one for interactions (working on separate scenes and branches)

**Next Task**

* Add script to place an object and interaction

### Unity Quick Guide: Find a Lost Scene

1. Go to your **Project window** (where your files are).
2. Click on the root **Assets** folder on the left side.
3. In the search bar at the top right of the Project window, type exactly this: `t:Scene`
4. This filters out all scripts, materials, and models. If your Scene is anywhere in your project, it will instantly appear right here.

---

## 17/02 & 10/02 — Start Sprint 1: Set Up Project

**Milestones**

* Approved idea by tutor
* Suggestion received: Make sure to have gamifying elements

**Sprint 1 Task Assignments**

* **GIORGOS:** Set up the GitHub repository and the Unity `.gitignore` to ensure version control works. Research AR Foundation and list possible features for the app.
* **KAT:** Create notes to keep track of progress. Write a script so that when the cube is tapped, there is a color change or a sound is played to show engagement.
* **ALEX:** Set up Trello and email about team’s roles. Find 2 existing AR apps and list what makes them engaging and accessible (e.g., Pokemon Go). Add a simple UI button.
* **ALL:** Get Unity running on a phone. Be able to open the camera, detect the floor, and place an object.

---

## 03/02 — Weekly Session Prep

**Deliverables for 10/02 Session (11:00-12:00)**

1. Present/Describe the research done (existing similar applications, capabilities, key functionality).
2. Demonstrate the First prototype (read the Assignment Brief carefully to extract user requirements).
3. Each team member must explain what they have done so far and how they contributed based on their Team Role.

### Target Audience & User Requirements

* **Primary Users:** New students who have declared a disability (Mobility, Sensory impairment, Neurodivergence, Mental health conditions).
* **Goals:** Help users get to know the university, find support, and preview student life.
* **Vibe:** Fun, engaging, encourages inclusion, and helps students meet others.
* **Context:** Addition to the STAR (Student Transition and Residential) programme. Includes meeting wellbeing ambassadors and an online FB group.
* **Tech Requirements:** Usable, accessible, engaging, and shows good use of AR.

### iOS Build Guide (Unity to Xcode)

**Tools Required:** Unity, VS Code, AR Foundation, Xcode, GitHub, a Mac, and a free Apple ID.

**1. Activate AR Engines**

* Open your project in Unity.
* Go to **Edit > Project Settings > XR Plug-in Management**.
* Click the Apple icon tab and check **ARKit**.

**2. Switch Platform**

* Go to **File > Build Settings**.
* Select **iOS** and click **Switch Platform** (bottom right). Wait for the progress bar.

**3. Configure Player Settings (Crucial for AR)**

* In Build Settings, click **Player Settings** (bottom left) and expand **Other Settings**.
* **Bundle Identifier:** Change this to something unique (e.g., `com.GroupName.StarProject`).
* **Camera Usage Description:** You MUST type a reason here (e.g., "Required for AR experience"). The app will crash if left blank.
* **Target Minimum iOS Version:** Set to 11.0 or higher.

**4. Build & Deploy via Xcode**

* Click **Build** and save it in a new folder named "Builds".
* Open the `.xcodeproj` file in that new folder to launch Xcode.
* Click the blue project icon on the top left, select the **Signing & Capabilities** tab, and set your Team to your personal Apple ID.
* Connect your iPhone via USB, select it in the top device bar, and click the **Play (Run)** button.

**5. Trust the App**

* If the install fails with an "Untrusted Developer" error, go to your iPhone **Settings > General > VPN & Device Management** (or Profiles). Tap your email and click **Trust**.

---

## 27/01 — Product Idea & Roles

**Product Concept:** Accessibility-focused navigation app for university campuses.

* Supports students with mobility issues in navigating halls and facilities.
* Digital campus layout generates multiple accessible path options.
* Flyers placed at key locations act as image targets (using the logo instead of QR codes). Scanning a flyer opens a pop-up list of destinations.
* Selecting a destination displays the navigation route.
* Menu with floating 3D buttons (AR coordinate system).
* **Gamification:** Users get points once they discover a new location, guided by a friendly mascot.
* **Future Features:** Voice navigation for blind students, high contrast UI for low vision, clear/simple structure for neurodivergence.

**Questions for Tutor:** * Is the product idea approved?

* Can the demo run on the university network, and can it be a video/screenshots instead of live?

### Team Roles & Responsibilities

* **GIORGOS (Git Manager):** Manages the GitHub repository (merge conflicts), focuses on core AR mechanics (camera, tracking).
* **KAT (Logic Dev):** Records meeting notes, focuses on interaction scripts (touch input, game logic).
* **ALEX (UI Dev):** Acts as the bridge to the "Client" (Lab Tutor), ensures agile principles are used, manages the Presentation, focuses on UI/UX code.
* **ALL:** Keep the "Sprint Board" (Trello) updated.

---

## 20/01 — Project Kickoff (13 weeks until submission)

**Initial Setup Tasks**

* Create GitHub repository and set up Unity.
* Create a Trello board, a WhatsApp group, and a shared document.

### Brief Summary & Assessment Breakdown

* **Tech Stack:** Mobile application, Unity Engine, C# or C++. (All members must contribute to the code).
* **Deliverables:** Artefact files and Presentation slides (23 April). Individual Report (5-6 pages, 50%) on 29 April.
* **Marking Categories (25% each):**
* **Planning & Design:** Clear concept, adheres to brief and user needs.
* **Product:** Evidence of testing, working demo.
* **Process:** Use of agile practices, reflection on methods/frameworks, discussion of strengths/weaknesses and alternative approaches.
* **Presentation:** Organised slides, analysis of the problem using diagrams, evaluation of agile techniques and tools. Must show good understanding, minimal notes, and be engaging (approx. 20 mins around 28 April).


