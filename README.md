# dev-portfolio
The portfolio is built with with Next.js for handling the user interface, Three.js for rendering 3D elements, Framer motion for beautiful animations, and styled with TailwindCSS.

[Acerternity-UI](https://ui.aceternity.com/)
Run 
 `npm i motion clsx tailwind-merge`
`npm install tailwind-css animate`
`npm i mini-svg-data-uri`

[Spotlight-Effect](http://ui.aceternity.com/components/spotlight)
[Grid-Background](https://ui.aceternity.com/components/grid-and-dot-backgrounds)

Create a library folder and add a `util.ts` file (you will find this on the Acerternity website)
Copy the code for particular component u want to use from `Acerternity` and paste it inside a folder `ui` in the `components` folder.
You also have to add the particular component to the `tailwind.config.ts` file otherwise you won't see it
The `config code `will also be on the `Acerternity` website.

Simple things I learned making this Portfolio:
`left-full` means `left:100%`
That we can add percentages after `left-[<value>%]`