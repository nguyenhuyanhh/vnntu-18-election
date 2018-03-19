# vnntu-18-election

Templates, HTML and CSS used to render our [voting page](vnntu.com/vote).

## Setup instructions

1. Make sure the Polls plugin is installed.

2. In `Dashboard > Polls > Poll Templates`, replace the current templates with those included in this repo (`template_*.html`).

3. Create Polls, one for each position. Note down the `answer_id` for each option.

4. Edit the [voting page](vnntu.com/vote), including the new Polls (similar to `vote.html`)

5. Under `Page Specific Stylesheet`, replace the current custom CSS with the content of `vote.css`. Edit the final section with the respective image link for each candidate, abiding the format

```css
#poll-icon-[answer_id] {
    background-image: url('http://i.imgur.com/mufrgkF.png');
}
```