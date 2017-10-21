# Thesis template for Tel-Aviv University
A thesis latex formatted according the requirement in the Tel-Aviv University at the faculty of engineering.

This project is based on a template by **Alex Liberzon** (@alexlib) that can be found in [here](https://github.com/alexlib/tau_thesis_lyx_template).
Compared to Liberzon's original template, this version contains enhancements and new features including:

1. Adherence to the engineering department updated requirements.
2. A facelift for the title page
3. Nomenclature support
4. Beautiful dedication page
4. Arabic support
5. Definition and Theorem style
6. First and second supervisor
7. With minimal changes it can be used for as Ph.D dissertation template
8. Bare Latex - LyX free.

We have made an effort to include an example for every possible type of element needed in an engineerig thesis (table, figure, nomenclatures, numbering, theorem, definition, etc).

**The project files:**
======

1. **tauthesis.sty** - the style file.
2. **Thesis-main.tex** - the main template file.
2. **acknowledge.tex** - the acknowledge part.
3. **abstract.tex** - the abstract part.
4. **introduction** - the introduction section (another chapter).
4. **chapter.tex** - a chapter template.
5. **conclusions.tex** - another chapter.
6. **references.tex** - the bibliography source file.
7. **hebrew_part.docx** - an MS Word document containing the hebrew title and abstract parts.
8. **hebrew_part.pdf** - the "hebrew_part.docx" exported to pdf.
7. **figures** - the directory which should contain your figures.

**Usage notes:**
======

1. The "main" file is the **Thesis-main.tex**, thus, to render a pdf, run **Thesis-main.tex**.
2. Your personal information, date, supervisor can be configured in the main file.
3. The main file also defines the structure, order and numbering of the thesis title pages.
4. The main file define the thesis content and order - starting from "\begin{document}"
5. The main file defines all needed keywords - don't hesitate to remove unneeded definitions.
6. The main file also include the dedication page.
6. Every chapter should be written in a different tex file and added to the main file.
7. Bibliography should be added in **references.bib**.
8. Do not edit the file **tauthesis** unless you really know what you're doing.
9. It is recommended that every chapter text file to contain its own nomenclatures, even if it is used in other chapters.
10. It is recommended that every chapter/section/subsection/figure/table will have it's own label according to the convention that you can find in the different files in the project.
10. Before start using this template it is recommended to go over all files in the project and try to make sense of the structure and also to see how to create different types of elements.
11. It is recommended to use png or pdf format for your figures.
12. To update the hebrew part, edit **hebrew_part.docx** file and export to pdf.

**General Notes:**
======

1. For help you can contact the author at: kourgeorge/at/gmail.com.
2. You can use, redistribute and do whatever with this project, however, the author takes no responsibility whatever usage of this project.
3. If you start another project based on this project, it would be nice to mention/link to this project.
4. You are very welcome to contribute to this project.
