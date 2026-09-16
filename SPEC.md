Problem: The current page sharing panel in Notion is cluttered and not user-friendly, making it difficult for users to quickly share pages with others. Users often struggle to find the right options, settings and to verify that they were applied correctly. 
Solution: Share panel should clearly state its current sharing status, provide a simple and intuitive interface for sharing options, and allow users to easily manage permissions. The redesign should focus on improving usability, reducing cognitive load, and enhancing the overall user experience.

Project goal: create a redesign of the existing page sharing panel in Notion. It should show in intuitive and easy to grasp way who can view and edit the page. The ability to switch between different sharing options (e.g., public, private, team, specific people). Also it should have sharing link expiration settings
Deliverable: Just a single page with a mockup of the redesigned sharing panel, including clear labels, icons, and visual hierarchy to indicate the current sharing status and available options. The mockup should also include a section for managing permissions and setting link expiration.

Sharing states:
- Private
- Anyone with link
- Workspace


| State  | Access | Sentence shown |
| -------- | -------- | -------- |
| Private  | Owner has read/edit access   | Only the owner can read/edit. |
| Anyone with link | Everyone on the internet with the link can read/edit   |  Everyone on the internet with the link can read/edit. |
| Workspace | List of team members with their individual read/edit toggle | The following team members have access. |


Link expiration states: Never/1 months/1 week/24 hours
Copy link button: copies to clipboard and displays a toast message "The link was copied to clipboard."

If the status is set to "Private" the copy link button is disabled and greyed out


Acceptance checks

- Current state displays currently selected access 
- On changing access state, current state updates
- On changing link expiration state, update link duration
- Copy link button saves share link into clipboard
- Changing individual members' access level
