# Too Long ; Didn't Read :sleeping:

I like to be conscious of others' time. Below please find my solutions for the prompts you've provided.

<p align="center">
  <img src="https://github.com/user-attachments/assets/56dbb810-fdb1-4547-a489-26c8ea0b5326" alt="Centered Image">
</p>

## Jump to:
- [1. Functional Requirements](#1-functional-needs-requirements)
  
- [2. UI/UX Requirements](#2-uiux-requirements)
  
- [3. Technical Requirements](#3-technical-requirements)
  
- [4. Transitional Requirements](#4-transitional-requirements)
  
- [Additionally: Project & Product Management](#additionally)
  
- [Bonus: Reader Room](#bonus)



# 1. Functional Needs (Requirements)
## What questions would you ask the librarians in regards to the functional needs (requirements) of the system?

1. **Current System Usage**: 
   - "Can you walk me through how you currently use your paper-based card catalog for lending and returning books?
(Buy-in is extremely important from the beginning, and this allows the librarian time to give that librarian-esque deeper dive into the subject of categorization by subject, author, shelf, etc.)
     
2. **Preferred Features**: 
   - "Are there any features from your current system that you really like and would want to keep in the new system?"
     
3. **Reservations and Hold Requests**: 
   - "How would you like the system to manage book reservations and hold requests?"
     
4. **Lending Policies**: 
   - "What are your current policies for lending periods, renewals, and handling late fees?"
     
5. **Media Types**: 
   - "What kinds of media are in the system now, and what new types would you like the new system to support?"




# 2. UI/UX Requirements
## What questions would you ask the librarians in regards to the UI/UX requirements of the system?
1. **Interface Preferences**: 
   - "What kind of look and feel are you envisioning for the system’s interface? Any design preferences or themes? How about a motif?"
     
2. **User Experience**: 
   - "How should the system accommodate users with varying levels of tech-savviness? Are there any accessibility requirements for patrons with disabilities?"
     
3. **Search Functionality**: 
   - "How do you want the search functionality to work for finding books in the catalog? Should it include e-books, e-audiobooks, physical books, and databases?"
     
4. **Navigation Features**: 
   - "Are there any navigation features that are particularly important to you, like quick links or shortcuts?"
     
5. **Feedback and Customization**: 
   - "How should users (both librarians and patrons) be able to provide feedback on the system? Should the system allow for customization by the library staff?"




# 3. Technical Requirements
## What questions would you ask the librarians in regards to the technical requirements of the system?
1. **System Integration**: 
   - "I'm sure you're familiar with the Integrated Library System. Are there any existing digital systems or databases from working with them that the new system needs to integrate with?"
     
2. **Data Migration**: 
   - "What are the data migration requirements from the current paper-based system to the new digital system? Do you already have some .MARC files for bibliogrpahic material (required for all)?"
     
3. **Security and Data Privacy**: 
   - "What are the security requirements for protecting patron data and book inventory information? How should the system handle authentication and authorization for librarians and patrons?"
     
4. **Scalability and Performance**: 
   - "What are the expected peak usage times, and how should the system handle high traffic periods? Are there any specific performance requirements, like response times for searches or transactions?"
     
5. **Backup and Recovery**: 
   - "What are the requirements for data backup and recovery in case of system failures or data loss?"




# 4. Transitional Requirements
## What questions would you ask the librarians in regards to the transitional requirements of the system (i.e. from catalog/paper-based system to software solution)?
1. **Change Management**: 
   - "What kind of training will be needed for librarians to transition from the paper-based system to the new digital system? How should the transition be managed to minimize disruption to library operations?"
     
2. **Data Migration**: 
   - "How much historical data from the paper-based system needs to be digitized and migrated to the new system? What is the plan for verifying the accuracy of the data after migration?"
     
3. **Support and Maintenance**: 
   - "What kind of ongoing support and maintenance will be required for the new system? Are there any specific requirements for user support, like helpdesk or tutorials?"
     
4. **Pilot Testing and Rollout**: 
   - "Would you prefer a phased rollout of the new system, starting with a pilot program, or a full-scale implementation? How will success be measured during the transition period, and what are the key milestones?"




# Additionally:

## 1. SDLC Process
### Assuming that the client is unfamiliar with the SDLC process, how would you orient them to feel comfortable with the process, to ensure they feel at ease when discussing their challenges and voicing their opinions?
"Let's envision the final result first: a fully deployed and functional library system. This kind of perfect product is going to need the maintenance and support you'll receive post-deployment, and before that, rigorous testing and feedback to ensure everything works perfectly. Before we can start the build phase, the design phase where we map out how everything will look and function my happen. That helps to figure out what we want, and to get there we have already finished the initial planning and requirements gathering. That's why I asked you so many questions! Each of these steps are part of the Software Development Cycle (SDLC), and I hope you feel at ease discussing your challenges and voicing your opinions throughout the process."

In my experiences, people know the final product they want, but they don't know how to get there. It's unconventional, but I like to start at the cart before the horse, and work my way back. After one explanation, you explain the concept again, this time from beginning to end.

## 2. Stakeholder Disagreements
### What strategies would you utilize if there was disagreement between the stakeholders as to the ‘most important’ features in the system? Or how they should function?
Should there be a disagreement between stakeholders about the 'most important' features or how they should function, I'd facilitate a collaborative discussion to understand everyone's perspective; it's amazing what the smallest bit of communication can do. I'd find a way for us to prioritize features based on factors like user impact, feasibility, and alignment with the library’s goals. Maybe we'd send them a "MoSCoW prioritization" (Must have, Should have, Could have, and Won’t have) form if they're the writing type, and that could help us reach a consensus.

## 3. Follow-Up Activities After the First Meeting
### After eliciting the high-level requirements on your first meeting, what follow-up activities would you perform to help prioritize the scope items they’ve discussed with you?
After the kickoff meeting, I’d create a low-level requirements document summarizing what we discussed. I would develop user stories or use cases to clarify functionality, draft a context diagram, and create a basic process flow of the desired system. Additionally, I think it's important to develop a prototype or wireframe of key screens to visualize the system, because we love a picture. The risk assessment matrix and a first-draft project charter would also be part of the follow-up.
### What thought exercises, or internal deliverables, would you produce to help clarify the ‘ask’ from the client for your colleagues?
I like to have some fun at work, so maybe I could put the steps into a framework of a "Quest" for gamification as follow:

- Step 1: :earth_americas: World Map

   - Action: Draw a world map with all the requirements of all the levels the Readers Room needs to go to.

- Step 2: :suspect: Playable characters

   - Action: Emulate the "create a character" screen on a game. What do they like what are their stats? If I'm working with someone nerdy like me, it's ATP and INT. For someone a little more normal, I'll ask age, gender, likes and dislikes.

- Step 3: :crossed_swords: World map connections

   - Action: Tell me how each level on the map talks to the other levels. How does each character respond each level? What battles need to be won for each connection?

- Step 4: :fire: Campfire spots

   - Action: At each campfire rest spot, what information is needed before moving to the next level?

# Bonus:
## 1. **Unique Features**
### What ‘fun or exciting’ features could you propose to the librarians to set their library apart from the crowd?
This is one of the most fun parts of the assignment, and also one where people get the most unrealistic (in a good way!).

My simple idea is a 'Reader Room' landing page in the library's web app where users can recommend books by filling out a form and provide a brief description, adding tags and categories for easier discovery. Because people like the idea of being published and involved, they could also submit formal reviews through the app to Submittable for potential publication and track their submission status directly from the app, therein teaching folks how publication work and helping the library with further grant funding. Depending on the scope of this project, the 'Reader Room' could be a virtual reading room (who doesn't love to be read to?) emulating the same system as a Twitch livestream, or a competitive section with rewards like challenges, badges, and leaderboards. By envisioning the final result first, we can then ensure every development step (planning :arrow_forward: design :arrow_forward: development :arrow_forward: testing :arrow_forward: deployment :arrow_forward: maintenance) aligns to bring the feature(s) to life.

## 2. **Feature Challenges**
### During your thought exercise (i.e. this task), what feature did you feel could pose the biggest challenge to the app being built successfully? What strategies would you recommend to manage the risks associated with that challenge?
I am a greenhorn to .NET, but I imagine from a little bit of [research](https://www.fortinet.com/resources/cyberglossary/digital-rights-management-drm) that the most challenging feature to implement would be to give security to the virtual reading rooms in a way that isn't awful to work with. It would be very cool to host live book clubs, author readings, and interactive discussions and uploading the element itself wouldn't be an issue, but the backend receives a lot of the technical complexity. To address these risks, I would start with a thorough feasibility study to understand the technical requirements and limitations. If for whatever reason, the library would decide they don't need to protect their your videos, then we'd use a player library or HTML5 video and static-host the video files with the UI only navigating and pointing to them. 

But the whole point of this project is we're trying to get them _out_ of the 19th century, and we'd still need to choose an format that encodes on all modern platforms and browsers. 

Implementing the feature in phases, beginning with simpler functionalities and gradually introducing live streaming, would help manage the complexity. Maybe we'd choose basic HTML5, standard video formats, and a fallback to some Java player using an object tag. Maybe it's even simpler though, and we simply leverage and established platform like Google Meet or Twitch which could ensure reliability and save development time. These would still have metrics allowing for grant writing. We'd continue to conduct user testing and gathering feedback, establishing support and maintenance, and continue to develp a risk management plan beyond the topics I've touched upon above.

## 3. **Operational Requirement Questions**
### What if any operational requirements questions would you ask the librarians?
I'd ask a lot of the same questions I've asked above, but will touch on the most important questions here.
- "How will access to the Readers Room be managed, and what policies would be in place to ensure fair and efficient use of the space?
  
- What types of resources should be readily available in the Readers Room? How will these resources be organized and accessed by patrons?
  
- Most importantly, are there any other specific services or programs that you believe would enhance your patrons' experience in the Readers Room?


[Back to Skills Assessment - Business Analysis](https://github.com/jonnyblevins/TWCSkillsAssessment/blob/main/README.md)
