# My Next.js Notes

# Basic routing : 
Next.js has an awsome routing feature where we can just make a folder in the directory to make a new route . 

#Advanced Routing :
For better routing and more functions we use "useRouter" 
- import it with `import { useRouter } from  'next/router'`
- intialization `const  router  =  useRouter()`
- the following are some methods we can use from it :
	- ### [router.push](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerpush)
	- ### [router.replace](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerreplace)
	- ### [router.prefetch](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerprefetch)
	- ### [router.beforePopState](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerbeforepopstate)
	- ### [router.back](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerback)
	- ### [router.reload](https://nextjs.org/docs/pages/api-reference/functions/use-router#routerreload)

# dynamic Routing  :

<!--stackedit_data:
eyJoaXN0b3J5IjpbNTAyMzk3MTA4LDE4ODgyNzk5MDJdfQ==
-->