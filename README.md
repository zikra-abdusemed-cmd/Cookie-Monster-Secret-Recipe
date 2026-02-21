Cookie Monster Secret Recipe Walkthrough

Author: Brhane Giday and Prince Niyonshuti N.

This walkthrough explains how to uncover Cookie Monster's hidden secret recipe in the challenge.

1. Launch the Challenge

   ![Cookie Monster inspecting cookies](images/challeng.png)

Open the website where the challenge is hosted.

Familiarize yourself with the page: look for visible elements such as text, links, images, buttons, or any interactive components.

Try logging in with any credentials to trigger the cookie logs. This will help you inspect the cookies later.

2. Inspect the Webpage

Modern browsers provide built-in developer tools to inspect webpages:

Chrome / Edge / Firefox / Safari: Right-click → Inspect

Keyboard shortcuts:

Windows: F12 or Ctrl + Shift + I

Mac: Cmd + Option + I

This opens the Elements panel, showing the HTML structure of the page.

3. Check Cookies

Since this challenge references "Cookie Monster," cookies are a key part of the solution:

Open the cookies panel:

Chrome/Edge: Application → Storage → Cookies

Firefox: Storage → Cookies

Look for cookies that contain:

Secret codes

Encoded text (Base64, hex, or other formats)

Tip: Many challenges hide messages in cookies, for example: cGFzc3dvcmQ= is Base64 for password.

4. Retrieve the Secret from the Cookie

After logging in, check the cookie logs that were triggered.

Click on the relevant cookie and scroll to the value field.

Copy the value.

If it’s URL-encoded, decode it first (many online tools or decodeURIComponent() in the browser console work).

Paste the decoded string into a Base64 decoder like https://www.base64decode.org/
.

The decoded value is your flag / secret recipe.

Example:

Found cookie value (URL-encoded Base64):

cGljb0NURntjMDBrMWVfbTBuc3Rlcl9sMHZlc19jMDBraWVzX0M0MzBBRTIwfQ%3D%3D

After URL decoding and Base64 decoding:

picoCTF{c00k1e_m0nster_l0ves_c00kies_C430AE20}

This is the hidden secret recipe.
