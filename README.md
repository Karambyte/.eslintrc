# .eslintrc
This is our configuration file for [ESLint](http://eslint.org), the pluggable JS linter. It's based on [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb), and a bit of a moveable feast for now until we get settled. We use it as a reference for when we're setting up new projects and machines, but by all means feel free to use in your own projects or make suggestions!

## How do I use this?
Whilst we use ESLint for automatic hinting inside WebStorm, our IDE of choice, it can be used on the command line: have a look at their [User Guide](http://eslint.org/docs/user-guide/configuring) for more details. If you're using WebStorm like us, have a look at the JetBrains [manpage](https://www.jetbrains.com/help/webstorm/2016.1/eslint.html), which explains how it all works inside WebStorm. Once you're comfortable, perform the following steps to install this `.eslintrc` for your project:  

1. Require the base ESLint library (`npm install --save eslint`)
2. Install everything that Airbnb's [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) requires (`npm install --save-dev eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y eslint`) 
3. Create a new file called .eslintrc in the base of your project using your favourite text editor (not getting into a holy war here): `vi .eslintrc`
4. Copy & paste the contents of our `.eslintrc` into _your_ `.eslintrc.`, and watch the magic unfold.


## Questions?
If you have questions on ESLint, we're _probably_ not the best people to ask, but we're more than happy to see how we can help (or put you in touch with someone who's better placed to solve your issue): send an email to [hello@karambyte.com](hello@karambyte.com). Alternatively, if you have an issue or want to file an improvement, head over to the Issues page.
