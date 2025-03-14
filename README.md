# Dev Portfolio

A professional developer portfolio built with modern web technologies to showcase your skills and projects with beautiful animations and interactive 3D elements.

## Technologies Used

- **Next.js** - React framework for the user interface
- **Three.js** - 3D rendering library
- **Framer Motion** - Animation library
- **TailwindCSS** - Utility-first CSS framework
- **Aceternity UI** - Beautiful UI components
- **Next-themes** - Theme management for light/dark mode

## Getting Started
   
## Project Setup

###  Install required packages:
   ```bash
   npm i motion clsx tailwind-merge
   npm install tailwind-css animate
   npm i mini-svg-data-uri
   npm i react-icons
   npm i --save-dev @types/react-lottie
   npm i three three-globe @react-three/fiber@alpha @react-three/drei
   npm i next-themes
   ```

### Adding Aceternity UI Components

1. Create a `components/ui` folder in your project.
2. Create a `lib` folder and add a `util.ts` file (code available on the Aceternity website).
3. Copy the desired component code from the [Aceternity UI](https://ui.aceternity.com/) website and paste it inside the `components/ui` folder.
4. All the `ShadCN` components will also come in this `ui` folder.
5. Update your `tailwind.config.ts` file with the component-specific configuration code (available on the Aceternity website).

### Theme Management

1. Install next-themes:
   ```bash
   npm i next-themes
   ```

2. Create a `provider.tsx` file in your app to manage themes following the [Shadcn UI dark mode documentation](https://ui.shadcn.com/docs/dark-mode/next).

3. Wrap your app with the ThemeProvider in your root layout.

## Aceternity UI Components Used

This portfolio utilizes the following components from Aceternity UI:

- [Spotlight Effect](http://ui.aceternity.com/components/spotlight)
- [Grid Background](https://ui.aceternity.com/components/grid-and-dot-backgrounds)
- [Layout Grid](https://ui.aceternity.com/components/layout-grid)
- [Text Generate Effect](https://ui.aceternity.com/components/text-generate-effect)
- [Magic Button](https://ui.aceternity.com/components/tailwindcss-buttons)
- [Floating Navbar](https://ui.aceternity.com/components/floating-navbar)
- [Bento Grid](https://ui.aceternity.com/components/bento-grid)
- [Infinite Moving Cards](https://ui.aceternity.com/components/infinite-moving-cards)
- [Github Globe](https://ui.aceternity.com/components/github-globe)
- [Canvas Reveal Effect](https://ui.aceternity.com/components/canvas-reveal-effect)
- [Background Gradient](https://ui.aceternity.com/components/background-gradient)
- [Moving Border](https://ui.aceternity.com/components/moving-border)

### Globe Configuration

The Github Globe component requires a JSON file for configuration:
- [GLOBE.JSON FILE](https://assets.aceternity.com/globe.json)

## Additional Resources

- Create custom gradients using [CSS Gradient](https://cssgradient.io/)

## Learnings

- `left-full` is equivalent to `left:100%`
- Custom percentage values can be added with `left-[<value>%]` syntax in Tailwind
- Tailwind classes can be combined with custom CSS for more complex styling requirements
- How to use an amazing UI Library like `Aceternity`

## Acknowledgments

- [Aceternity UI](https://ui.aceternity.com/) for the beautiful UI components
- [Next.js](https://nextjs.org/) for the React framework
- [Three.js](https://threejs.org/) for 3D rendering
- [Tailwind CSS](https://tailwindcss.com/) for styling