<!-- PROJECT HEADER -->
<div align="center">
  <a href="https://github.com/Yuugen64/">
    <img src="assets/CrystalCube.png" alt="Logo" width="100" height="100">
  </a>


  <h2 align="center">Readme Template</h2>
  <p align="center">This is a general template in markdown to use in the repo's of your projects for clearer documentation. This document is meant to be starting point for purposeful documentation that is well adapted to the particular project; hopefully this bare minimum can suffice in a pinch. This intro area can be re-purposed for a simple explanation of your project.</p>

</div>


<br>
<br>

<p align="center">Please check the <mark>**Commit Syntax**</mark> section to ensure repo consistency!!</p>
<br>

# Table of Contents
1. [Tools](#tools-required)
2. [Commit Syntax](#commit-syntax)
3. [Example List](#example-numbered-list)
4. [Useful Readme Sections](#useful-readme-sections)
5. [Markdown Syntax](#markdown-syntax)

<br>
<br>

# Tools Required:
***(REPLACE)*** This area shouild always include the tools that you need other devs/users to have on their system in order to correctly build/install/use your software.
<br>
<br>

# Commit Syntax:
Please try to maintain the established commit syntax - please do your commits in the following style so that the repo is easy to read and understandable for newcomers/dev's (especially in times of crunch).

General Syntax:
```
git commit -m "[ general topic:: specific change ] - explanation of what you did. Explanation of what needs work as a result (optional)."
```
  
As an example:
```
git commit -m "[ tablet view:: button alignment ] - I added the second button to the tablet card. Need to fix the desktop button alignment now."
```  
<br>
<br>

# Example Numbered List:
1. This document is for reference.
2. Markdown is really cool!
3. Try to provide answers to any quirks, issues etc to your program so other people who aren't as familiar (see also "future you") can reference this document!
<br>
<br>

# Useful Readme Sections:
1. Branches && their purpose.
2. Project Setup.
3. Using the software.
4. Dependencies.
5. Platform support.
6. Explanation of the project directory.
7. Commit Syntax.
8. General conventions; naming, styling, etc.
<br>
<br>

# Markdown Syntax:
I initially had some trouble with getting Markdown to work as expected. Thus I am recording here the syntax that I got to function in both Github AND Bitbucket. It's important to note that there are actually multiple implementations of markdown rendering and thus it can be tedious to build a document that renders as expected everywhere (especially when you want control over format as I do).
<br>
<br>

1. If using [Visual Studio Code](https://code.visualstudio.com/) you can actually "render" the markdown to preview it within the IDE. 

Either use the "chord" to open a split view previewer:
```
Ctrl + K --> V
```
Or use the shortcut to preview a single time:
```
Ctrl + SHift + V
```
<br>
<br>

2. Use double 'break' tags to add vertical spacing between elements; this helps with readability a LOT since markdown is not really rich text formatting per se, but rather stylized code. Keeping things locgically separated goes a long way in reducing headaches and anxiety.
3. A single back-tick around test will color it as a command.
4. Triple 'back-ticks' allow for CLI outputs as seen above.
5. Single asterisks (1*) will make text *italic*.
6. Double asterisks (2**) will make text **bold**.
7. Triple asterisks (3***) will make things ***italic and bold***.
8. Using 'mark' tags around text will <mark>highlight</mark> it (useful for critical things).
9. Indentations DO affect how text is output.
- Using a single hyphen will create a bullet point.
