# dev-portfolio
The portfolio is built with with Next.js for handling the user interface, Three.js for rendering 3D elements, Framer motion for beautiful animations, and styled with TailwindCSS.

[Acerternity-UI](https://ui.aceternity.com/)
Run 
`npm i motion clsx tailwind-merge`
`npm install tailwind-css animate`
`npm i mini-svg-data-uri`
`npm i react-icons`
`install this npm i --save-dev @types/react-lottie`
`npm i three three-globe @react-three/fiber@alpha @react-three/drei`

[Spotlight-Effect](http://ui.aceternity.com/components/spotlight)
[Grid-Background](https://ui.aceternity.com/components/grid-and-dot-backgrounds)
[Layout-Grid](https://ui.aceternity.com/components/layout-grid)
[Text-Generate](https://ui.aceternity.com/components/text-generate-effect)
[Magic-Button](https://ui.aceternity.com/components/tailwindcss-buttons)
[Text-Generate-Effect](https://ui.aceternity.com/components/text-generate-effect)
[Floating-Navbar](https://ui.aceternity.com/components/floating-navbar)
[Bento-Grid](https://ui.aceternity.com/components/bento-grid)
[Infinit-Moving-Cards](https://ui.aceternity.com/components/infinite-moving-cards)
[Github-Globe](https://ui.aceternity.com/components/github-globe)
[Canvas-Reveal-Effect](https://ui.aceternity.com/components/canvas-reveal-effect)
[Background-Gradient](https://ui.aceternity.com/components/background-gradient)
[Moving-Border](https://ui.aceternity.com/components/moving-border)
[GLOBE.JSON-FILE](https://assets.aceternity.com/globe.json)

Create a library folder and add a `util.ts` file (you will find this on the Acerternity website)
Copy the code for particular component u want to use from `Acerternity` and paste it inside a folder `ui` in the `components` folder.
You also have to add the particular component to the `tailwind.config.ts` file otherwise you won't see it
The `config code `will also be on the `Acerternity` website.

To download the themes use : 
`npm i next-themes`
Create the `provider.tsx` file in your app to manage the `next-themes`
The code to copy paste in the file can be found here [dark-theme](https://ui.shadcn.com/docs/dark-mode/next)
And then you have to copy the root layout with the themeprovider

Simple things I learned making this Portfolio:
`left-full` means `left:100%`
That we can add percentages after `left-[<value>%]`
Make custom gradients using [CSS-Gradient](https://cssgradient.io/)