## Tailwind CSS

#### Nomal CSS framework
**Example:**  Boostrap, Bulma
- Provide CSS classes whose names describe how they are to be used
- Example: "button", "card", "nav"
	- These classes tend to define a number of CSS styles together

#### Tailwind CSS
- Basic Tailwind calsses are thin wrappers around a single CSS style setting

```javascript
// Normal CSS (Bulma)
<button class="button is primary">Click Me</button>
```

```javascript
// Tailwind CSS
<button class="bg-green-500 text-white font-bold py-3 px-4 rounded-lg text-center">
Click Me
</button>
```

- Made it possible to understand the display simply by looking at the HTML markup
- You don’t need to continually come up with names for CSS property combinations that might not be reused.

#### Reusing Tailwind CSS
- Tailwind provides an `@apply` directive that you can use to build new CSS classes out of Tailwind’s utilities,

#### Changing behavior in Tailwind CSS
```javascript
hover: bg-blue-500
```

- Specify different behaviors at different screen size