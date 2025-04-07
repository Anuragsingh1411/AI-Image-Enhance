# AI Image Enhance

This project provides an application for enhancing images using AI technology.

## Setup Instructions

### Environment Variables

1. Create a `.env` file in the root directory
2. Copy the contents from `.env.example` to your `.env` file
3. Replace the placeholder values with your actual API keys and configuration

```
VITE_API_KEY=your_actual_api_key_here
```

**Note:** The `.env` file is excluded from version control for security reasons. Never commit your actual API keys to GitHub.

## Tech Stack

This project is built with React and Vite, providing a minimal setup with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
