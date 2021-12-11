# eScience Conference Series Website Template

This is a template for the eScience conferece websites. To start using this template, please **fork** this repository into a new repository at the [escience-conference](https://github.com/escience-conference) GitHub organization in which the repository name should be the year of the conference (e.g., `2022`).

## Customizing the website

Once forked, there are a few steps that need to be followed to properly configure the website.

### Configuration file

In `config.yml`, edit the line `baseurl: /_template` with the conference year (e.g., `baseurl: /2022`)

### Conference information

In `_data/main.yml`, edit the `edition`, `dates`, `location`, and `description` keys with the current's year conference information.

### Contents visibility

In `_data/main.yml`, the `contents` key controls which pages/links will be **visible** in the website menu. If you want to hide (resp. display) a menu option, use `false` (resp. `true`) as value for the sub-keys.

### Important dates

Edit `_data/important_dates.yml` with the list of important events (e.g., deadlines, notifications, etc.) related to the conference:

- `type` and `date` are required keys
- If the `extended` key is used, it will strikethrough the original date text and display the date extended date instead
- Important dates will be displayed in the order entered in the file
