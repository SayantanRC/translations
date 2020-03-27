# Translations
Repo of translations

For locale codes, check here: https://stackoverflow.com/questions/7973023/what-is-the-list-of-supported-languages-locales-on-android

## Steps
1. Fork this repo.
2. If you have already forked and want to update a translation, always update your repo. Check this answer: https://stackoverflow.com/questions/20984802/how-can-i-keep-my-fork-in-sync-without-adding-a-separate-remote/21131381#21131381
3. For each app, `strings_nn.xml` is the default english strings. The `nn` is a number to reflect the build number of the app. The `nn` value helps to distinguish if translations are updated.
4. To submit a new translation, make a new strings file with locale code, followed by the `nn` value. For example, if you are making turkish translation make a file `strings-tr_nn.xml` and put your translations in that file.
5. The original `strings_nn.xml` and your `strings-xx_nn.xml` must be under the same directory.
6. <b>Important</b>: In the main strings file, a string is `translators_list` is present. Please help yourself and add your name in it to show that you contributed. :)
7. After translating, submit a pull request.
	<b>Important</b>: Please check other pull requests before open yours in order to minimize asynchronous translations

Thank you.
