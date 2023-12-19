# fem-downloader

Simple, less than 100 LOC script that downloads courses from [frontend masters](https://frontendmasters.com/).

## Disclaimer

Made for educational purposes only, I do not care if you get banned by using this program.

## How to use it

1. Clone the repo

```bash
  $ git clone https://github.com/H4wk507/fem-downloader.git
```

2. Install

```bash
  $ npm install
```

3. Adjust values in `config.js`

```js
const config = {
  FEM_AUTH_MOD: "", // Can be found in browser cookies after logging in (it changes every log in)
  COURSE_URL: "", // Course url
  QUALITY: "2160", // 2160, 1440, 1080, 720, 360 (check which are available for your course before setting)
};
```

4. Run

```bash
  $ node main.js
```

## License

GPLv3
