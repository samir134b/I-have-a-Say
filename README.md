# I-have-a-Say
a. In this project, I have created a comment section. It lets users enter comments, provide replies to comments, delete a comment, like comment functionalities, and retains users' comments even after the site is closed.

b. I have used HTML, CSS, and Pure Vanilla JavaScript. I did not use Bootstrap, jQuery, or any other frameworks.

c. I had implemented some of the features including;-

The page is always launched with one static text area at the top and an add button that allows the user to add comments.
Every comment added will have a reply, a like, and a delete button.
A reply button will launch a new text area below the parent comment, allowing the user to either add a reply or cancel the addition.
A like button will keep incrementing the number of likes on the respective comment at every click.
A delete button will delete the entire comment chain or if the user wants to delete a single comment, he can.
Comments can be chained resembling a tree-like structure wherein every child comment will be aligned with some pixels left to the parent comment.
Comments once added should be persisted on page re-load — this is an enhancement, I have implemented it using localStorage.
