# tayori-client
This repository has template to Tayori's client
Tayori is owned CMS to manage blog written with markdown

## Environment variable
`tayori-client` is needed to set some environment variables to `.env`

#### TAYORI_ORIGIN
Please set origin like `http://localhost:3000`

#### NEXT_PUBLIC_MIDDLE_COMPONENT_PATH
`NEXT_PUBLIC_MIDDLE_COMPONENT_PATH` is used to convert markdown to original-component on client.
Please set directory path where is storaged component's files.

## How to start
1. set environment variables to `.env`(`.env.local` etc...)
2. run `npm install`
3. run `npm run dev`
