# Pixel-Perfect Copilot
Make pixel-perfectness great again! CSS classes for interactive outline of containers for pixel-perfect layouts ('a la' Pesticide copilot). Made with love in France 🇫🇷

## Usage


### Adding CSS link
Just add this link inside `<head>` tag:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/spanarin/pixel-perfect/copilot.css">
```
### Adding debug utility classes
Then add classes `db-1` – `db-5` to your containers classes like this and preview in a built-in browser in VSCode (example with Tailwind CSS utility classes:
```html
<!-- Live Demo -->
<div class="db-1">
    <div class="db-2 bg-gray-200 mx-10 rounded-2xl my-20 font-sans p-10">
        <div class="db-3 flex flex col gap-4 justify-center items-center rounded-xl p-2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ipsam hic nostrum deleniti animi,
            aut laborum maxime beatae, consequuntur voluptatibus quaerat enim unde aperiam temporibus
            deserunt tenetur quod est dolores.</div>
    </div>
</div>
```

### Live Demo

![Pixel Perfect Copilot Live Demo](https://github.com/spanarin/pixel-perfect/blob/0a7e7e89527b4d998f715a63f0914c52386dfe81/pixel-perfect-copilot-demo.png)
