scout-app for compiling scss ("sass")

If you want to go back to regular css:
- commit code for pre-change commit
- move your css file to styles
- in the css file (from the new location) get rid of line references
  - select "/* line" and multiselect each line with "ctrl d" and "shift end"
  - delete
  - test for sanity (git diff in terminal to see that you only deleted what you intended)
- change the css link in your index.html file to styles/home.css instead of styles/css/home.css

dropdown code
https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp

what to download for development

- normal, non-node project
  - vscode
  - git
  - scout-app if you want scss

- node, react project
  - devcamp-js-builder ("google it" on npm's website) - just for new projects
  - node (will include npm which you also need)
  - vscode
  - git
  - scout-app if you want scss
  - heroku cli (insructions for installation on any existing project - deploy tab)

  jeremiahchris7@gmail.com
  - for further assistance