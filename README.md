# Adobe and Typesetting via AI

![Page from the Doves Bible](/images/Doves_Press_Bible.jpg)

Typesetting is a lovely craft that sits at the intersection of art and utility. Text ought to be beautiful but it _must_ be readable and that necessity constrains the art of the typesetter. From the first copied manuscripts, through Gutenberg, and into the digital age, craftsmen have developed new ways to make type more beautiful, more functional, and easier to set. Could AI have a role in continuing the evolution of the craft? 

Adobe is one of the leaders in the field of digital typesetting and design. I will be considering how Adobe might use AI to change the way designers create in the future. 

## Overview and Origin

### Justification and hyphenation in the pre-digital age

![Page from the Book of Kells](/images/blog-book-of-kells.png)

Micah Rich and Thomas Jockin have written [a wonderful article for Google Fonts](https://fonts.google.com/knowledge/history_of_type/justification_hyphenation) that describes the history of typesetting. I recommend that anyone even slightly interested in typesetting go and check out the whole thing but I’ll be quoting a couple sections here. 

> A block of text is justified if all its lines are exactly the same length, producing a clean edge on the left and the right...Hyphenation and justification tend to go hand in hand. While text can be justified without resorting to hyphenation...effective justification generally requires hyphenation.

In the Middle Ages, even before the advent of print, a solid rectangular block of justified text became the standard:

> Before starting to write, scribes carefully ruled out a rectangular text area on parchment with a sharp tool, lead, or ink. They justified as they wrote, fitting text to the line by hyphenating, abbreviating, overlapping letters, using ligatures, and making slight alterations to the widths of letters. Scribes might allow a letter or two to protrude into the right margin, but on the whole, they went to great lengths to preserve the solid rectangle of the text area, sometimes filling the empty space at the end of a final line with decoration, or even with arbitrary letters. 

When Gutenberg invented moveable type, he transferred many of the same techniques used by the scribes to his new system. As subsequent innovators continued to build on the foundation Gutenberg laid, they streamlined away a few of his techniques but the basic goal remained the same: a justified rectangular block of text.

The Linotype machine and other ‘hot type’ machines streamlined the process even further and made typesetting easier albeit at the expense of some of the beauty of the text. 

### Digital typesetting

In the 1970s, digital typography began to replace the Linotype and Monotype machines. The history is long and varied but the remaining gold-standard typesetting engines are Tex, an open-source algorithm developed by Donald Knuth, and Adobe InDesign’s proprietary typesetting engine. 

> Knuth’s system was based on three essential concepts: boxes, glue, and penalties. A “box” is something to be typeset, whether a single character or something more complex like a mathematical formula; the important thing about a box is its width. A word is represented by a series of boxes. “Glue” is the blank space between boxes; glue is elastic, with an ideal width, and a degree of “stretchability” or “shrinkability.” A “penalty” is the “aesthetic cost” of breaking a line in a particular place. Existing typesetting systems made line-breaking decisions on a line-by-line basis; they couldn't look forward or back to see the effect of a line break on the rest of the paragraph. TeX determines optimum break points by considering the paragraph as a whole.

Adobe’s system is similar to Knuth’s and “considers a network of breakpoints for an entire paragraph... evaluating them, and assigning a weighted penalty to them.” It also allows designers to tweak “micro-typographic” features such as “letter-spacing, glyph scaling, and optical margins” to achieve the optimal line justification.  

### Adobe and Type

Adobe was incorporated the year I was born (1982) by founders John Warnock and Charles Geschke. While it is now most well-known for products like Adobe Photoshop and Adobe Illustrator—applications built for visual artists and designers—it started with a single product: Adobe PostScript, which became the industry standard for computer printing. Adobe’s second product was a set of digital fonts and Adobe’s type library now contains over 20,000 fonts. In 1999, Adobe released InDesign which slowly ate into competitor, QuarkXPress’s, market share and ultimately beat it out to become the leading professional desktop publishing software package. (At least, this seems to be the case—finding data on desktop publishing as a separate industry distinct from office productivity, web publishing, and graphic design is a little tricky. Nevertheless, this site has Adobe Indesign at 41% of the market with its nearest competitor (Microsoft Publisher) at 17% ([source](https://enlyft.com/tech/desktop-publishing)).

### Adobe and AI

![Adobe AI infor](/images/adobe_ai.png)

Adobe, like many tech companies, is attempting to retool and make AI a significant part of their tech stack. The Adobe About page has a large section on AI immediately below the basic description of what the company is and what it does. So far, Adobe’s focus has been on three areas: 

- Adobe Firefly which uses text prompts to create images
- Adobe Sensei GenAI which is built into photoshop to create image backgrounds and extend images and patterns
- Adobe Sensei for Experience Cloud which uses AI to find patterns in data

### Impacts of AI on Adobe so far

Adobe achieved 13% growth in FY’23. They have not released public metrics on how much of that growth they believe is attributable to AI but they did mention that Adobe Firefly has had 4.5 billion generations since its release. Adobe has dominated the professional space and so one of its focuses is to try to increase its footprint in the hobbyist and amateur digital creation market and user-friendly AI tools are a big part of that push. 

Adobe announced an internal initiative to fund a number of small internal “start-ups” that would work fast and lean to try to create new AI products. Any employee can pitch an idea to senior leadership and be funded as part of one of these internal “start-ups.” Adobe is displaying a strong commitment to staying ahead of these technologies. 

### The current state of AI typesetting

While Adobe’s current typesetting system is very good, it is certainly not perfect. This is also true of its open-source competitor, Tex. Both Tex and InDesign will “break” under different circumstances. LaTeX will allow words to overflow the margin and produce an error if it can’t find an optimal way to set the text. InDesign will sometimes produce text with very strange spacing and it also is prone to widows (breaking a page right before the last line of a paragraph so that it ends up by itself at the top of the page). if its algorithm fails.

![LaTeX typesetting error](/images/LaTeX_typesetting_error.png) 

However, neither Adobe nor the Tex open-source community has explored the possibility of using AI to typeset large blocks of text. As far as I can tell, no one has. There are a few proof-of-concept explorations in that direction, but no solid commercial applications have arrived yet. 

For example, [this article](https://www.fastcompany.com/90892069/best-ai-tools-creativity) describes how AI can set text in an image and make it look like the type is made of various materials or is integrated into the image. [This website](https://www.calligrapher.ai) allows users to convert text to realistic handwriting. However, as best I can tell, AI has not been utilized for typesetting a traditional book. This may be because the current set of tools are good enough despite their flaws. But they’re only good enough for talented designers who can harness the power of the tools but also deal with their complexity and steep learning curves. Adobe has been trying to tap more and more into the casual designer market. I believe this is where the future of AI typesetting lies. 

## Recommendations

![Page from the Arion Press Moby Dick](/images/arion_press_moby_dick.jpg)

If I were to pitch an “internal start-up” idea to Adobe, I would start with the following: Indie book authors publish anywhere from 2.3 to 3 million books every year (see [this site](https://ideas.bkconnection.com/10-awful-truths-about-publishing)). For many of these authors, using a tool like InDesign or paying someone to do it for them is unrealistic. These authors would benefit from a solution where they could feed their text to an application and say, “create a beautifully typeset book that looks fun and friendly” or “create a beautifully typeset book that looks elegant and austere” and have the AI do all the work. 

I would propose training an AI on the best work of small private presses from the last one hundred years—presses like the Officina Bodoni or the Arion Press—which have produced the most beautifully hand-set books of all time, and creating a simple, easy-to-use application for indie authors to create gorgeous books with very little effort. 

Some other recommendations I’d make would be trying to see if an AI-trained model could produce computationally cheap methods of justifying text for use in the web and on eBook readers. I would also suggest using AI to simplify the creation of digital typefaces from older physical faces. Finally, I’d recommend using AI to reproduce Benton’s optical scaling techniques for typefaces allowing for faces that look better at different sizes (see [this article](https://fonts.google.com/knowledge/history_of_type/the_tight_not_touching_style)).

To conclude, while typesetting seems like a mature technology in a mature market, I believe that AI has the potential to grow the market and bring excellent typesetting to many new customers. 

## Resources consulted

- [Google Fonts](https://fonts.google.com/knowledge/history_of_type/justification_hyphenation)
- [Calligrapher.ai](https://www.calligrapher.ai/)
- [Adobe.com](https://www.adobe.com)
- [Desktop publishing (Wikipedia)](https://en.wikipedia.org/wiki/Desktop_publishing)
- [Typography (Wikipedia](https://en.wikipedia.org/wiki/Typography)
- [LaTex Project](https://www.latex-project.org/about/)
