# Redirect Page

A simple HTML page with JavaScript that redirects to YouTube after a specified delay. This can be used as a landing page or a placeholder for redirects.

## Usage

Simply open the `index.html` file in a web browser, and you will be redirected to YouTube after a few seconds.

## Customization

If you want to customize the redirection target or the delay, you can edit the `window.location.href` line in the `<script>` tag inside `index.html`.

```javascript
// Redirect to YouTube after a delay (in milliseconds)
setTimeout(function() {
  window.location.href = 'https://www.youtube.com';
}, 3000); // Redirect after 3 seconds (adjust as needed)
