# web603-hw-w3d1

## Getting Started

### Step 1: Create the App

To create the React application named `react-fb_login`:
```bash
$ npx create-react-app react-fb_login
```

### Step 2: Fix and Install Dependencies:

The application will need `react-facebook-login`, which depends on React 16. However, `npx create-react-app` will automatically install React 18 (the latest version as of January 2024), so a few dependencies related need to be downgraded.

In `package.json`, change `"dependencies"` to
```json
  "dependencies": {
    "@testing-library/jest-dom": "^5.17.0",
    "@testing-library/react": "^12.0.0",
    "@testing-library/user-event": "^12.0.0",
    "react": "^16.0.0",
    "react-dom": "^16.0.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  }
```

And then install `react-facebook-login` by
```bash
$ npm install react-facebook-login
```
