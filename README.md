# mishika-blog

Step 1: Project Setup

1. Create Next.js app
   npx create-next-app@latest mishika-blog
   cd mishika-blog

2. Install dependencies
   npm install tailwindcss @tailwindcss/typography next-mdx-remote gray-matter
   npx tailwindcss init -p

3. tailwind.config.ts

ts
Copy
Edit
import type { Config } from 'tailwindcss';

const config: Config = {
  content: [
    './src/app/**/*.{ts,tsx,js,jsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
export default config;

4. 
