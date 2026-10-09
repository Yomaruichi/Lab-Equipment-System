# Lab-Equipment-System

## Authors

- Lunele Iven Moscoso
- John Dave Valentin
- Ethan Sean Gapulan
- Marc Raven Sian

## Figma Design

link:`https://www.figma.com/design/ZDwpMP3tRk4zyvx14o6V6f/142-Lab-Final-Project?node-id=15-22&t=2jdRe1zoi1zIuKeq-1`

## Tech Stack

| Layer | Language |
| --- | --- |
| Frontend | React |
| Backend | Node.js & Express.js |
| Database | Firebase |

## Requirements

- Git
- npm
- Node.js (20.x+)
- A Firebase database

## Installation & Initialization

1. Clone the repo

```bash
git clone https://github.com/Yomaruichi/Lab-Equipment-System.git
cd Lab-Equipment-System
```

2. Create `.env` file in project root

```bash
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
VITE_FIREBASE_MEASUREMENT_ID=
```

3. Set up the client

```bash
cd client
npm install
```

4. Run the client

If you're in the root folder

```bash
cd client
npm run dev
```

else

```bash
npm run dev
```

default address: http://localhost:5173/

5. Set up the server

```bash
cd ../server
npm install
```

6. Run the server

```bash
npm run start
```