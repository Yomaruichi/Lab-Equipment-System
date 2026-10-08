# Lab-Equipment-System

## Authors

- Lunele Iven Moscoso
- John Dave Valentin
- Ethan Sean Gapulan
- Marc Raven Sian

## Tech Stack

| Layer | Language |
| --- | --- |
| Frontend | React |
| Backend | Node.js & Express.js |
| Database | MongoDB |

## Requirements

- Git
- npm
- Node.js (20.x+)
- A MongoDB database

## Installation & Initialization

1. Clone the repo

```bash
git clone https://github.com/Yomaruichi/Lab-Equipment-System.git
cd Lab-Equipment-System
```

2. Create `.env` file in project root

```bash
MONGO_DB=your-mongodb-connection-string
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