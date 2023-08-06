# Chat UI

This is my solution for a technical interview test at ALDI.

## ⚙️ Installation

- `npm install`: Install dependencies.

## 🚀 Usage

- `npm run dev`: Start a development server using Vite.
- `npm run build`: Build the project using TypeScript and Vite.
- `npm run preview`: Serve the production build locally for previewing before deployment.
- `npm run lint`: Run ESLint on all applicable files with the TypeScript and TypeScript React extensions.
- `npm run lint:prettier`: Check if all files are formatted according to the Prettier configuration.
- `npm run lint:prettier:fix`: Automatically fix any Prettier formatting issues in the codebase.
- `npm run prepare`: Install Husky, a tool for creating Git hooks, in the local repository.
- `npm run commit`: Open a prompt for writing a commit message according to the Conventional Commits specification.
- `npm run storybook`: Start Storybook, an interactive development environment for testing and documenting UI components.
- `npm run build-storybook`: Build Storybook into a static web application for deployment.
- `npm run test`: Run tests using Vitest.

## 🚀 Cleaning up the example code

- Remove the contents of the `src/components/` folder
- Remove each subfolder in the `src/pages/Root/` folder
- Clean the `src/pages/Root/Root.tsx` component
- Remove any interfaces from the `src/interfaces` folder
- Remove any hookes from the `src/queries` folder
- Remove the handler in `src/mocks/handlers.ts`
- Revise the routes in the `src/main.tsx` file
- Revise the auth logic in the `src/pages/PrivateOutlet.tsx` file
- Maybe revise the `src/pages/Error/ErrorPage.tsx` file
- Maybe revise the remaining mr templates in the `.gitlab/merge_request_templates/` folder
- Revise the languages in the `src/i18n/useLocaleContext.ts` file
- Revise the messages in the `public/i18n` folder
- Revise the metadata in `package.json`
- Revise the `README.md`
- Consider adding labels on GitLab to organize MRs (Project information -> Labels)
- Delete section of the README.
