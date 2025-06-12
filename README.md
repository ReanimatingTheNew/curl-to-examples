# curl-to Examples

A comprehensive collection of real-world examples showing how to convert cURL commands to various programming languages using [<sup>1</sup>](https://curl-to.com).

Try [curl-to.com](https://curl-to.com)

## 🎯 Why This Repository?

While [<sup>1</sup>](https://curl-to.com) makes it easy to convert any cURL command, this repository provides:

- ✅ **Real-world examples** from popular APIs
- ✅ **Best practices** for each programming language
- ✅ **Common patterns** you'll use repeatedly
- ✅ **Side-by-side comparisons** to understand conversions better
- ✅ **Copy-paste ready** code snippets

## 📚 Table of Contents

- [Quick Start](#quick-start)
- [Examples by Category](#examples-by-category)
  - [Basic Requests](#basic-requests)
  - [Authentication](#authentication)
  - [File Uploads](#file-uploads)
  - [JSON APIs](#json-apis)
  - [Webhooks](#webhooks)
- [Supported Languages](#supported-languages)
- [Contributing](#contributing)

## 🚀 Quick Start

### Basic GET Request

**cURL:**
```bash
curl https://api.github.com/users/github
```

**Python (requests):**
```python
import requests

response = requests.get('https://api.github.com/users/github')
print(response.json())
```

**JavaScript (fetch):**
```javascript
fetch("https://api.github.com/users/github")
  .then(response => response.json())
  .then(data => console.log(data));
```

[See more examples →](./examples/basic-requests)

## 📂 Examples by Category

### Basic Requests
- [GET requests](./examples/basic-requests/get.md)
- [POST requests](./examples/basic-requests/post.md)
- [PUT requests](./examples/basic-requests/put.md)
- [DELETE requests](./examples/basic-requests/delete.md)
- [Custom headers](./examples/basic-requests/headers.md)

### Authentication
- [Bearer token](./examples/authentication/bearer.md)
- [Basic auth](./examples/authentication/basic.md)
- [API key](./examples/authentication/api-key.md)
- [OAuth 2.0](./examples/authentication/oauth.md)
- [Custom auth headers](./examples/authentication/custom.md)

### File Uploads
- [Single file upload](./examples/file-uploads/single.md)
- [Multiple files](./examples/file-uploads/multiple.md)
- [File with form data](./examples/file-uploads/with-data.md)
- [Base64 encoded](./examples/file-uploads/base64.md)

### JSON APIs
- [POST JSON data](./examples/json-apis/post-json.md)
- [Nested JSON objects](./examples/json-apis/nested.md)
- [JSON arrays](./examples/json-apis/arrays.md)
- [PATCH requests](./examples/json-apis/patch.md)

### Webhooks
- [Stripe webhooks](./examples/webhooks/stripe.md)
- [GitHub webhooks](./examples/webhooks/github.md)
- [Slack webhooks](./examples/webhooks/slack.md)
- [Custom webhooks](./examples/webhooks/custom.md)

## 🔧 Supported Languages

Each example includes conversions for:

- **Python** - requests, urllib, http.client
- **JavaScript** - fetch, axios, XMLHttpRequest
- **PHP** - cURL, Guzzle
- **Go** - net/http
- **Ruby** - net::http
- **Java** - HttpURLConnection, OkHttp
- **C#** - HttpClient, RestSharp
- **Rust** - reqwest
- **Node.js** - node-fetch, axios, request
- **And many more...**

## 🤝 Contributing

We love contributions! If you have a useful cURL example:

1. Fork this repository
2. Add your example following our [template](./TEMPLATE.md)
3. Create a pull request

### Contribution Guidelines

- Include real-world use cases
- Test your code examples
- Follow the existing format
- Add comments for clarity

## 📖 Example Template

Each example should include:

```markdown
# [Example Name]

## Use Case
Brief description of when you'd use this

## cURL Command
```bash
curl [your command here]
```


## 🌟 Popular Examples

1. [Stripe Payment Integration](./examples/popular/stripe-payment.md)
2. [OpenAI API Call](./examples/popular/openai-api.md)
3. [AWS S3 Upload](./examples/popular/aws-s3.md)
4. [Twilio SMS](./examples/popular/twilio-sms.md)
5. [SendGrid Email](./examples/popular/sendgrid.md)

## 🔗 Resources

- [<sup>1</sup>](https://curl-to.com) - Online cURL converter
- [Everything Curl](https://everything.curl.dev/) - The curl book
- [HTTP Status Codes](https://httpstatuses.com/) - HTTP reference

## 📝 License

MIT License - feel free to use these examples in your projects!

---

<p align="center">
  Made with ❤️ for developers who are tired of manual conversions
</p>

<p align="center">
  <a href="https://curl-to.com">Try curl-to.com →</a>
</p>
