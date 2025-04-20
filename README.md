ForeverUnfinishedArtworxEngine- AWeb Interface for Generative art creation using Layers

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Development-orange)](https://shields.io/)
![GitHub Repo stars](https://img.shields.io/github/stars/Foreverunfinishedartworx/art_engine?style=social)

## Overview

FUAXArt_engine is a user-friendly web application that provides an intuitive interface for the powerful  Art Engine](https://github.com-lab/art-engine). This platform empowers users of all technical levels to easily generate unique, multi-layered digital artworks directly through their web browser.

By simplifying the complexities of Node.js and command-line interactions, FUAXArt_engine allows artists, collectors, and enthusiasts to effortlessly create custom generative art for NFTs, collectibles, or any other creative purpose, all within a familiar web environment. Users can upload their art layers, configure generation parameters, preview their creations in real-time, and download the generated assets and metadata.

## Features

* **Intuitive Layer Management:**
    * Option to upload multiple folders containing distinct layers.
    * Alternative option to upload individual layers into pre-defined category folders.
    * Clear visual feedback on uploaded layers.
* **Live Preview:** A dynamic preview window that updates in near real-time as layers are uploaded and configurations are adjusted, providing immediate visual feedback on the potential artwork.
* **Comprehensive Configuration:** User-friendly input fields for essential Art Engine parameters, including:
    * Payment wallet address and royalty share.
    * Collection name and detailed description.
    * Customizable rarity delimiter (defaults to `#`).
    * Control over the edition size (number of artworks to generate).
    * Naming of layer folders, which directly translate to metadata attribute names (e.g., `eyes`, `mouth`, `background`).
    * Image format options such as width and height.
    * [Add any other specific configuration options your UI will expose].
* **Easy Output:** Simple options to download the generated artwork files (likely as a `.zip` archive) and the corresponding metadata.
* **[Add any other unique features your application will offer]**

## Usage

1.  **Access the Application:** Open your web browser and navigate to the following URL:(https://foreverunfinishedartworx.github.io/art_engine/)
2.  **Upload Layers:**
    * You will see a section to upload your artwork layers. You can either drag and drop multiple folders (where each folder represents a trait category and contains the individual layer images) or upload individual image files into designated category folders.
    * Ensure your layer images follow the naming conventions expected by the Art Engine (e.g., `[rarity weight]_[filename].png`).
3.  **Configure Settings:** Fill in the various input fields to customize your artwork generation:
    * Enter the recipient wallet address for payments.
    * Specify the royalty percentage.
    * Provide a name and description for your art collection.
    * Adjust the rarity delimiter if needed.
    * Set the desired number of artworks to generate in the "Edition Size" field.
    * The folder names you uploaded will be displayed as the attribute names for your metadata.
    * Set the desired width and height for the generated images.
    * [Configure any other available options].
4.  **Live Preview (Optional):** As you upload layers and adjust settings, the live preview window will attempt to display a sample of the potential artwork being generated. This gives you a visual idea of how the layers might combine.
5.  **Generate Artwork:** Once you have uploaded your layers and configured the settings, click the "Generate" button.
6.  **Download Output:** Upon successful generation by the back-end, you will be provided with a link or button to download a `.zip` file containing your generated artwork images and the associated metadata files.

## Contributing

While the primary usage of this application is through the web interface, if you are a developer interested in contributing to the codebase, please follow these steps:

1.  **Fork the Repository:** Click the "Fork" button on the top right of the GitHub repository page.
2.  **Create a Branch:** Create a new branch for your changes: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/your-bugfix`.
3.  **Make Your Changes:** Implement your desired changes and ensure the code is well-documented and follows any established code style guidelines.
4.  **Test Your Changes:** Thoroughly test your changes to ensure they are working as expected and do not introduce any new issues.
5.  **Commit Your Changes:** Commit your changes with a clear and concise commit message: `git commit -m "Add feature: Implement XYZ"`.
6.  **Push to Your Fork:** Push your local branch to your forked repository on GitHub: `git push origin feature/your-feature-name`.
7.  **Create a Pull Request:** Go to the original repository on GitHub and click the "New Pull Request" button. Provide a detailed description of your changes and why they should be merged.

## Screenshots/Demo

[**Important:** Once your application has a visual interface, replace this section with actual screenshots or a link to the live demo of the application.]

### Screenshots

* **Layer Upload Section:** [Insert a screenshot of the layer upload area]
* **Configuration Options:** [Insert a screenshot of the input fields for settings]
* **Live Preview:** [Insert a screenshot of the live preview window]
* **Generation Controls:** [Insert a screenshot of the generate and download buttons]
* **[Add more screenshots as needed to showcase key features]**

### Demo

[Link to the live application hosted online: **YOUR APPLICATION URL WILL GO HERE - e.g., yourdomain.com/art-generator**]

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more details.

## Acknowledgements

* This project is built upon the foundation of the incredible  Art Engine](https://github.com-lab/art-engine) by  Lab](https:/.io/).
* [Mention any other libraries, frameworks, or resources you used].

## Contact

[Your Name/Organization Name] - [Your Email Address] - [Your Website/Social Media Link (Optional)]