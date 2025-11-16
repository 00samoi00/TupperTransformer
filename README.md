# TupperTransformer (A Novel Image Processing Algorithm)

<p align="center">
  <a href="License"><img alt="GitHub" src="https://img.shields.io/github/license/Prathameshnium/TupperTransformer"></a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Prathameshnium/TupperTransformer">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Prathameshnium/TupperTransformer">
</p>

> **Note:** This project is in a very early, experimental stage.

Welcome to my repository. This project is my exploration of a new image processing technique based on my 2018 preprint, "Transformation of the pixels in Tupper's self-referential formula."

This algorithm operates directly on the high-precision integer (k-value) used to generate Tupper's self-referential bitmaps, rather than manipulating the pixels after they are rendered. This repository contains the interactive demo that serves as the proof-of-concept and implementation of that research.

## Live Demonstration

Experience the algorithm in action with the new and improved interactive demo. The interface has been completely redesigned to be more intuitive and mobile-friendly.

**[Click here to open the live demo](https://prathameshnium.github.io/TupperTransformer/)**

## About the New Demo

The interactive demo brings these concepts to life with a simple, unified interface designed for both desktop and mobile use.

The layout is organized into two main columns on larger screens:

### Left Column (The Canvas & Workspace)
This is your main area for interaction.
- **The Plot:** The $106 \times 17$ grid where the formula is rendered. **You can draw freely on the plot** at any time by clicking and dragging to create your own patterns.
- **Transform Controls:** A compact control box is located directly below the plot, allowing you to move the entire pattern up, down, left, right, or diagonally.
- **K-Value:** The high-precision integer `k` is always visible below the controls. It updates in real-time as you draw or transform the image. You can also paste a `k` value directly into this box, and the plot will update automatically.

### Right Column (Actions & Examples)
All actions are organized into a simple, two-part accordion panel.
- **1. Demos & Examples:**
    - **Load Patterns:** Instantly load the classic "Tupper's" self-referential plot or a "UFO" pattern.
    - **Animation Demo:** Watch the "Top-Left UFO" animation from the paper.
    - **Interactive Tetris:** This special demo loads a Tetris scene. When active, the standard transform controls below the canvas are **replaced with special "Piece" controls** that only move the falling L-piece, demonstrating the concept of transforming individual pixel groups.
    - **Library of Babel:** See the formula generate random patterns continuously.
- **2. Draw Your Own:**
    - **Enable/Disable Draw Mode:** Toggle the ability to draw on the canvas (it is on by default).
- **Clear Canvas:** A prominent red button is always visible at the top of this column to let you easily start over.

### Other Features
- **Clickable Formula:** Click the main Tupper's formula at the top of the page to instantly load the self-referential plot.

## About the Paper (Algorithm Summary)

My research paper is based on Tupper's self-referential formula, which is popular due to its property of plotting itself. But that is not the only amazing thing about this formula: it doesn't only plot itself, but it plots every possible combination of the $106 \times 17$ pixels.

A copy of the paper is also available in this repository in the [`paper`](./paper) directory.

I.e. it plots all possible combinations of these 1802 pixels, and the value of k is used for sliding over the y-axis.

My research idea started with a question:

> "If there is some graphical formation at a particular value of k, then what can be done to change the graphical formation or to change its position?"

This question leads to my research, which has two main ideas:

1.  How to change any graphical formation into another graphical formation by applying some kind of operation to the value of the k.

2.  How this different graphical formation can be used as a frame to create a film or motion picture.

### What can my research do?

My research can do the following:

-   Represent all possible graphical formations (within 1802 pixels) and all their possible variations.
-   Create a formula for any film or motion picture.

In short, my research represents a mathematical form of the "Library of Babel" but for film and motion pictures.

## Citation

If you use this work, please cite the original preprint.

### Formatted Citation (APA Style)

> Deshmukh, P. (2018). *Transformation of the pixels in Tupper's self-referential formula*. Figshare. https://doi.org/10.6084/m9.figshare.6373046

### BibTeX Citation (Recommended)

```bibtex
@article{Deshmukh2018,
  author  = "P Deshmukh",
  title   = "{Transformation of the pixels in tupper's self-referential formula}",
  year    = "2018",
  month   = "6",
  url     = "https://figshare.com/articles/preprint/Transformation_of_pixels_pdf/6373046",
  doi     = "10.6084/m9.figshare.6373046.v2"
}
```

For a full list of publication details, indexing, and archive links, please see the CITATION.md file in this repository.

## History & Related Materials

### History

-   **2018-06-08** - First online date, Posted date

### Related Materials

-   [Tupper's Self-Referential Formula Explained](https://www.petervis.com/mathematics/tuppers_self-referential_formula/tuppers_self-referential_formula.html)
-   [Tupper's Formula Tools (defunct)](http://tuppers-formula.tk)
-   [Numberphile: The 'Everything' Formula](https://youtu.be/_s5RFgd59ao)
-   [Tupper's Original Paper (Self-Referential Formula)](http://campus.lakeforest.edu/trevino/Tupper_Paper.pdf)

## Technologies Used

The interactive demo is built with standard web technologies:

-   **HTML5:** For the structure of the web page.
-   **CSS3:** For styling the user interface.
-   **JavaScript (ES6+):** For the core logic of the TupperTransformer algorithm and user interactions.
-   **BigInt:** Natively handled in modern JavaScript for the high-precision integer arithmetic required for the k-value.

## Project Structure

The repository is organized as follows:

```
.
├── paper/
├── CITATION.md
├── index.html
├── License
├── README.md
```

-   `paper/`: Contains the original 2018 preprint that this project is based on.
-   `index.html`: The core file for the interactive web demo, containing all HTML, CSS, and JavaScript.
-   `CITATION.md`: Provides detailed citation information for academic use.
-   `License`: The MIT license for the project.
-   `README.md`: This documentation file.

## Future Work

I will be creating some more advanced features as I get free time. This includes exploring more complex transformations and further optimizing the rendering process.

## Contributing

I am open to suggestions and collaborations. If you have any ideas or would like to discuss implementing this research, please feel free to open an issue to start a conversation.

## License

This project is licensed under the MIT License - see the [LICENSE](License) file for details.

## Categories & Keywords

*(From Figshare)*

### Categories

-   Theory of computation 
-   Applied computing 
-   Image processing
-   Applied mathematics 

### Keywords

-   tuppers-formula
-   tuppers-self-referential-formula
-   image-processing
-   algorithm
-   math
-   theory-of-computation
-   applied-computing
-   applied-mathematics
-   computation-theory
-   applied-computer-science
-   javascript
-   interactive-demo
-   preprint
-   bigint