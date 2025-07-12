# Telegram Android Contest 2025 - Profile Redesign

This project is a submission for the **Telegram Android Contest 2025 - Round 1**.  
The goal is to redesign the profile screens of Telegram (users, groups, channels, businesses) following the official mockups provided by the Telegram team.  
All features, transitions, and layouts strictly follow the contest requirements.

## Screenshots

![Untitled-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/b47e3387-f0fc-4d80-9c13-44be8f991b3a)
![Screenshot_20250712_174115_contest farid telegram web](https://github.com/user-attachments/assets/5dd1f5a6-38fb-44bf-aceb-c7b2e615986f)

## Contest Compliance

- Written entirely in Java
- No third-party UI frameworks used
- Performance and stability maintained
- All mockups and transitions implemented accurately


## Tech Stack

- Language: Java
- Framework: Native Android SDK
- No third-party UI libraries used (as per contest rules)

## Project Structure and New Changes
**Note: ** Google play service for notifications has been disabled to have more time for developing app instead of creating api keys.

- **AndroidUtilities.java** updated with adding some helper functions
- **NotchDropView.java** addde for profile top notch view
- **ProfileHeaderQuickActions.java** added for profile quick actions section (it would be better to append View at the end of the file name)
- **ProfileGiftsView.java** updated for gift icons translations based on scroll
- **ProfilePatternDrawer.java** added for new pattern drawing in TopView

## Limitations & Future Improvements

Due to discovering the contest relatively late, I had only 7 days to work on this project. While I managed to implement the core functionality and UI flow according to the provided mockups, with just one additional week, I would have significantly improved both the structure and performance of the codebase. Some of the key areas I had planned to refine include:

1. **Refactoring `ProfileActivity` (Monster Class)**  
   This class currently contains a large volume of code and responsibilities, making it difficult to maintain and extend.  
   My plan was to refactor it using proper **object-oriented design principles** such as:
   - **Separation of Concerns**
   - **Single Responsibility Principle**
   - **Encapsulation**
   - Applying **Design Patterns** like **MVC/MVP** or **Command/Observer** to decouple business logic from UI rendering.  
   With this approach, I estimate the code size could be reduced by at least 30%, improving both clarity and testability.

2. **Smoother Animations**  
   Improving animation smoothness was entirely feasible by optimizing rendering logic and minimizing layout recalculations.  
   Unfortunately, the original code in these sections lacks structure (e.g., missing design patterns, tightly coupled logic), which made integrating optimized code more difficult within the limited timeframe.

3. **Reducing Redundancy**  
   The current implementation still has noticeable redundant logic and repetitive patterns. These could be eliminated by creating shared UI components and utility methods, resulting in a cleaner and more maintainable codebase.

4. **Optimizing the Settings Screen**  
   I didn’t have enough time to fully optimize the Settings screen. Some elements are not yet properly modularized or consistent with the new design flow.

---

### Final Note  
Despite the time constraint, I aimed to deliver a functional and accurate implementation aligned with the contest guidelines. I would be excited to continue refining the codebase and applying architectural improvements if given more time.

## Author

**Farid Fatehi**  
GitHub: [f0121](https://github.com/f0121)  
Telegram: [@bytegroup_co](https://t.me/bytegroup_co)
