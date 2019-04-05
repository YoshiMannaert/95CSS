# Forms

So far some basic form styling has been added.

To make sure spacing stays stays the same a `.input-field` class has been added as a wrapper for inputs and their labels.

Basic input fields, buttons, selects and textareas have received a basic styling.
A fieldset and legend styling is available as well and have been styled as what field groups in Windows95 look like.

## Example form
```html
<form action="" method="post" class="card">
    <div class="card-header">
        <h2 class="card-title">Forms</h2>
    </div>
    <div class="card-body">
        <div class="input-field">
            <label for="">Text input</label>
            <input type="text" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Number input</label>
            <input type="number" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Email input</label>
            <input type="email" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Password input</label>
            <input type="password" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Date input</label>
            <input type="date" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Datetime input</label>
            <input type="datetime" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Tel input</label>
            <input type="tel" name="" value="">
        </div>
        <div class="input-field">
            <label for="">Textarea</label>
            <textarea name="name" rows="8" cols="80"></textarea>
        </div>
        <div class="input-field">
            <label for="">Select</label>
            <select class="select" name="">
                <option value="">Small fonts</option>
                <option value="">Medium fonts</option>
                <option value="">Large fonts</option>
            </select>
        </div>

        <fieldset>
            <legend>Fieldset</legend>
            <div class="input-field">
                <label for="">Fieldset input</label>
                <input type="text" name="" value="">
            </div>
        </fieldset>


        <div class="input-field">
            <label for="">Disabled input</label>
            <input type="text" disabled>
        </div>

        <button type="reset" name="button" class="btn">Reset form</button>
        <input type="submit" name="" value="Submit form" class="btn">
    </div>
</form>
```
