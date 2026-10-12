# Graph Report - MENUPATIOS  (2026-09-19)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 670 nodes · 1186 edges · 53 communities (32 shown, 20 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `df01f351`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- dependencies
- field.tsx
- hooks/use-toast.ts
- sidebar.tsx
- lib/utils.ts
- alert-dialog.tsx
- cn
- app/page.tsx
- command.tsx
- src/app/layout.tsx
- compilerOptions
- components.json
- menubar.tsx
- package.json
- context-menu.tsx
- dropdown-menu.tsx
- form.tsx
- carousel.tsx
- chart.tsx
- drawer.tsx
- select.tsx
- sheet.tsx
- input-group.tsx
- navigation-menu.tsx
- toggle-group.tsx
- react
- devDependencies
- card.tsx
- empty.tsx
- theme-provider.tsx
- popover.tsx
- tabs.tsx
- collapsible.tsx
- hover-card.tsx
- scripts
- scroll-area.tsx
- TestimonialCarousel.tsx
- aspect-ratio.tsx
- progress.tsx
- slider.tsx
- switch.tsx
- next.config.mjs
- AnimatedCounter.tsx
- FloatingElements.tsx
- ImageParallax.tsx
- MagneticButton.tsx
- MenuItemCard.tsx
- SectionReveal.tsx
- TestimonialCard.tsx
- eslint.config.mjs
- next-env.d.ts
- postcss.config.mjs

## God Nodes (most connected - your core abstractions)
1. `cn()` - 279 edges
2. `react` - 63 edges
3. `lucide-react` - 25 edges
4. `compilerOptions` - 16 edges
5. `class-variance-authority` - 14 edges
6. `buttonVariants` - 9 edges
7. `Button()` - 8 edges
8. `@radix-ui/react-slot` - 8 edges
9. `Separator()` - 6 edges
10. `aliases` - 6 edges

## Surprising Connections (you probably didn't know these)
- `AlertDescription()` --calls--> `cn()`  [EXTRACTED]
  components/ui/alert.tsx → lib/utils.ts
- `AlertTitle()` --calls--> `cn()`  [EXTRACTED]
  components/ui/alert.tsx → lib/utils.ts
- `ButtonGroupSeparator()` --calls--> `cn()`  [EXTRACTED]
  components/ui/button-group.tsx → lib/utils.ts
- `ButtonGroupText()` --calls--> `cn()`  [EXTRACTED]
  components/ui/button-group.tsx → lib/utils.ts
- `FieldContent()` --calls--> `cn()`  [EXTRACTED]
  components/ui/field.tsx → lib/utils.ts

## Import Cycles
- None detected.

## Communities (53 total, 20 thin omitted)

### Community 0 - "dependencies"
Cohesion: 0.04
Nodes (51): dependencies, autoprefixer, class-variance-authority, clsx, cmdk, date-fns, embla-carousel-react, framer-motion (+43 more)

### Community 1 - "field.tsx"
Cohesion: 0.06
Nodes (37): Alert(), AlertDescription(), AlertTitle(), alertVariants, Badge(), badgeVariants, ButtonGroup(), ButtonGroupSeparator() (+29 more)

### Community 2 - "hooks/use-toast.ts"
Cohesion: 0.07
Nodes (39): Toast, ToastAction, ToastActionElement, ToastClose, ToastDescription, ToastProps, ToastTitle, toastVariants (+31 more)

### Community 3 - "sidebar.tsx"
Cohesion: 0.07
Nodes (35): Input(), Sidebar(), SidebarContent(), SidebarContext, SidebarContextProps, SidebarFooter(), SidebarGroup(), SidebarGroupAction() (+27 more)

### Community 4 - "lib/utils.ts"
Cohesion: 0.06
Nodes (24): AccordionContent(), AccordionItem(), AccordionTrigger(), Checkbox(), InputOTP(), InputOTPGroup(), InputOTPSlot(), RadioGroup() (+16 more)

### Community 5 - "alert-dialog.tsx"
Cohesion: 0.10
Nodes (21): AlertDialogAction(), AlertDialogCancel(), AlertDialogContent(), AlertDialogDescription(), AlertDialogFooter(), AlertDialogHeader(), AlertDialogOverlay(), AlertDialogTitle() (+13 more)

