Deedy x DFOO - Resume
=========================

A **one-page**, **two asymmetric column** resume template in **XeTeX** that caters particularly to an **undergraduate Computer Science** student.
As of **v1.2**, there is an option to choose from two templates:

1. **MacFonts** - uses fonts native to OSX - *Helvetica*, *Helvetica Neue* (and it's Light and Ultralight versions) and the CJK fonts *Heiti SC*, and *Heiti TC*. The EULA of these fonts prevents distribution on Open Source.
2. **OpenFonts** - uses free, open-source fonts that resemble the above - *Lato* (and its various variants) and *Raleway*.

It is licensed under the Apache License 2.0.

## Motivation

Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter)  and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates. 

This template attempts to **look clean**, highlight **details**, be a **single (or more) page**, and allow useful **LaTeX templating**.

## Preview

### OpenFonts
![alt tag](https://user-images.githubusercontent.com/18390092/90956906-f2bb2100-e4cd-11ea-976b-0cd32ad1cee3.jpg =700x876)
![alt tag](https://user-images.githubusercontent.com/18390092/90956905-f058c700-e4cd-11ea-89d0-eef20fe7417e.jpg =700x876)

### MacFonts
![alt tag](https://raw.githubusercontent.com/deedydas/Deedy-Resume/master/MacFonts/sample-image.png)

## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.
2. Uses fonts that are usually only available to **Mac** users such as Helvetica Neue Light.

## Availability

1. MacFonts version - [as an online preview](http://debarghyadas.com/resume/debarghya-das-resume.pdf) and [as a direct download](https://github.com/deedydas/Deedy-Resume/raw/master/MacFonts/deedy_resume.pdf)
2. OpenFonts version - [as a direct download](https://github.com/deedydas/Deedy-Resume/raw/master/OpenFonts/deedy_resume-openfont.pdf)
3. **Overleaf**.com (formerly **WriteLatex**.com) (v1 fonts/colors changed) - [compilable online](https://www.writelatex.com/templates/deedy-resume/sqdbztjjghvz#.U2H9Kq1dV18)
4. **ShareLatex**.com (v1 fonts changes) - [compilable online](https://www.sharelatex.com/templates/cv-or-resume/deedy-resume)

## Changelog

### v.1.3 only OpenFont version (DFoo):
 0. Forked from original Deedy CV
 1. Fixed overflow issue from previous version by using paracol package (idea from CVs made by LianTze Lim in overleaf)
 2. Adjusted column widths to suit my preference
 3. Used tabularx package which makes it easier to set relative widths for tables
 4. Copied formatting .cls file from "Deedy Resume Reversed" by Zachary Taylor in overleaf
 
### v1.2
 1. Added publications in place of societies.
 2. Collapsed a portion of education.
 3. Fixed a bug with alignment of overflowing long last updated dates on the top right. 

### v1.1
 1. Fixed several compilation bugs with \renewcommand
 2. Got Open-source fonts (Windows/Linux support)
 3. Added Last Updated
 4. Moved Title styling into .sty
 5. Commented .sty file.

## TODO
1. Merge OpenFont and MacFonts as a single sty with options.
2. Figure out a smoother way for the document to flow onto the next page.
3. Add styling information for a "Projects/Hacks" section.
4. Add location/address information
5. Fix the hacky 'References' omission outside the .cls file in the MacFonts version.
6. Add various styling and section options and allow for multiple pages smoothly.

## Known Issues:
1. Hacky space on the first bullet point on the second column.
2. Hacky redefinition of \refname to omit 'References' text for publications in the MacFonts version.

## License
    Copyright 2014 Debarghya Das

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
