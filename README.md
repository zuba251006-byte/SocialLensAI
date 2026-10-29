# Social Lens AI

A responsive social publishing studio built with React and Vite. Create a post, select exactly which social channels should receive it, review the live preview, and publish to see an individual status for every selected channel. The analytics cards use sample data.

## Requirements

- Node.js 18 or later
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. No account or sign-up is required.

## Production build

```bash
npm run build
npm run preview
```

## Notes

The publishing flow is a front-end demonstration: it simulates per-channel publishing results and does not connect to social network APIs. Image and video uploads are previewed locally in your browser. Connect authorized platform APIs and a backend publishing service to enable live publishing.