### Community 6 - "cn"
Cohesion: 0.14
Nodes (21): Avatar(), AvatarFallback(), AvatarImage(), BreadcrumbEllipsis(), BreadcrumbItem(), BreadcrumbLink(), BreadcrumbList(), BreadcrumbPage() (+13 more)

### Community 7 - "app/page.tsx"
Cohesion: 0.10
Nodes (21): adicionales, bebidas, cazuelaMariscos, cervezas, ceviches, crepes, fadeInUp, formatPrice() (+13 more)

### Community 8 - "command.tsx"
Cohesion: 0.11
Nodes (16): Command(), CommandDialog(), CommandGroup(), CommandInput(), CommandItem(), CommandList(), CommandSeparator(), CommandShortcut() (+8 more)

### Community 9 - "src/app/layout.tsx"
Cohesion: 0.10
Nodes (11): metadata, oswald, pacifico, robotoCondensed, nextConfig, next, greatVibes, metadata (+3 more)

### Community 10 - "compilerOptions"
Cohesion: 0.11
Nodes (18): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+10 more)

### Community 11 - "components.json"
Cohesion: 0.11
Nodes (17): aliases, components, hooks, lib, ui, utils, iconLibrary, rsc (+9 more)

### Community 12 - "menubar.tsx"
Cohesion: 0.11
Nodes (12): Menubar(), MenubarCheckboxItem(), MenubarContent(), MenubarItem(), MenubarLabel(), MenubarRadioItem(), MenubarSeparator(), MenubarShortcut() (+4 more)

### Community 13 - "package.json"
Cohesion: 0.11
Nodes (17): name, private, version, autoprefixer, date-fns, @hookform/resolvers, postcss, react-dom (+9 more)

### Community 14 - "context-menu.tsx"
Cohesion: 0.12
Nodes (10): ContextMenuCheckboxItem(), ContextMenuContent(), ContextMenuItem(), ContextMenuLabel(), ContextMenuRadioItem(), ContextMenuSeparator(), ContextMenuShortcut(), ContextMenuSubContent() (+2 more)

### Community 15 - "dropdown-menu.tsx"
Cohesion: 0.12
Nodes (10): DropdownMenuCheckboxItem(), DropdownMenuContent(), DropdownMenuItem(), DropdownMenuLabel(), DropdownMenuRadioItem(), DropdownMenuSeparator(), DropdownMenuShortcut(), DropdownMenuSubContent() (+2 more)

### Community 16 - "form.tsx"
Cohesion: 0.17
Nodes (13): FormControl(), FormDescription(), FormFieldContext, FormFieldContextValue, FormItem(), FormItemContext, FormItemContextValue, FormLabel() (+5 more)

### Community 17 - "carousel.tsx"
Cohesion: 0.17
Nodes (14): Carousel(), CarouselApi, CarouselContent(), CarouselContext, CarouselContextProps, CarouselItem(), CarouselNext(), CarouselOptions (+6 more)

### Community 18 - "chart.tsx"
Cohesion: 0.23
Nodes (10): ChartConfig, ChartContainer(), ChartContext, ChartContextProps, ChartLegendContent(), ChartTooltipContent(), getPayloadConfigFromPayload(), THEMES (+2 more)

### Community 19 - "drawer.tsx"
Cohesion: 0.17
Nodes (7): DrawerContent(), DrawerDescription(), DrawerFooter(), DrawerHeader(), DrawerOverlay(), DrawerTitle(), vaul

### Community 20 - "select.tsx"
Cohesion: 0.17
Nodes (8): SelectContent(), SelectItem(), SelectLabel(), SelectScrollDownButton(), SelectScrollUpButton(), SelectSeparator(), SelectTrigger(), @radix-ui/react-select

### Community 21 - "sheet.tsx"
Cohesion: 0.17
Nodes (8): Sheet(), SheetContent(), SheetDescription(), SheetFooter(), SheetHeader(), SheetOverlay(), SheetTitle(), @radix-ui/react-dialog

### Community 22 - "input-group.tsx"
Cohesion: 0.24
Nodes (9): InputGroup(), InputGroupAddon(), inputGroupAddonVariants, InputGroupButton(), inputGroupButtonVariants, InputGroupInput(), InputGroupText(), InputGroupTextarea() (+1 more)

### Community 23 - "navigation-menu.tsx"
Cohesion: 0.20
Nodes (10): NavigationMenu(), NavigationMenuContent(), NavigationMenuIndicator(), NavigationMenuItem(), NavigationMenuLink(), NavigationMenuList(), NavigationMenuTrigger(), navigationMenuTriggerStyle (+2 more)

