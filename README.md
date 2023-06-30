<img src="./images/rodneylab-github-sveltekit-session-cookies.png" alt="Rodney Lab sveltekit-session-cookies Github banner">

<p align="center">
  <a aria-label="Open Rodney Lab site" href="https://rodneylab.com" rel="nofollow noopener noreferrer">
    <img alt="Rodney Lab logo" src="https://rodneylab.com/assets/icon.png" width="60" />
  </a>
</p>
<h1 align="center">
  SvelteKit Session Cookies
</h1>

> **Warning**
> 🚧 **This repo uses a deprecated SvelteKit routing API. See [updated example using current SvelteKit routing API](https://github.com/rodneylab/svelte-login-form). See you there!** 👋🏽

# sveltekit-session-cookies

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/rodneylab/sveltekit-session-cookies)

Demo code for handling temporarily caching user input form data using Session Storage to improve user experience in SvelteKit. The code accompanies the <a aria-label="Open Rodney Lab blog post on using Session cookies with Svelte Kit" href="https://rodneylab.com/sveltekit-session-cookies/">video on using the SvelteKit session store with HttpOnly cookies</a>. If you have any questions, please drop a comment at the bottom of that page.

## Building and previewing the site

If you're seeing this, you've probably already done this step. Congrats!

```bash
git clone https://github.com/rodneylab/sveltekit-session-cookies.git
cd sveltekit-session-cookies
pnpm install # or npm install
pnpm run dev
```

## Building

```bash
pnpm run build
```

> You can preview the built app with `pnpm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
