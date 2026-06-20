# CSS Grid Intro

This repository contains the starter files for the CSS Grid Intro coding exercise in Web Design 1.

This exercise is your first introduction to CSS Grid. CSS Grid is a layout system that lets you arrange content into rows and columns. It is especially useful when you want to divide a page into larger layout areas, such as columns, sidebars, headers, footers, galleries, and other structured page sections.

In this exercise, the examples are intentionally simple. The goal is to understand the basic Grid concepts you will need before moving into more complete website layouts.

---

## Use Canvas for the Full Assignment Instructions

Canvas has the full assignment description, screencast videos, due date, and submission instructions.

This README is here to explain the project, remind you of the major concepts, and help you check your work before submitting.

Follow the Canvas instructions and watch the screencast videos in order.

---

## Important GitHub Workflow

This assignment uses a GitHub template repository. You are not downloading a ZIP file for this exercise.

Instead, you will:

1. Create your own repository from the instructor’s template repository.
2. Clone your copy to your computer using GitHub Desktop.
3. Open the project folder in Visual Studio Code.
4. Complete the CSS Grid Intro exercise.
5. Commit your changes in GitHub Desktop.
6. Push your changes to GitHub.
7. Publish the site using GitHub Pages.
8. Add the published GitHub Pages link to the About section of your repository.
9. Submit the URL of your GitHub repository in Canvas.

The submitted Canvas link should be the **repository** URL, not the published GitHub Pages website URL.


---

## Why This Exercise Is Important

CSS Grid is one of the main layout tools used in modern web design.

Earlier in the course, you learned how to create HTML structure, write basic CSS styles, and did a little Flexbox. Flex is useful when you want to arrange content in one direction, such as a single row or a single column.

Grid is especially useful when you want to think in both rows AND columns at the same time.

For example, Grid can help create:

- two-column page layouts
- sidebars
- card grids
- image galleries
- page sections
- complex website layouts

In this exercise, we will keep the examples simple so you can focus on the core ideas.

---

## The Big Idea: Grid Container and Grid Items

CSS Grid starts with a parent-child relationship.

The parent element becomes the grid container when you apply:

- `display: grid;`

The direct children of that parent become grid items.

That means Grid is usually controlled from the parent container.

For example, if a `<div>` contains three sections, you usually turn the `<div>` into the grid container. The three sections inside it become the grid items.

This is one of the most important concepts in CSS Grid.

---

## On Your Own Challenge

At the end of the exercise, you will complete a Grid challenge on your own.

The challenge asks you to create a simple page-layout-style grid with:

- a main content area
- a sidebar
- a full-width box below them

Your goals are:

1. Turn the challenge area into a grid.
2. Create three equal columns.
3. Add a gap between the grid items.
4. Make the main content area span two columns.
5. Make the full-width box span across all three columns.

This challenge uses the same ideas from the demos, but combines them in a new way.

That is important. In coding, you do not really understand a concept until you can use it in a slightly different situation.

---

## Why We Are Using `span`

In this first Grid exercise, we are using the `span` method to make items stretch across columns.

Examples:

- `grid-column: span 2;`
- `grid-column: span 3;`

This is easier to understand at the beginning because it reads almost like a sentence:

- “This item should span 2 columns.”
- “This item should span 3 columns.”

CSS Grid also allows you to place items using grid line numbers, such as:

- `grid-column: 1 / 4;`

That method is powerful, but it requires understanding grid lines. For this first introduction, we are keeping the focus on columns, gaps, fractional units, and the span method.

---

## A Note About Rows

This exercise focuses mostly on columns.

Grid can also control rows, and grid items can span rows too. However, for this first Grid introduction, we are focusing on column-based layouts because that is what you will need most immediately in the next website layout exercise.

You will see more advanced Grid techniques later.

---

## GitHub Pages

For this exercise, you will publish the repository using GitHub Pages.

GitHub Pages turns your repository into a live website that can be viewed in a browser.

This is different from the repository itself.

The repository stores your code.

GitHub Pages displays the website created from that code.

After you publish the site, add the GitHub Pages link to the About section of your repository. That makes it easy to find the live version of your project when viewing the repo.

Remember: submit the repository URL in Canvas, not just the published site URL.

---

## Repository URL vs. Published Website URL

For this exercise, you will end up with two different URLs.

