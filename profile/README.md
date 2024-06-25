![Mock Service Worker banner](../banner.jpg)

[Mock Service Worker](https://github.com/mswjs/msw) is an API mocking library for browser and Node.js that uses a Service Worker to intercept requests that actually happened. This means no request client stubs and unmatched resilience when it comes to request integrity, as your app now performs requests the same way it does in production.

- 💬 [**Ask a question**](https://github.com/mswjs/msw/discussions/new)
- 📙 [Read the documentation](https://mswjs.io/docs)
- 🔍 [Browse usage examples](https://github.com/mswjs/examples)
- 🏆 [Make your first contribution](https://github.com/mswjs/msw/labels/help%20wanted)

## Ecosystem

We favor composition in both how we write our code and how we distribute it. That's why instead of building a single monolithic package that's responsible for too many things, we distribute the [core module](https://www.npmjs.com/package/msw) with the essentials that everybody could use, and provide a set of standalone _extensions_ that enable specific workflows and push the developer experience even further.

### Native extensions

| Package                                                            | Description                                      |
| ------------------------------------------------------------------ | ------------------------------------------------ |
| [@mswjs/data](https://github.com/mswjs/data)                       | Model and query your mock data (fixtures).       |
| [@mswjs/http-middleware](https://github.com/mswjs/http-middleware) | Spawn an HTTP server from your request handlers. |

### Third-party extensions

| Package                                                             | Description                                                       |
| ------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [msw-storybook-addon](https://github.com/mswjs/msw-storybook-addon) | Official Storybook add-on for MSW to write and test your stories. |

## Support us!

This project is the result of hundreds of hours of work that our contributors spend so that you could enjoy the best API mocking experience there is to offer. If you'd like us to bring new features and mitigate issues more effectively, consider supporting us.

👉 [**Support Mock Service Worker via GitHub Sponsors**](https://github.com/sponsors/mswjs)

_By becoming a baker you help us ensure a bright future for the project. We value and treasure every contribution, big or small. Thank you_.
