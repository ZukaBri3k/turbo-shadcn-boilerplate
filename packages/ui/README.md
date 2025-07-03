# Shadcn-UI package - @repo/ui

This package is a collection of components built with [Shadcn-UI](https://ui.shadcn.com/).

## Installation

```bash
pnpm add @repo/ui
```

## Configuration

In the global.css file, import the globals.css file from this package:

```css
@import "@repo/ui/globals.css";
```

and add a postcss.config.mjs file in the root of the project:

```js
export { default } from "@repo/tailwindcss/postcss.config.mjs";
```

## Usage

```tsx
import { Button } from "@repo/ui/components/ui/button";

export default function Home() {
  return (
    <div>
      <h1 className="text-3xl text-red-500">Test</h1>
      <Button>Test</Button>
    </div>
  );
}
```

## Add new components

To add new components, you can use the shadcn cli inside the **ui** package:

```bash
pnpm dlx shadcn@latest add <component-name>
```

