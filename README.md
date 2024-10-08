# [Selector: Interactive Web Interface for Chemical Subset Selection](https://summerofcode.withgoogle.com/programs/2024/projects/JpL7n5Ji)

| **Student** | Jun Xia            |
| :- | :------------------------ |
| **Organization** | [QC-Devs](https://qcdevs.org/)<br />                      |
| **Project** | [Interactive web interface for Selector](https://github.com/theochem/Selector/issues/191) <br />                     |
| **GitHub** | [@](https://github.com/ashaman999)​[JackyZzZz](https://github.com/JackyZzZz)                        |
| **Email** | jackyxia.uci@gmail.com |

# Special thanks to my mentor and community:

* [Fanwang Meng](https://github.com/FanwangM)
* [Paul W. Ayers](https://github.com/PaulWAyers)

# Excited to Explore the Selector Web Interface?
If you're interested in checking out the interface and play around with some chemical data, feel free to explore the [webapp branch](https://github.com/theochem/Selector/tree/webapp).

# Intro

Dear contributors of QC-Devs, 

My name is Jun Xia. I have been selected as a GSoC contributor for our Selector package this year (2024) . I will work on creating a web interface for our Selector package using [Streamlit](https://streamlit.io/), and I will leverage [Docker](https://www.docker.com/) and [Github Actions](https://github.com/features/actions) to deploy the complete application on [HuggingFace](https://huggingface.co/).

Currently, our Selector package is a complete backend application, which makes it difficult for scientists or scholars with minimal coding experience to use our tool. Fortunately, Streamlit simplifies the process of creating interfaces for data-based tools, and I am excited to learn and use this new Python framework for the first time in a real-world application.

You can find the most updated details in the progress log below. (I can be a bit chatty, but I believe this helps me stay motivated and on track with our timeline.) You can also check out our [weekly meeting notes](https://github.com/theochem/Selector/discussions) in the discussion panel.

I am open to suggestions and ideas, so feel free to @ me below to discuss your thoughts.

I am looking forward to a great summer with our project!

# Roadmap

Note that more details about the roadmap may be added to this list as I start to work on them.

- [x] A Web Interface to Perform Subset Selection
  - [x] Home Page 
  - [x] Distance based methods
    - [x] DISE 
    - [x] MaxMin 
    - [x] MaxSum 
    - [x] OptiSim 
  - [x] Partition based methods
    - [x] GridPartition
    - [x] Medoid
  - [x] Converter Page that transform `SMILES` and `SDF` chemical formats into matrix

- [x] Establish a CI/CD Process Using Docker and GitHub Actions 
  - [x] Create a suitable DOCKERFILE
  - [x] Setting up Github Actions pipeline
  - [x] Publish the image on DockerHub

- [x] Deploy the Interface on HuggingFace


# Meeting Notes
- Week 0-1
  - [Meeting Notes for GSoC (5/9/2024)](https://github.com/theochem/Selector/discussions/205)
  - [Meeting Notes for GSoC (5/27/2024)](https://github.com/theochem/Selector/discussions/209)
- Week 3
  - [Meeting Notes for GSoC (6/10/2024)](https://github.com/theochem/Selector/discussions/211)
- Week 4
  - [Meeting Notes for GSoC (6/18/2024)](https://github.com/theochem/Selector/discussions/215)
- Week 6
  - [Meeting Notes for GSoC (7/2/2024)](https://github.com/theochem/Selector/discussions/226)
- Week 7
  - [Meeting Notes for GSoC (7/12/2024)](https://github.com/theochem/Selector/discussions/232)
- Week 10
  - [Meeting Notes for GSoC (8/1/2024)](https://github.com/theochem/Selector/discussions/233)
- Week 11
  - [Meeting Notes for GSoC (8/8/2024)](https://github.com/theochem/Selector/discussions/241)
- Week 12
  - [Meeting Notes for GSoC (8/15/2024)](https://github.com/theochem/Selector/discussions/247)
- Week 13
  - [Meeting Notes for GSoC (8/22/2024)](https://github.com/theochem/Selector/discussions/253)

# Blog

I decided to write blogs to document my progress throughout the project as well. Check it out below😍

- [Week 1-3](https://medium.com/@xiaj8/gsoc-week-1-3-be7ceb35e6c8)
- [Week 4-5](https://medium.com/@xiaj8/gsoc-week-4-5-a5a2edd8fdf0)
