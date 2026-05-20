# Info

This presentation and accompanying expose for a PhD project was designed for my application to be accepted into the IMPRS-trust (International Max Planck Research School on Trustworthy Computing).

After my presentation on the 8th of January 2026 and subsequent qualification interviews, I was officially accepted into the program on the 11th of March 2026.

## Abstract

When learning to write code, either overall or in a previously unknown programming language, many developers might get tripped up by the colors of text and instructions in their IDE.
Fresh programmers might express typical questions like “Why are the words colored all of a sudden” or “If the compiler knows that there is a semicolon missing in line 12, why do I have to place it?”.
But even coding veterans might stumble upon the occasional odd “Why would this not work?” and get saved from hours of head-wrenching debugging, by the fact that the one variable is colored differently than the rest.
A static code analysis tool just alerted them of the fact, that this identifier seems to be a reserved keyword in the language they were just tasked to work in.
With a brief introduction to the programming work a computational physicist might get confronted with, we want to explore possible uses for code analysis tooling and methods to improve the development of machine learning architectures or speed up the evaluation of expensive computational tasks.
We also want to pose the question: “If there is syntax checking and automatic refactoring for code, why not for doing your algebraic derivations?”.
That is what a computer algebra system is for! And it basically does the same: code analysis, just on your mathematical formulas.
This train of thought motivates our research proposal called Timing Analyzable Rust Compilation, that suggests a toolchain targeted at improving the timing analyzability of code for embedded systems.
By providing feedback about timing analyzability already during the compilation step, we plan to streamline the code for downstream tools while it is still in the high-level language.
All while generating annotation symbols and meta information for external calculations of the Worst Case Execution Time (WCET) or ensuring your functions are secure against timing-based side-channel attacks.

## How to present

Presentation tool [pympress](https://github.com/Cimbali/pympress).

```cmd
pympress ApplicationPresentation_Animations+Notes.pdf
```

The outline/extra slides section-titles are functional links and should be used to navigate the presentation, most of all to chose the correct graph from the extra-slides section.
While presenting the links on the main display and on the `current slide` view are clickable.
