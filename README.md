# Starlight Starter Kit: Basics

```
npm create astro@latest -- --template starlight
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/starlight/tree/main/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/starlight/tree/main/examples/basics)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro + Starlight project, you'll see the following folders and files:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   │   └── config.ts
│   └── env.d.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Check out [Starlight’s docs](https://starlight.astro.build/), read [the Astro documentation](https://docs.astro.build), or jump into the [Astro Discord server](https://astro.build/chat).


<starlight-tabs class="astro-JDRV5PDC">
  <div class="tablist-wrapper astro-JDRV5PDC">
        <ul role="tablist" class="astro-JDRV5PDC">
          <li role="presentation" class="tab astro-JDRV5PDC">
              <a role="tab" href="#tab-panel-45" id="tab-45" tabindex="-1" class="astro-JDRV5PDC">
                Stars
              </a>
            </li><li role="presentation" class="tab astro-JDRV5PDC">
              <a role="tab" href="#tab-panel-46" id="tab-46" class="astro-JDRV5PDC" aria-selected="true">
                Moons
              </a>
            </li>
        </ul>
      </div>
  <section id="tab-panel-45" aria-labelledby="tab-45" role="tabpanel" tabindex="-1" hidden="">
  Sirius, Vega, Betelgeuse
</section><section id="tab-panel-46" aria-labelledby="tab-46" role="tabpanel" tabindex="-1">
  Io, Europa, Ganymede
</section>
</starlight-tabs>