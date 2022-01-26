### [Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)
* Pages that begin with "[" and end with "]" are dynamic routes in Next.js. e.g. [id].js 
*   ```
        export async function getStaticPaths() {
        // Return a list of possible value for id
        }
    ```
* ```
    export async function getStaticProps({ params }) {
     // Fetch necessary data for the blog post using params.id
    }
  ```
* ```export function getAllPostIds() {}```
* ```
    import { getAllPostIds } from '../../lib/posts'

    export async function getStaticPaths() {
        const paths = getAllPostIds()
        return {
            paths,
            fallback: false
        }
    }
  ```

### [Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)
* How to deploy Next.js to Vercel
* Next.js can be deployed to any hosting provider that supports Node.js.

### [Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)


### [Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-serving)



[<--Back](README.md)