# Shadoww
## The modern way to create shadows.

<p>Shadoww is a library that allows you to add box shadows to any element without styling.</p>
<hr>

### Forgot about styling, that's for nerds.

<hr>

# Installation
<code>npm i shadoww --save</code>
<hr>

## Usage
<i>Ready to get started? Let's go!</i>

<hr>

<p>First add the following line:</p>
<code>import { shadoww } from 'shadoww';</code>
<hr>

<p>Your ready! To use the library, go into your html code, and add a classname of <code>shadoww</code> to the images you want to add the shadow to.
<hr>
Example: <code>&lt;img src="test.png" class="shadoww"></code>
<hr>

Now to use the library, add the following to your js:

<code>
shadoww({
  shadow_type: 'soft',
  padding: true
})
</code>
<hr>
Change <code>soft</code> to <code>hard</code> to get hard shadows, and change <code>padding: true</code> to <code>false</code> to disable padding.
<hr>
Hope you enjoy the extension!!!