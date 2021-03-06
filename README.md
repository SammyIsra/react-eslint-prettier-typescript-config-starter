# Sammy's Reference on how to use ESLint, Prettier, and TypeScript in React (from create-react-app)

I will use this project to reference how to:
* set up ESLint to use the Prettier rules and use the Prettier formatter, 
* set up ESLint to be able to parse TypeScript and set up TypeScript rules
* on a React project that was started from create-react-app

This project is made for the benefit of my own sanity 😭 


Please feel free to point out if something is out of place in the settings. I know this is not the best config setup, but it is one that mostly works. 

Also, this is a learning opportunity for me as well, so input is appreciated. 

### 📚 Some resources: ###
* ESLint in Create-React-App: https://facebook.github.io/create-react-app/docs/setting-up-your-editor#displaying-lint-output-in-the-editor
* TypeScript in ESLint: https://github.com/typescript-eslint/typescript-eslint#how-do-i-configure-my-project-to-use-typescript-eslint
* Prettier in ESLint: https://prettier.io/docs/en/integrating-with-linters.html#use-eslint-to-run-prettier

### 📝 Some notes: ###
* Some VSCode workspace settings (inside of `\.vscode`) are set up to override some User VSCode settings that allow me to use Prettier globally on my machine.
* The ESLint output on VScode says `No ESLint configuration (e.g .eslintrc) found for file: c:\Users\Sammy-Surface\Development\Learning\WorkspaceReactTSSetup\workspace-setup\src\App.tsx File will not be validated. Alternatively you can disable ESLint by executing the 'Disable ESLint' command.`. I think it is because ESLint is running Prettier for `tsx` files, but I am not 100% sure. Also, VSCode says that ESLint was not able to format a `.tsx` file when I save but... It *is* formatted, and the formatting on save is disabled when I disable the ESLint plugin so... idk 🤷‍♂️🤷‍♂️🤷‍♂️
* Only the ESLint VSCode plugin is recommended, since that's what VSCode uses to format files on save.
* While the entire project is on the repo, the more important files I want to keep track of in this repo are the settings and config files, like
  * `.eslintrc.json`
  * `package.json`
  * What's inside the `\.vscode` folder

### 😱 Some opinions: ###
* For someone that doesn't do config setups often, this dance was kind of complicated, which is the entire reason why I set up this repo.
* **TypeScript** is here because I like TypeScript and use it whenever I can.
* **ESLint** is here because, while I use the Prettier default rules and formatter, I have the need to add custom rules.
* **Prettier** is here because I enjoy the default Prettier experience
* **`1react-a11y`** is here because it enforces good accessibility practice
* **`eslint-plugin-react-hooks`** is here because that is THE ENTIRE REASON THAT SET ME ON THIS QUEST. 
