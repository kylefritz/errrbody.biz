# Errrbody.biz

Post & find gigs with people you kind of know.

## Development

To install dependencies:

```bash
bun install
```

To start a development server:

```bash
bun dev
```

To build for production:

```bash
bun run build
```

To run for production:

```bash
bun start
```

## Deploying to Vercel

### Option 1: Deploy with Vercel CLI

1. Install the Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to link your project and deploy.

### Option 2: Deploy via Git Integration

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel will automatically detect the configuration from `vercel.json`
5. Click "Deploy"

The build settings are configured in `vercel.json`:
- Build Command: `bun run build`
- Output Directory: `dist`
- Install Command: `bun install`

---

This project was created using `bun init` in bun v1.3.2. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.
