# FoodTruckNerdz Help Center

This repository contains the customer-facing help documentation for FoodTruckNerdz.

## Structure

- **Astro + Starlight**: Landing page at root (`help.foodtrucknerdz.com`) and documentation at `/docs` (`help.foodtrucknerdz.com/docs`)
- **Antora Docs**: Located in `docs/` for use with the internal documentation site's Antora playbook

## Development

```bash
# Install dependencies
pnpm install

# Start dev server
pnpm dev

# Build for production
pnpm build
```

## Documentation

- **Public Site**: `help.foodtrucknerdz.com` (landing) and `help.foodtrucknerdz.com/docs` (Starlight docs)
- **Internal Antora**: Included in `docs.foodtrucknerdz.com` via the `docs` repository's Antora playbook
