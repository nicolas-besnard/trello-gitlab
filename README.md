# trello-gitlab

## Working with Trello and Gitlab to make your client happy

The main goal of this project is to let Trello and Gitlab communicate to create a seamless communication between your clients, your project owner, and your developpers.

The first step is to create a Trello board. You’ll need many list to describe each step of a story:
- Backlog: The place where you client put new idea.
- Specified: Once a card is specified by the client and the project owner accept it, the project owner move this card on this list. This will create an issue on Gitlab linked to this card.
- Pending:  When the card is in the specified column, the project owner will add a developer to this task. This developer will be assigned to the previous created issue.
- Code Review: The developer has finished the task, has created a Merge Request, and has assigned an other developer to this merge request.
- Ready to Deploy: Merge Request has been accepted.
- Intern Validation:  The card has been deployed and the project owner need to review this on staging.
- Intern Feedback: The card has some problem.