### Community 24 - "toggle-group.tsx"
Cohesion: 0.31
Nodes (7): ToggleGroup(), ToggleGroupContext, ToggleGroupItem(), Toggle(), toggleVariants, @radix-ui/react-toggle, @radix-ui/react-toggle-group

### Community 25 - "react"
Cohesion: 0.22
Nodes (3): react, BadgeProps, FeatureCardProps

### Community 26 - "devDependencies"
Cohesion: 0.22
Nodes (9): devDependencies, postcss, tailwindcss, @tailwindcss/postcss, tw-animate-css, @types/node, @types/react, @types/react-dom (+1 more)

### Community 27 - "card.tsx"
Cohesion: 0.25
Nodes (7): Card(), CardAction(), CardContent(), CardDescription(), CardFooter(), CardHeader(), CardTitle()

### Community 28 - "empty.tsx"
Cohesion: 0.29
Nodes (7): Empty(), EmptyContent(), EmptyDescription(), EmptyHeader(), EmptyMedia(), emptyMediaVariants, EmptyTitle()

### Community 31 - "tabs.tsx"
Cohesion: 0.33
Nodes (5): Tabs(), TabsContent(), TabsList(), TabsTrigger(), @radix-ui/react-tabs

### Community 34 - "scripts"
Cohesion: 0.40
Nodes (5): scripts, build, dev, lint, start

### Community 35 - "scroll-area.tsx"
Cohesion: 0.50
Nodes (3): ScrollArea(), ScrollBar(), @radix-ui/react-scroll-area

## Knowledge Gaps
- **191 isolated node(s):** `FormFieldContextValue`, `FormItemContextValue`, `CarouselApi`, `CarouselContextProps`, `CarouselOptions` (+186 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 267 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **20 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `cn()` connect `cn` to `field.tsx`, `hooks/use-toast.ts`, `sidebar.tsx`, `lib/utils.ts`, `alert-dialog.tsx`, `command.tsx`, `menubar.tsx`, `context-menu.tsx`, `dropdown-menu.tsx`, `form.tsx`, `carousel.tsx`, `chart.tsx`, `drawer.tsx`, `select.tsx`, `sheet.tsx`, `input-group.tsx`, `navigation-menu.tsx`, `toggle-group.tsx`, `card.tsx`, `empty.tsx`, `popover.tsx`, `tabs.tsx`, `hover-card.tsx`, `scroll-area.tsx`, `progress.tsx`, `slider.tsx`, `switch.tsx`?**
  _High betweenness centrality (0.337) - this node is a cross-community bridge._
- **Why does `react` connect `react` to `field.tsx`, `hooks/use-toast.ts`, `sidebar.tsx`, `lib/utils.ts`, `alert-dialog.tsx`, `cn`, `app/page.tsx`, `command.tsx`, `menubar.tsx`, `package.json`, `context-menu.tsx`, `dropdown-menu.tsx`, `form.tsx`, `carousel.tsx`, `chart.tsx`, `drawer.tsx`, `select.tsx`, `sheet.tsx`, `input-group.tsx`, `navigation-menu.tsx`, `toggle-group.tsx`, `card.tsx`, `theme-provider.tsx`, `popover.tsx`, `tabs.tsx`, `hover-card.tsx`, `scroll-area.tsx`, `TestimonialCarousel.tsx`, `progress.tsx`, `slider.tsx`, `switch.tsx`, `AnimatedCounter.tsx`, `FloatingElements.tsx`, `ImageParallax.tsx`, `MagneticButton.tsx`, `MenuItemCard.tsx`, `SectionReveal.tsx`, `TestimonialCard.tsx`?**
  _High betweenness centrality (0.269) - this node is a cross-community bridge._
- **Why does `dependencies` connect `dependencies` to `package.json`?**
  _High betweenness centrality (0.133) - this node is a cross-community bridge._
- **What connects `FormFieldContextValue`, `FormItemContextValue`, `CarouselApi` to the rest of the system?**
  _191 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `dependencies` be split into smaller, more focused modules?**
  _Cohesion score 0.0392156862745098 - nodes in this community are weakly interconnected._
- **Should `field.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.06090808416389812 - nodes in this community are weakly interconnected._
- **Should `hooks/use-toast.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.07419712070874862 - nodes in this community are weakly interconnected._