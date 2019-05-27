This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

I will use this project to reference how to:
* set up ESLint to use the Prettier rules and use the Prettier formatter, 
* set up ESLint to be able to parse TypeScript and set up TypeScript rules
* on a React project that was started from create-react-app

For the benefit of my own sanity. 

Please feel free to point out if something is out of place in the settings. I know this is not the best config setup, but it is one that mostly works. Also, this is a learning opportunity for me as well. 

Some resources: 
* ESLint in Create-React-App: https://facebook.github.io/create-react-app/docs/setting-up-your-editor#displaying-lint-output-in-the-editor
* TypeScript in ESLint: https://github.com/typescript-eslint/typescript-eslint#how-do-i-configure-my-project-to-use-typescript-eslint
* Prettier in ESLint: https://prettier.io/docs/en/integrating-with-linters.html#use-eslint-to-run-prettier

Some notes: 
* Some VSCode settings are set up to override some User rules that allow me to use Prettier globally on my machine.
* The ESLint output on VScode says `No ESLint configuration (e.g .eslintrc) found for file: c:\Users\Sammy-Surface\Development\Learning\WorkspaceReactTSSetup\workspace-setup\src\App.tsx File will not be validated. Alternatively you can disable ESLint by executing the 'Disable ESLint' command.`. I think it is because ESLint is running Prettier for `tsx` files, but I am not 100% sure.
* Only the ESLint VSCode plugin is recommended.
