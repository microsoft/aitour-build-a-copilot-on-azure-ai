# Source code

All source code for the workshop can be found in the [aitour-WRK550](https://github.com/Azure-Samples/contoso-chat/tree/aitour-WRK550) branch of the Contoso Chat sample repository. The `main` branch is under active development, but this branch will remain stable (and aligned to workshop guide) throughout the tour.

> [!IMPORTANT]  
> The workshop instructions will guide you to fork the repo as a first step. You **MUST** uncheck the "main only" option in order to make sure your fork gets the `aitour-WRK550` branch. 



## Workshop Guide

The instructions for the workshop are contained in the `docs/workshop` folder of the repository as Markdown files - so you can preview it in GitHub or Visual Studio Code. However, it is designed for use with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) which gives the richer interactive experience shown below.

1. Want to explore it? Check out [this hosted version](https://aka.ms/aitour/contoso-chat/workshop) we are maintaining for the tour.
1. Want to run it yourself? Scroll down for details on how you can do this. 

![Workshop Guide](./../img/contoso-chat-workshop.png)

## Manual Preview

The workshop guide files are in the same sample respository as the source code. We assume you already forked the sample to your personal profile for the workshop. To preview docs, do this:

1. Launch GitHub Codespaces on your personal fork of the sample.
1. Change directories to the `docs/workshop` folder
    ```bash
    cd docs/workshop
    ```
1. Launch the `mkdocs` preview server on a port of your choice. I used 5000.
    ```bash
    mkdocs serve -a localhost:5000
    ```
1. Look for a pop-up dialog offering you a choice to open this in a browser window or within a Visual Studio Code preview editor. Click either option to get the preview - and that's it.

---
