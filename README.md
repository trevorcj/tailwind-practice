# Roadmap (Easy → Pro)

```
3 phases: components → layouts → full apps.
```

### Beginner (components)

```
→ Buttons (different states, hover/focus)
→ Cards (profile card, product card)
→ Navbars (basic, responsive)
→ Forms (inputs, checkboxes, login page)
```

### Intermediate (layouts)

```
→ Landing page hero section
→ Blog post layout
→ Dashboard sidebar + content
→ Pricing tables
→ Responsive grid gallery
```

Advanced (full projects)

```
→ Full Landing Page (like SaaS website)
→ Admin Dashboard (charts, tables, sidebar, modals)
→ E-commerce Storefront (product list, filters, cart UI)
→ Portfolio Website (with responsive sections, animations)
```

## Cheatsheet (Core Classes)

### Spacing

- Margin: `m-4`, `mx-8`, `my-2`
- Padding: `p-4`, `px-6`, `py-2`
- Gap (grid/flex): `gap-4`
- Space between children: `space-x-4`, `space-y-6`

### Layout

- Flex: `flex`, `justify-between`, `items-center`, `flex-col`, `flex-wrap`
- Grid: grid, `grid-cols-2`, `md:grid-cols-4`, `gap-6`
- Width/Height: `w-1/2, h-64`, `max-w-xl`
- Position: `absolute`, `relative`, `top-0`, `z-50`

### Typography

- Font size: `text-sm`, `text-lg`, `text-4xl`
- Font weight: `font-bold`, `font-medium`
- Colors: `text-gray-700`, `text-blue-600`
- Alignment: `text-center`, `text-right`

### Colors + Backgrounds

- Background: `bg-gray-100`, `bg-blue-600`
- Hover: `hover:bg-blue-700`
- Gradient: `bg-gradient-to-r` `from-blue-500` `to-purple-600`

### Borders & Effects

- Border: `border`, `border-gray-300`, `rounded-lg`, `rounded-full`
- Shadow: `shadow`, `shadow-lg`
- Transition: `transition`, `duration-300`, `ease-in-out`

---

And for anyone interested in building layouts that look goodddd!
This is for you:

# Tailwind CSS Curriculum

### 1. Foundations

- **What Tailwind is**: utility-first, atomic classes, mobile-first.
- **Setup methods**:
  - CDN (quick prototyping)
  - Local build (`npx tailwindcss`)
  - Frameworks (React/Vite, Next.js, etc.)
- **Editor setup**: Tailwind IntelliSense, Prettier Tailwind plugin.
- **Core file structure**: `@tailwind base; @tailwind components; @tailwind utilities;`

---

### 2. Utility System (The Core)

- **Spacing**: `m-`, `p-`, `space-x-*`, `space-y-*`
- **Sizing**: `w-*`, `h-*`, `min/max-*`, fractional widths
- **Typography**: `text-*`, `font-*`, `leading-*`, `tracking-*`
- **Colors**: text, background, border (`bg-*`, `text-*`, `border-*`)
- **Borders & Radius**: `border`, `rounded-*`
- **Shadows & Effects**: `shadow-*`, `opacity-*`, `mix-blend-*`

### 3. Layout & Positioning

- **Display utilities**: `block`, `inline`, `inline-block`, `flex`, `grid`, `hidden`
- **Flexbox**:
  - Direction (`flex-row`, `flex-col`)
  - Justify & align (`justify-*`, `items-*`, `content-*`)
  - Grow/shrink (`flex-1`, `flex-shrink-0`)
- **Grid**:
  - Columns (`grid-cols-*`)
  - Rows (`grid-rows-*`)
  - Gaps (`gap-*`)
  - Spanning (`col-span-*`, `row-span-*`)
- **Positioning**: `relative`, `absolute`, `fixed`, `sticky`, `z-*`
- **Overflow & object fit**: `overflow-*`, `object-cover`, `object-contain`

### 4. Responsive Design

- **Breakpoints**:
  - `sm` (640px), `md` (768px), `lg` (1024px), `xl` (1280px), `2xl` (1536px)
- **Mobile-first philosophy**
- **Responsive utilities**: `text-sm md:text-lg lg:text-xl`
- **Container**: `container`, `mx-auto`, max-width breakpoints
- **Container queries**: `@container`, `container-type`

### 5. State & Variant System

- **Pseudo-classes**:
  - `hover:`, `focus:`, `active:`, `disabled:`, `visited:`
- **Advanced variants**:
  - `group-hover:`
  - `peer-checked:`
  - `aria-*`
  - `focus-visible:`
  - `motion-safe:`
- **Dark mode**:
  - Config (`class` vs `media`)
  - Usage: `dark:bg-gray-900`

### 6. Advanced Styling

- **Backgrounds**:
  - Gradients (`bg-gradient-to-r`)
  - Background position/size
- **Transforms & Transitions**:
  - `scale-*`, `rotate-*`, `translate-*`
  - `transition`, `duration-*`, `ease-*`
- **Animations**:
  - Built-in utilities (`animate-bounce`, `animate-spin`)
  - Custom animations via `@keyframes`
- **Filters**:
  - `blur-*`, `brightness-*`, `backdrop-blur-*`
- **Typography enhancements**:
  - `truncate`, `line-clamp-*`
  - Lists, text-decoration, text-shadow (custom)

### 7. Forms & Interactions

- **Form controls**: inputs, selects, checkboxes, radios
- **Plugin**: `@tailwindcss/forms`
- **Focus rings & accessibility** (`focus:ring-*`)
- **Validation states**: `invalid:`, `required:`

### 8. Plugins & Extensibility

- **First-party plugins**:
  - `@tailwindcss/forms`
  - `@tailwindcss/typography` (`prose`)
  - `@tailwindcss/aspect-ratio`
  - `@tailwindcss/container-queries`
- **Creating custom plugins**:
  - `addUtilities`
  - `addComponents`
  - `addVariant`
- **Extending the theme** (`@theme` in v4 or `extend` in v3)

### 9. Best Practices & Professional Usage

- **Design tokens**: define brand colors, fonts, spacing scale
- **Reusability**: `@apply` for common component classes
- **Organization**:
  - Extract components (React/Vue/partials)
  - Layout wrappers
- **Productivity**:
  - Prettier Tailwind plugin (auto class sorting)
  - IntelliSense + JIT instant feedback
- **Performance**:
  - Purge unused CSS (content paths)
  - Minification
- **Accessibility**:
  - `sr-only`, `focus-visible`
  - Dark/light preference
  - Motion-safe animations

### 10. Expert-Level Techniques (Top 1%)

- **Complex layouts**:
  - Overlapping grids
  - Magazine-style designs
  - Responsive dashboards
- **Modern UI trends**:
  - Glassmorphism
  - Neumorphism
  - Animated gradients
  - Layered shadows
- **Container queries mastery**
- **Component composition** (Headless UI, Radix + Tailwind)
- **Custom plugin libraries** (building your own UI kit)
- **Scaling Tailwind**:
  - For teams (naming conventions, design systems)
  - Large projects with hundreds of components
- **Integration**:
  - Tailwind + Framer Motion / GSAP (for animations)
  - Tailwind + React (clsx, tailwind-variants)

### 11. References (Always at Hand)

- [Tailwind Docs](https://tailwindcss.com/docs) — primary source
- [Tailwind Play](https://play.tailwindcss.com) — instant sandbox
- [Heroicons](https://heroicons.com/) — SVG icons
- [Headless UI](https://headlessui.com/) — unstyled accessible components
- [Prettier Plugin](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)
