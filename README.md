## vercel/turbo#8583

Turbo LSP is unable to resolve the value of `turbo.path` unless an absolute path is provided.

See https://github.com/vercel/turbo/issues/8583 for more details.

## Steps to reproduce

1. Clone this repo
2. Install all the dependencies by running `pnpm install`
3. Open the repo using VS Code
4. You should see the error showing that the `turbo not found` error
5. Done

---
