# A library of variable fonts optimized and ready to use
--
All the variable fonts found in Google Fonts as of today (22 March 2020) + Montserrat

- optimized for Latin/European languages (latin subset with [glyphhanger](https://github.com/filamentgroup/glyphhanger))

## Example files

[Netlify demo here](https://variable-fonts.netlify.com/)

In the example folder, you'll find a basic example to show how to use variable fonts the easiest way.

Here are some key points:

- It doesn't work on IE and other old browsers that don't support CSS Variables
- This example uses variable fonts with 2 different files for normal and italic
- If you use a variable font with no italic style file, you'll have a fake italic
- To reduce the number of static fonts files loaded, we rely on fake italic when needed
- If you want to use Inter variable font, it's another story because Slant is harder to setup than Italic 😨

Due to some inconsistencies with how browsers handle variable font files that contain both italic and upright variants, I recommend starting with the kind of "classic" setup I use in my example.

It's also easier to setup and the `font-style: italic` css property works as expected out of the box.

## Support

If you want to thank me or support my work, you can [buy me a coffee](https://www.buymeacoffee.com/marcfilleul) 😉
