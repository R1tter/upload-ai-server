# 🎥 Upload AI

Upload AI is an application that allows users to upload a video, transcribe it to audio, and then transcribe that audio to text. The magic begins when we use the powerful OpenAI API to interpret this text. Based on a prompt generated by the application, we provide suggestions for titles, descriptions, and hashtags, all adjusted according to the "creativity temperature" defined for the AI model.

## 💡 Project Details

**Objective:** 
- Video Upload 
- Conversion to Audio 
- Audio Transcription to Text
- Title, Description, and Hashtags suggestions using OpenAI

**Frontend Tools/Technologies:**
- React
- Vite
- TypeScript
- Tailwind

**Backend Tools/Technologies:**
- Node
- TypeScript
- Fastify

**Results:** 
An integrated system that streamlines and enriches the content creation process through Artificial Intelligence.

## 🚀 Getting Started

### Frontend

Here are the available scripts for working on the frontend:

#### `npm run dev`
Starts the development server using Vite.

#### `npm run build`
First, it compiles the project with TypeScript (`tsc`), then builds the project for production using Vite.

#### `npm run lint`
Lints the code, focusing on `.ts` and `.tsx` files, reporting unused directives, and failing on any warnings.

#### `npm run preview`
Offers a built project preview using Vite.

### Backend

Here are the available scripts for working on the backend:

#### `npm run dev`
Runs the server in development mode, monitoring changes with `tsx`.

#### `npm run prisma:seed`
Runs the database seed using Prisma.

To execute any of the above scripts, you can use:
```sh
npm run [script-name]
```

For example, to start the frontend development server:
```sh
npm run dev
```

And to start the backend development server:
```sh
npm run dev
```