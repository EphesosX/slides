## GitHub,
## Reveal.js presentations,
## Jekyll websites

* Press 'o' for overview mode

* Use arrow keys to navigate presentation

* Organization is top to bottom, left to right




-vertical-

* **GitHub**: hosting, version control

* **Prose.io**: File editing

* **Reveal.js**: presentations

* **Jekyll**: websites

[jacob.moorman.me/slides/s18math290j/](https://jacob.moorman.me/slides/s18math290j/)




-vertical-

Open a web browser if you want to follow along

Chrome, Firefox, Internet Explorer, etc




-horizontal-

## Github

Create an account at [github.com/join](https://github.com/join)

<img src="./images/github_create_account.png" width="45%">




-vertical-

Verify your email address

<img src="./images/verify_email.png" width="100%">




-vertical-

Options for creating a new project:

* Create a new empty repository

* Import code from an existing repository

* Fork an existing repository




-vertical-

To create a new empty repository,

click the plus at the top right corner

and select "New repository"

<img src="./images/new_repository_button.png" width="50%">




-vertical-

* Give your repository a name
* Tick "Initialize this repository with a README"
* Click "Create repository"

<img src="./images/new_repository_dialogue.png" width="50%">




-vertical-

## Checkpoint

Create a new empty repository
called "test"




-vertical-

To import code from an existing repository,

click the plus at the top right corner

and select "Import repository"

<img src="./images/import_repository_button.png" width="60%">




-vertical-

* Paste a link to the existing repository
* Give your new repository a name
* Click "Begin import"

<img src="./images/import_repository_dialogue.png" width="45%">




-vertical-

To fork an existing repository,

go to the repository you wish to fork

and click the fork button near the top right

<img src="./images/fork_repository_button.png" width="80%">




-vertical-

<img src="./images/forking_revealjs.png" width="80%">




-vertical-

To rename a repository,

go to the settings tab

<img src="./images/repository_settings.png" width="100%">




-vertical-

Type the new name of your repository

and click "Rename". 

<img src="./images/change_name_of_repo.png" width="60%">




-vertical-

The page should reload and the name of your repository should change

<img src="./images/after_renaming.png" width="60%">




-vertical-

## Checkpoint

Change the name of "test" to something else

verify the name changed, then change it back to "test"




-vertical-

Forking is very similar to importing code from an existing repository, but only works on repositories within GitHub.




-vertical-

To host your GitHub project as a website,

go to the settings tab of your repository

<img src="./images/repository_settings.png" width="100%">




-vertical-

* Scroll down until you see "GitHub Pages"
* Select "master branch"
* Click "Save"

<img src="./images/enable_github_pages.png" width="50%">




-vertical-

Check that a confirmation message appears

<img src="./images/github_pages_published.png" width="100%">




-vertical-

Eventually the confirmation message turns green if you wait a while and refresh the page

(takes about 30 secs, tops)

<img src="./images/site_is_alive.png" width="100%">




-vertical-

## Checkpoint

Enable GitHub Pages on your test repository

visit the site at [username.github.io/test/]()

---

You will get a 404 error if you visit before the confirmation turns green



-vertical-

The home of a GitHub Pages site is

[username.github.io/repository-name/]()

Unless the repository name is "username.github.io"

which will be accessible at [username.github.io]()




-horizontal-

## Prose.io

A file editor GitHub repositories


-vertical-

Enable editing at [prose.io](https://prose.io)

<img src="./images/prose_landing.png" width="40%">




-vertical-

Authorize prose to access your repositories

<img src="./images/enable_prose.png" width="45%">




-vertical-

Open the "test" repository on prose

<img src="./images/prose_test_repo.png" width="100%">




-vertical-

Add a new file

<img src="./images/new_file_test_prose.png" width="100%">




-vertical-

Name the file "index.md"

<img src="./images/prose_index_md.png" width="100%">




-vertical-

Save the file

* Click the save icon on the right
* Click "commit"

<img src="./images/save_index_md.png" width="40%">




-vertical-

## Checkpoint

Verify that when you load [username.github.io/test]()

you see the contents of the file you just added




-vertical-

Today, everything will be written in Markdown

To view a summary of Markdown formatting, google "Markdown Cheatsheet" and click the first link

<img src="./images/markdown_cheatsheet_google.png" width="60%">







-horizontal-

## Reveal.js

Examples/Demonstrations

* [Reveal.js overview slides](https://revealjs.com/)

* [My 285J presentation](https://jacob.moorman.me/slides/s18math285j/)

* [This very presentation](https://jacob.moorman.me/slides/s18math290j/)




-vertical-

## Reveal.js

* beautiful html presentations

* slides exist in a 2d grid

* slides are ordered top-to-bottom, left-to-right




-vertical-

Fork [github.com/jdmoorman/slides]()

<img src="./images/fork_revealjs.png" width="100%">




-vertical-

<img src="./images/forking_revealjs.png" width="80%">




-vertical-

When finished, open the settings tab

<img src="./images/repository_settings.png" width="80%">




-vertical-

Scroll down until you see the "GitHub Pages" section

Change the GitHub Pages branch to "master branch"

<img src="./images/github_pages_branch_becomes_master.png" width="65%">




-vertical-

## Checkpoint

<img src="./images/slides_published_success.png" width="100%">

You should be able to load

[username.github.io/slides/template/]()




-vertical-

Remember

* Press 'o' for overview mode

* Use arrow keys to navigate presentation

* Organization is top to bottom, left to right




-vertical-

On prose.io, open the "slides" repository

<img src="./images/prose_projects_page_1.png" width="100%">




-vertical-

Open the "template" folder

<img src="./images/template_folder.png" width="100%">




-vertical-

To edit your presentation

edit the code in "content.md"

<img src="./images/editable_content.png" width="100%">




-vertical-

To add inline equations such as \\( c = \sqrt{a^2+b^2} \\), surround with `\\(  \\)`

```
\\( c = \sqrt{a^2+b^2} \\)
```

To add block equations such as \\[ c = \sqrt{a^2+b^2}, \\] surround with `\\[  \\]`

```
\\[ c = \sqrt{a^2+b^2} \\]
```




-vertical-

## Checkpoint

Try adding this equation to your presentation:
```
\\[ c = \sqrt{a^2+b^2} \\]
```
and verify that it renders correctly.

[username.github.io/slides/template/]()




-vertical-

To add a new slide in the current column, use

```markdown
-vertical-
```

To add a new slide and start a new column, use

```markdown
-horizontal-
```




-vertical-

Use Markdown to control the

appearance of your content




-horizontal-

## Jekyll

A website generator

Commonly used for blogs




-vertical-

For example: [jekyllrb.com]()

<img src="./images/jekyll_website.png" width="60%">




-vertical-

For example: [jacob.moorman.me](https://jacob.moorman.me)

<img src="./images/my_website_example.png" width="70%">




-vertical-

Was generated from

<img src="./images/about_page_source_code.png" width="100%">

barely any more code than just the text on the screen




-vertical-

For this tutorial, I've chosen the template "Hyde". However, most templates function similarly.

<img src="./images/hyde_demo_img.png" width="70%">




-vertical-

Most templates will not have equation rendering

built in, but I've added it to this one




-vertical-

Fork [github.com/jdmoorman/hyde](https://github.com/jdmoorman/hyde)

<img src="./images/fork_hyde.png" width="100%">




-vertical-

<img src="./images/forking_hyde.png" width="100%">




-vertical-

Open the settings tab, change the name

to [username.github.io](), and click rename

<img src="./images/change_repo_name.png" width="60%">




-vertical-

It's important that the name of the repository exactly matches [username.github.io]()




-vertical-

Scroll down until you see the "GitHub Pages" section

Change the GitHub Pages branch to "master branch"

<img src="./images/github_pages_branch_becomes_master.png" width="65%">




-vertical-

Open a tab of prose.io and
open the [username.github.io]() repository

<img src="./images/prose_with_hyde.png" width="65%">




-vertical-

open "\_config.yml"

<img src="./images/open_config.png" width="65%">




-vertical-

On line 13, change

```markdown
baseurl:         "/hyde"
```

to

```markdown
baseurl:         ""
```

and save the file




-vertical-

## Checkpoint

You should be able to load [username.github.io](https://mrmoorman.github.io/)

<img src="./images/first_look_at_hyde.png" width="65%">




-vertical-

Back in "\_config.yml", change

```markdown
title:            Hyde
description:      'A brazen two-column ...'
url:              https://jacob.moorman.me/hyde/
```

to

```markdown
title:            Your Name
description:      'A brief description of yourself'
url:              https://username.github.io/
```

and save the file




-vertical-

also change

```markdown
author:
  name:           'Jacob Moorman'
  url:            https://jacob.moorman.me/
```

to

```markdown
author:
  name:           'Your Name'
  url:            https://username.github.io
```

and save the file




-vertical-

If you don't need a blog, you can change

```markdown
has_blog:         True
```

to

```markdown
has_blog:         False
```

but for now, just leave it as True




-vertical-

## Checkpoint

Verify that the changes are reflected at

[username.github.io](https://mrmoorman.github.io/)




-horizontal-

## Adding pages
## to your website




-vertical-

Suppose you want to add pages for

each of the courses you teach.




-vertical-

in prose.io, go to the [username.github.io](https://mrmoorman.github.io/) repo

<img src="./images/prose_with_hyde.png" width="100%">




-vertical-

Add a new file

<img src="./images/prose_new_website_file.png" width="100%">




-vertical-

name the file "teaching.md"

<img src="./images/teaching_md.png" width="100%">



-vertical-

Replace the contents of "teaching.md" with

```markdown
---
layout: page
title: Teaching
---

The courses I'm teaching are:
* [Course 1](/teaching/course1/)
* [Course 2](/teaching/course2/)
```




-vertical-

Save "teaching.md", and return to prose.io at [username.github.io]()

<img src="./images/prose_new_website_file.png" width="100%">

Add another new file




-vertical-

Name the file "teaching/course1.md"

<img src="./images/prose_course_1.png" width="100%">

This will create a directory called "teaching" and a file in that directory called "course1.md"




-vertical-

Replace the contents of "course1.md" with

```markdown
---
layout: default
---
## Hello from course 1
```




-vertical-

Create another file called "teaching/course2.md"

replace its contents with 

```markdown
---
layout: default
---
## Hello from course 2
```




-vertical-

## Checkpoint

You should now be able to load

* [username.github.io/teaching/]()
* [username.github.io/teaching/course1/]()
* [username.github.io/teaching/course2/]()

And the links on the teaching page should work




-vertical-

To add a blog post, open prose.io to [username.github.io]()

navigate to the "\_posts" directory

<img src="./images/prose_posts_dir.png" width="100%">




-vertical-

Create a new file, give it whatever title you want

<img src="./images/prose_blog_post.png" width="100%">

commit the file




-vertical-

Open the settings of the file,

<img src="./images/prose_create_draft.png" width="100%">

Click "create draft"




-vertical-

Click "Draft to post" and commit

<img src="./images/prose_draft_to_post.png" width="100%">

If you get a red warning, reload the page, hope the warning goes away




-vertical-

Click "Unpublished" and commit

<img src="./images/prose_unpublished.png" width="100%">




-vertical-

## Checkpoint

Your new blog post should show up at

[username.github.io/blog/]()