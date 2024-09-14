``router.refresh()``: Refresh the current route. Making a new request to the server, re-fetching data requests, and re-rendering ``Server Components``. The client will merge the updated ``React Server Component`` payload without losing unaffected client-side ``React`` (e.g. ``useState``) or ``browser state`` (e.g. scroll position).
## useSWE, Tanstack Router, RTK Query
They are also have polling features and interval revalidations

[https://redux-toolkit.js.org/rtk-query/usage/polling](https://redux-toolkit.js.org/rtk-query/usage/polling)
[https://swr.vercel.app/docs/revalidation](https://swr.vercel.app/docs/revalidation)
[https://tanstack.com/query/v4/docs/framework/react/guides/important-defaults](https://tanstack.com/query/v4/docs/framework/react/guides/important-defaults)
