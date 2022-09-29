# CLAID Website

Welcome to the CLAID Website! If you are reading this, you have probably been tasked with maintaining and updating the official UIUC CLAID website! Here are some things to know:

## Backend
This website was created using Jekyll powered by Ruby. You can find instructions for how to set up your machine here: https://jekyllrb.com/docs/. Make sure to install the prerequisites in Step 1. You can skip steps 3 and 4, since we already have the Jekyll site (it's the code you're looking at right now). The instructions don't say this, but if you want `bundle exec jekyll serve` to work (that's the command to run the site on your local server), use Ruby version 2.6.10. One day they might fix this to work with the latest version of Ruby, but for now, save yourself the trouble.

If you don't know how to use Ruby, don't worry, neither do I. I have not had to use Ruby in the ~3 years since creating this website; everything I've done has been using Markdown, HTML/CSS, and JS.

## Layout
The main folders that you will be looking at and editing in the layout are:

    - _services
    - _team

Occasionally, you may also be editing:

    - team.html

You really shouldn't need to touch any of the other files, as long as you are doing frontend work. If you find yourself wanting/needing to do backend work, you'll have to look at the other files (more on that later).

The main four pages of the website (which you can see by looking at the top of the site at claid.club) are Home, Join Us, Board, and Connect. Be sure to familiarize yourself with these pages on the website so you can have a good understanding of how the code connects to it.

Here's how the pages connect:

    - Home -> index.html
    - Join Us -> services.html
        - Under this page, you also have:
        - Chinese Corner -> _services/chinese-corner.md
        - Events -> _services/events.md
        - Peer Tutoring -> peer-tutoring.md
    - Board -> team.html
        - Each board member has their own .md file under _team
    - Connect -> contact.html

## How to Edit
Most of the work you will do is in the .md files, using Markdown. Markdown is a really intuitive markup language that uses plaintext editors. This README.md file is written in Markdown. Google has great resources for Markdown formatting.

The most common page you'll be editing is the Events page. This will be done in _services/events.md, as shown above. Reference the above layout to see how to edit other pages.

You may notice that the main four pages don't have .md files, but rather are written in html. To edit these pages, you will have to edit those html files, which means you'll be writing in html rather than md. Don't worry, Google also has lots of resources for html. You will probably never have to touch Home, Join Us, or Connect. To open/close board applications, edit the team.html file. You may also need to update the application form, which can be found in _team/board-applications.html. Same thing with the tutor and learner applications, which can be found under _services\tutor-application.html and _services\learner-application.html respectively.

**VERY IMPORTANT**

PLEASE familiarize yourself with basic Git commands before editing this code. The main things you'll need are:

    - git pull
    - git push
    - git add
    - git commit

If you don't mess up, these should be the only git commands you'll need. PLEASE PLEASE PLEASE do a git pull before editing or committing any code.

## Other Questions
If you have any other questions that can't be solved by Google and it's at or before 2024, contact me (Annie) on Discord (sugaronsnow#4950). Otherwise, uhhh look on Google harder I guess?

## TODO
-add chinese language toggle (in progress! woohooo) <br/>

