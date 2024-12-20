# Labels in Forms

### Labels are critical for blind users, user with low vision, users with mobility disabilities and users with memory loss. Missing labels will make a form inaccessible for many users.

### `<Label>` Tag:
- Label tag defines a label for several elements like `<input> <select> <textarea>`.

- The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

- The `<label>` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button or checkbox.

- The for attribute of label tag should be eqal to the id attribute of the input tag to bind them together.

### Required fields:
- Form labels often contain a "*" or the word "required" to indicate that the field is required.

- It is recommended to add the required and aria-required="true" to the form control if you use an asterisk (*).

### Aria-label
- Fields without visual labels still needs a label. If you can not use a `<label>`, one option is to use a aria-label. 

### `<fieldset>` and `<legend>`
- Groups of form controls, like checkboxes and radio buttons often require a higher level of "label" in addition to the `<label>`. This high level "label" is made with `<fieldset>` and `<legend>`.

``` html
<fieldset>
  <legend>Your date of birth</legend>
  <label for="Day">Day</label>
  <select id="Day">…</select>
  <label for="Month">Month</label>
  <select id="Month">…</select>
  <label for="Year">Year</label>
  <input id="Year" type="text" placeholder="YYYY">
</fieldset>
