---
layout: layout.html
---

# Contact Me

Fill out this form to contact with me!

<form method="POST" action="https://formsubmit.co/7b3e890575db30c7d63fc4abe98f26e9">
    <input type="hidden" name="_subject" value="New contact submission from the Blog!">
    <input type="hidden" name="_next" value="https://justablog.netlify.app/thankyou/">
    <p>
        <label>
            Name:
            <input type="text" name="name" >
        </label>
    </p>
    <p>
        <label for="email">
            Email:
        </label>
        <input type="email" name="email"/>
    </p>
    <p>
        <label for="content">Content:</label>
        <textarea name="content" id="content"></textarea>
    </p>
    <input type="submit" value="Send Form">
</form>