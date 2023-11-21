# Grade
HTML Code Quality: 4/5
CSS Code Quality: 4.5/5
Responsive Design: 4.5/5
Assignment Requirements: 5/5
Subtotal: 18/20

Penalty: -30% (-6pts) - Please see email I sent you.

Total: 12/20

## Comments

### HTML
Search for `prof comment` in individual files for specific comments.

- You are using more tags than necessary. You often nest multiple levels of `section`/`div` when you do not need to.
  - Use `<section>` to group related content, there shouldn't be sections within sections
  - Only add `<div>` when the layout you want to create is not possible with the existing tags.
  - Our goal is to reduce the amount of unnecessary tags and only include tags that are necessary to describe our content, plus a few extra when the layout requires it.

### CSS
Search for `prof comment` in individual files for specific comments.

- You should set the default font in the CSS Reset. You still have Roboto there.
- Default responsive Typography styles are missing

### Responsive Design
- There is some inconsistency in the width and alignment of different section content. Ideally all sections should have the same width of container, and the same padding on the left and right, applied through the `.container`, to ensure everything lines up perfectly.

### Assignment Requirements
All requirements met!