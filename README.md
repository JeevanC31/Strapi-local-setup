# Strapi Local Setup

## Objective

The objective of this task is to clone the Strapi repository, run it locally, explore the project structure, start the Admin Panel, create a sample content type, and document the complete process.

---

## Prerequisites

- Node.js (v18.x recommended)
- Yarn
- Git

---

```bash
## Step 1: Clone the Strapi Repository


git clone https://github.com/strapi/strapi.git
cd strapi

---

## Step 2: Install Dependencies

yarn install

## Step 3: Run Strapi Locally

Navigate to the example Strapi application and start the development server using Yarn.

cd examples/getstarted
yarn develop
http://localhost:1337/admin

## Step 4: Create a Sample Content Type

Using the Content-Type Builder in the Admin Panel:

- Created a collection type named `Article`
- Added fields:
  - Title (Text)
  - Description (Rich Text)
  - Published Date (Date)
- Saved the content type and allowed Strapi to restart

## Step 5: Add Sample Content

Using the Content Manager:

- Created a sample entry for the Article content type
- Saved and published the entry

```

```

```
