# jsm_banking

JavaScript Mastery のバンキングアプリのチュートリアルを進めるためのリポジトリです（作り始めの段階）。

A repository for following the [JavaScript Mastery](https://www.youtube.com/@javascriptmastery) tutorial that builds a fintech banking app, Horizon ([tutorial video](https://youtu.be/PuOVqP_cjkE), [original repository](https://github.com/adrianhajdin/banking)).

## Status

Early stage. So far the repository has:

- A Next.js 14 (App Router) project with TypeScript and Tailwind CSS
- shadcn/ui set up (`components.json`, `components/ui/button.tsx`)
- The tutorial's icon set in `public/icons/`
- Shared folders for later steps: `constants/`, `lib/`, `types/`

`app/page.tsx` is still the default Next.js start page. The banking screens, sign-in and bank connections from the tutorial are not built yet.

## Usage

```sh
git clone https://github.com/Sol-momma/jsm_banking.git
cd jsm_banking
npm install
npm run dev     # http://localhost:3000
```

Other scripts: `npm run build`, `npm start`, `npm run lint`.

## Tech stack

- Next.js 14, React 18, TypeScript
- Tailwind CSS, shadcn/ui (Radix UI), lucide-react

## License

No license file. The app design and the icon assets come from the JavaScript Mastery tutorial.
