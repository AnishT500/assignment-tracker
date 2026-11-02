# Assignment Tracker

## Project Goal
A web application that helps students track assignments, recurring weekly deadlines, and completion status in one centralized dashboard.

## MVP Scope
- Add assignments with a name, due date, and weekly repeat option
- Delete assignments from the list
- Mark assignments as complete and view upcoming deadlines (sorted soonest first)
- Set recurring weekly deadlines (automatically generating next week's incomplete occurrence when marked complete)
- Save and load assignment data persistently in the browser using localStorage

## Future Plans (Schedule - V2.0+)
- Automated text reminders
- Automated phone calls
- Advanced study planning for exams and projects

## Tech Stack
- **Languages:** JavaScript, HTML, CSS
- **Framework:** Next.js
- **Libraries:** date-fns for handling dates and recurring assignments
- **Data Storage:** Browser localStorage to save assignment information
- **Development Tools:** VS Code, Git, GitHub
- **Hosting:** Vercel
- **External APIs:** None needed for the MVP, potentially Twilio for future text/phone reminders

## Build Plan
1. Set up the GitHub repository and Next.js project.
2. Create the basic website layout.
3. Add a form for entering assignments and due dates.
4. Display assignments sorted by their due dates.
5. Add the ability to mark assignments complete or delete them.
6. Implement recurring weekly assignments.
7. Save assignment information using `localStorage`.
8. Test the website, fix bugs, and improve the design.

## Design Documents
- [Eisenhower Matrix](./eisenhower-matrix.pdf)
- [System Diagram](./assignment-tracker-system.png)
