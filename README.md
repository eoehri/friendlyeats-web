# Friendly Eats with Next.js + Firebase

The codelab has the full instructions, but as a quick start, you can do this.

## Introduction

FriendlyEats is a restaurant recommendation app built on Cloud Firestore.
For more information about Firestore visit [the docs][firestore-docs].

## Run the application

1. In your terminal, run:

```sh
cd .firebase
npm i
```

```sh
firebase emulators:start --project demo-codelab-nextjs
```

2. Copy the file `lib/firebase/config-copy.js` to `lib/firebase/config.js` and fill in the values from the Firebase console.

3. In a new terminal tab/window, run:

```sh
npm i
npm run dev
```

4. In your browser, open the URL: `http://localhost:3000`

## Use the application

1. While on `http://localhost:3000/` within your browser, click the "Sign in" button in the top right corner and sign in.
2. In the dropdown menu in the top right menu, select "Add sample restaurants".
