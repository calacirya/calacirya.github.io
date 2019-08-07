# On Posting

Hello you! :wave:

So, you want to post to the [Calacirya]? That's great! Before you begin, however, please take the time to read our [Code of Conduct] and our [Contribution Guidelines].

You must be familiar with our philosophy because it applies not only to [issues], [pull requests] or comments - it applies to posts as well!

Now that you are familiar with our way of work, let's talk posts!

## Template

This project uses [Cayman] as its theme. However, we made some modification to the vanilla layouts used by it to improve our experience.

For the post to look it's better, please use the template file (`template.md`) at the `_drafts/` folder. You may even save your unfinished work under that folder until you feel ready to publish.

#### Front Matter

The template file holds all the front matter fields you must fill and in what style. Let's, however, review all fields here:

| Field        | Description                                     | Type     | Example                      |
|:------------:|:------------------------------------------------|:--------:|:-----------------------------|
| `layout`     | The `post` layout. **Don't change** this value. | `string` | `layout: post`               |
| `title`      | The title of the post.                          | `string` | `title: Hello World!`        |
| `author`     | Your name, nick or pen name.                    | `string` | `author: Foo Bar`            |
| `date`       | The date of submitting, see [this] [ISO].       | `date`   | `date: 1867-11-07`           |
| `categories` | Under which categories the post is published.   | `array`  | `categories: [foo, bar]`     |
| `tags`       | Under which tags the post is published.         | `array`  | `tags: [foo, bar, moo]`      |
| `contents`   | The post itself, in markdown.                   | `string` | `Lorem *Ipsum* dolor sit...` |

#### Contents

The contents of the post are the *de facto* post. Just remember that you have set the title on the front matter, you don't need to add it also to the contents - nor any information that was given on the front matter, for that matter. The layout will take care of displaying that information!

Also, remember to **proofread your texts**! There are resources off- and online to help with that, as well as professional and amateur help you may seek.

## Posting

Finished your post? Good job! :tada:

Before you move your draft file to the `_posts/` folder you must rename it to the default [jekyll post format]!

Your post file must follow the format: `YEAR-MONTH-DAY-title.md`. The year must be 4-digit (`1990` not `90`), and both month and day must be 2-digit (`03` not `3`). The title must not contain any non-alphanumeric character (bye bye `!`s, `?`s and the like), and all spaces must be replaced by hyphens (`-`). Also, the title can be any *reasonable* length you choose, shortening it for better file readability is encouraged and will not interfere with the displaying of the correct title inside the layout.

#### Examples

Let's say, like in the table above, your post is called `Hello World!`, and that you are posting it `November 7, 1867`. Your final file will be named `1867-11-07-hello-world.md`!

But then you take a couple years working nonstop on a post called `On the ephemeral nature of pearlescent homunculi and their quintessential relationships with the layers of the seven heavens` (just a sec, let me take a breath :laughing:). With this title, you took a very long time to write it, and will post it on `March 29, 2007`. We discourage you to name your post `2007-03-29-on-the-ephemeral-nature-of-pearlescent-homunculi-and-their-quintessential-relationships-with-the-layers-of-the-seven-heavens.md`. A better option would be `2007-03-29-ephemeral-nature-pearlescent-homunculi.md` or even the excelent `2007-03-29-pearlescent-homunculi.md`.

Remember, someone else may have a hard time reading a two-paragraph-long filename.

## Checklist

That's it! Now you are capable of posting on [Calacirya]! Here is a checklist with all steps to follow:

1.  [ ] Read the [Code of Conduct]
2.  [ ] Read the [Contribution Guidelines]
3.  [ ] Ask the [Content team] for help and approaval
4.  [ ] Read this tutorial
5.  [ ] Copy the `template.md` file under `_drafts/`
6.  [ ] Understand the front matter of the file...
7.  [ ] ...and fill with your post's info
8.  [ ] Write the post
9.  [ ] Proofread your text
10. [ ] Change the file name
11. [ ] Move the new file into the `_posts/` folder

### :tada: You've done it! :confetti_ball:

[Calacirya]: https://github.com/calacirya/calacirya.github.io
[Code of Conduct]: ../CODE-OF-CONDUCT.md
[Contribution Guidelines]: ../CONTRIBUTING.md
[issues]: https://github.com/calacirya/calacirya.github.io/issues
[pull requests]: https://github.com/calacirya/calacirya.github.io/pulls
[Cayman]: https://pages-themes.github.io/cayman/
[this]: http://xkcd.com/1179/
[ISO]: https://www.iso.org/iso-8601-date-and-time-format.html
[jekyll post format]: https://jekyllrb.com/docs/posts/#creating-posts
[Content team]: https://github.com/orgs/calacirya/teams/content
