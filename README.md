# Devlify CodeGen

**Auto-Generate API Clients & SDKs by [Devlify Marketplace](https://github.com/devlify-marketplace)**

Generate API client libraries, server stubs, and documentation from OpenAPI/Swagger specifications. Define your API once, generate type-safe code for 40+ languages.

## Features

- **40+ languages**: TypeScript, Python, Java, Go, Rust, C#, Kotlin, Swift, Ruby, PHP, and more
- Generates API clients, server stubs, and API documentation
- Extensible with custom Mustache templates
- Available as CLI, Maven/Gradle plugin, or Docker image
- Active community with 20k+ GitHub stars

## Quick Start

```bash
# Via Docker
docker run --rm -v "${PWD}:/local" openapitools/openapi-generator-cli generate \
  -i /local/api.yaml \
  -g typescript-axios \
  -o /local/generated-client

# Via npm
npx @openapitools/openapi-generator-cli generate \
  -i api.yaml \
  -g python \
  -o ./generated-client
```

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.

---

*Part of the [Devlify Marketplace](https://github.com/devlify-marketplace) ecosystem.*
