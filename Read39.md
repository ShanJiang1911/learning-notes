#### [NextJs](https://nextjs.org/learn/basics/create-nextjs-app)
* Create a Next.js App:
  * ```npx create-next-app your-project-name```
  * ```cd your-project-name```
  * ```npm run dev``` The server should work now
* Navigate Between Pages:
  * add 'pages/any-name.js' to the 'pages' directory
  * ```export default function AnyName() { return <h1>First Post<h1>}```
  * ```import Link from 'next/link'```   
* Assets, Metadata, and CSS:
  * Next.js can serve static assets, like images, under the top-level public directory
  * Open ```pages/index.js``` to make changes
  * ```import Head from 'next/head'```
  * add third party JavaScript: add```<script src="https://connect.facebook.net/en_US/sdk.js" /></Head>```under title in <Head>
  * Using the Script Component: ```import Script from 'next/script'```
  * CSS styling: create a layout module then import to pages
  * Create global CSS: add ```pages/_app.js``` and put ```export default function App({ Component, pageProps }) {return <Component {...pageProps} />}``` inside
  * Polishing Layout
#### [React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)
* React context: allows users to pass down and use (consume) data in whatever component needed in our React app without using props
* helps avoid props drilling
* ```React.createContext()```
* ```React.useContext()```

#### [Why I’m using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)


#### [Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)


#### [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)


[<--Back](README.md)