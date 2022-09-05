# What is this?
- a quick template for app development going forward

# Dependencies
├── @astrojs/mdx@0.11.1
├── @astrojs/partytown@1.0.0
├── @astrojs/prefetch@0.0.7
├── @astrojs/react@1.1.1
├── @astrojs/tailwind@1.0.0
├── astro@1.1.5
├── react-dom@18.2.0
└── react@18.2.0




# Deployments to Azure
- https://docs.astro.build/en/guides/deploy/microsoft-azure/



# FAQ

### Why not use windi.css instead?
- No good answer at the moment.  Seeking max compatibility and may later switch for better performance if the tailwind JIT project doesn't suffice.

### Why React?
- The size of the existing components already out there, plus extensibility.

### Why Astro?
- I hate mono apps, and I really hate mono SPA apps.  I like the idea of creating React apps and being able to have them contained on different pages within the MPA provided by Astro.