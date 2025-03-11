# Resume Template

This is a resume template written in LaTeX, based on the work of Andrew Li. It has been heavily modified from the original, to make it more convenient and to add additional features, such as the creation of multilingual CVs and the introduction of a more involved build system. To build the project you need to have a `texlive` distribution and `latexmk` installed.

## Multilingual 
To add a new language you need to add a new makefile goal, a resume-xx.tex file and the relevant macros in the main tex file. This way of working ensures that updates are more likely to propagate to all possible languages and save you any headaches later.

There are also a number of different header styles, as the original style was using a lot of whitespace.

### UTF-8 support

Based on some user feedback I have made the template able to accept UTF-8 text by switching the compilation to LuaLaTeX. As I don't feel like I am proficient enough in Chinese or Japanese to typeset my resume in it, I have only made a stub to demonstrate that it works. Check out the `resume-macros.tex` file for the `\jp` macro and see it in use in the main `resume.tex` file. Note that you might have to enable the correct fonts for your language still. 

## Preview

![resume](resume.png)

## Recommendations

Andrew Li says: "Please do not use Overleaf". I agree. Also, as of a few days ago (time of writing: 2024-01-16) they made their editor worse. Yet again.

## License

MIT

## Special Thanks

Anicca, for lots of feedback on the content. 😘
