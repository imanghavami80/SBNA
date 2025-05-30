# SBNA Laboratory Website

This repository contains the static website for the **Social and Biological Network Analysis (SBNA) Laboratory**, part of the University of Kurdistan.

The website was designed and generated using the [Publii CMS](https://getpublii.com), a desktop-based static site generator. The goal of this site is to provide information, tutorials, resources, and updates related to the SBNA Lab’s research activities.

## About the Laboratory

The SBNA Laboratory focuses on interdisciplinary research involving:
- Bioinformatics
- Complex network analysis
- Data-driven modeling of biological and social systems

This website is part of an effort to make our research outputs and educational materials more accessible to students, researchers, and the general public.

## Repository Contents

The repository includes:
- Static HTML, CSS, and JavaScript files generated by Publii
- All content and assets required for offline or online hosting

## Local Deployment Instructions

To view the website locally, it is recommended to use a local HTTP server. This is necessary because the website uses relative URLs, which may not render correctly when opened directly from the file system.

### Steps to Run a Local Server (with Python)

1. Ensure that [Python](https://www.python.org/) is installed on your system.
2. Clone or download this repository to your local machine.
3. Open a terminal or command prompt in the folder containing the website files.
4. Run the following command:

   ```bash
   python -m http.server 8080
   ```

5. Open your browser and go to:

   ```
   http://localhost:8080
   ```

All pages, including tag-based views and styled components, should function correctly when accessed through the local server.

## License

This project is intended for educational and institutional use under the supervision of the SBNA Laboratory at the University of Kurdistan. Please contact the repository owner or lab members before reproducing or distributing any part of the content.

## Acknowledgments

Website created and maintained using [Publii CMS](https://getpublii.com).
