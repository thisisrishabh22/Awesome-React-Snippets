# Contribution Guidelines

**Awesome React Snippets** is powered by the community, so feel free to contribute in any way you can to help us!

## How you can help

- Participate in community Discussions.
- Submit Pull Requests with new awesome snippets.
- Submit Issues or Pull Requests related to bugs, improvements, typos etc.
- Suggest new Ideas

## Ground rules

Breaking any of these rules will result in your pull request being closed. Please follow these guidelines above all else:

- **Use existing templates for snippets and collections**, ensuring to follow guidelines and that files are in the correct location.
- **Follow snippet format exactly**, otherwise your content will not be recognized correctly by the tools responsible for publishing them on the website. Consult the templates or previous snippets if you are unsure.
- **Snippets should solve real-world problems**, no matter how simple and should be abstract enough to be applied to different scenarios.

## Snippet creation

In order to create a new snippet, you should follow the steps below:

- Fork the **Awesome React Snippets** repository
- Create a new branch in the name of your snippet such as `sweet_alert_with_react`.
- Create a copy of the snippet template in the relevant subdirectory of the `snippets` directory and move it under the `snippets/doc` directory.
- Change the name of the newly created file to the name of your snippet.
- File name should be exactly matching with branch name.
- Edit the file, adding your snippet based on the guidelines.
- Open a PR mark approriate moderators as reviewers.
- If merged or closed delete the branch right after that. 

## Snippet guidelines

- Snippets must have all their frontmatter sections (title, tags, cover etc.) filled.
- Snippet filenames must be in `kebab-case` and end in `.md`. Use SEO-friendly names and avoid unnecessary words.
- Snippet titles must loosely correspond to the filename and follow the language and repository's naming conventions.
- Snippet tags must be comma-separated, contain a primary tag as seen on the website as their first tag.
- Snippets must include a cover image from the `assets/cover` directory, without the file extension.
- Snippets must have their `dateModified` dates formatted using [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601).
- Snippet descriptions must be short and to the point. Explain *what* the snippet does and detail *how* the snippet works and the language features used in it.
- Snippet code and examples must be enclosed in appropriate, language-tagged blocks as shown in the snippet template, be short and use modern techniques and features. Also make sure to test your code before submitting.
- Try to strike a balance between readability, brevity, and performance.
- Always use soft tabs (2 spaces), never hard tabs.
- Leave a single space after a comma (`,`) character (both in the description and code).
- Define multiple variables on the same line, if possible. Use meaningful variable names (e.g. `letter` instead of `lt`) and follow existing conventions as seen in other snippets. Do not use trailing or leading underscores in variable names.
- Whenever appropriate, an excerpt should be used to provide a short summary of the snippet. Excerpts should be up to 140 characters long and end in a period (`.`).