### Repository URL

The repository URL shows your code on GitHub.

It will look something like this:

- `https://github.com/your-username/css-grid-intro`

This is the URL you submit in Canvas.

### GitHub Pages URL

The GitHub Pages URL shows the live published website.

It will look something like this:

- `https://your-username.github.io/css-grid-intro/`

This is the URL you should add to the About section of your GitHub repository.

Do not submit only the GitHub Pages URL in Canvas. The published site is useful, but the repository is what your instructor needs to grade your code.


---

## GitHub Workflow Reminder

This assignment uses GitHub instead of a ZIP submission.

That means your work must be committed and pushed before your instructor can see it.

The basic workflow is:

1. Make changes in VS Code.
2. Save your files.
3. Open GitHub Desktop.
4. Review the changed files.
5. Write a short commit message.
6. Commit the changes.
7. Push the changes to GitHub.

Saving updates the files on your computer.

Committing records a checkpoint in Git.

Pushing uploads that checkpoint to GitHub.com.

If you forget to push, the repository on GitHub may not show your latest work.

---

## Before You Submit

Before submitting your work in Canvas, check the following:

- You created your own repository from the instructor template
- You cloned your repository to your computer
- You opened the full project folder in VS Code
- You worked in `index.html` and `styles.css`
- Demo 1 uses three equal columns
- Demo 2 uses unequal columns
- Demo 3 uses a grid gap
- Demo 4 has an item spanning all three columns
- Demo 5 previews a main content and sidebar layout
- The On Your Own Challenge is complete
- The challenge grid has three equal columns
- The challenge grid has a gap
- The challenge main content spans two columns
- The challenge full-width box spans all three columns
- The page looks correct when opened in a browser
- You committed your changes in GitHub Desktop
- You pushed your changes to GitHub
- You published the site with GitHub Pages
- You added the GitHub Pages link to the About section of your repository
- You are submitting the GitHub repository URL in Canvas

---

## What to Submit

Submit the URL of your GitHub repository in Canvas.

Do not submit a ZIP file.

Do not submit only the GitHub Pages URL.

Your Canvas submission should look something like:

- `https://github.com/your-username/css-grid-intro`

The GitHub Pages URL should be added to the About section of the repository, but the repository URL is what should be submitted in Canvas.

---

## Troubleshooting Tips

If something is not working, check these common issues first.

### My CSS is not changing the page

Check:

- Did you save the CSS file?
- Is the CSS file linked correctly in the HTML?
- Is the file name spelled correctly?
- Did you forget a semicolon?
- Did you forget a closing curly brace?
- Is your selector spelled correctly?

### My grid is not turning into columns

Check:

- Did you add `display: grid;` to the parent container?
- Did you use `grid-template-columns`?
- Are you styling the grid container, not the grid items?
- Did you save and refresh the browser?

Remember: the grid container controls the layout of its direct children.

### My gap is not showing

Check:

- Did you add `gap` to the grid container?
- Did you turn on Grid with `display: grid;`?
- Did you save the file and refresh the browser?

### My wide box is not spanning columns

Check:

- Did you add `grid-column: span 3;` to the item that should span?
- Is that item a direct child of the grid container?
- Did you spell the class name correctly in both HTML and CSS?

### My challenge main content is not spanning two columns

Check:

- Did you target the correct class?
- Did you use `grid-column: span 2;`?
- Is the main content box inside the challenge grid container?

### My GitHub repository does not show my latest work

Check GitHub Desktop.

You may have saved your files locally but forgotten to commit or push.

Remember:

- Save updates files on your computer.
- Commit creates a checkpoint.
- Push uploads the checkpoint to GitHub.com.

### My GitHub Pages site does not update immediately

GitHub Pages may take a little time to rebuild after you push changes.

Wait a minute or two, then refresh the published site.

Also make sure your repository includes an `index.html` file at the correct location.

---

## Final Reminder

CSS Grid can feel strange at first because you are not just styling individual boxes. You are often styling the parent container and telling it how to arrange the boxes inside it.

The key pattern is:

1. Find the parent container.
2. Turn on Grid with `display: grid;`.
3. Define the columns.
4. Add a gap if needed.
5. Make individual items span columns when needed.

Once that pattern starts to make sense, you will be ready to use Grid in more realistic page layouts.
