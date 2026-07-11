# PE01 - Hello World

A React Native "Hello World" mobile app built with Expo and TypeScript. It displays the
developer's name, degree program, and school on a yellow background, using exactly five
React Native building blocks: one `View`, three `Text` components, and `StyleSheet`.

## Screenshot

![Hello World app running in Expo web preview, yellow background with name, degree, and school centered on screen](docs/screenshot-web.png)

## Input

This app has no runtime user input. The "input" is static data supplied by the developer
directly in `App.tsx`: the strings `"Mohammad Al Bataineh"`, `"Master of Science in Computer
Science"`, and `"City University of Seattle"`, along with the yellow background color defined
in the `StyleSheet`.

## Process

Expo's Metro bundler transpiles the TypeScript/JSX in `App.tsx` and boots the Expo runtime.
React Native builds a component tree: a single `View` acts as the container, styled by
`StyleSheet.create` to fill the screen with a yellow background and center its contents. The
three `Text` components are laid out inside the `View`, each styled with the shared text style
for font size, color, and spacing.

## Output

The rendered screen shows the three lines of text — name, degree program, and school — centered
on a yellow background, matching the assignment's mockup.

## Run locally

```bash
npm install
npm run start   # or: npm run web / npm run android / npm run ios
```

Scan the QR code with the Expo Go app on your phone, or press `w` to open the web preview.

## Quality tooling

```bash
npm run lint         # ESLint (eslint-config-expo)
npm run typecheck     # TypeScript compiler, strict mode
npm run format:check  # Prettier
```
