
# Thesis experiment 

## Overview

This repository contains code of experiments performed as part of my research titled **Comparative Evaluation Of Prompting Techniques For Financial Text Analysis With Explainable AI: A Multi-Task Study On Sentiment Classification, Question Answering, and Topic Detection**. I conducted this research as part of my Masters In Machine Learning and Artifical Intelligence.

The research evaluated impact of different prompting techniques on outputs geneerated by LLMs for various financial text analysis tasks such as Sentiment Classification, Question Answering and Topic Detection. The experiments are performed on open-sourced LLMs of different sizes. This research aims to compare different prompting techniques for different financial tasks and identify best prompting techniques specific to each task in combination with LLMs.

## How to user this repository

This repository contains code of research experiments. All the code files are inside **Experiments** folder. Futher code is divided in to four folders, each for one prompting strategy. Inside each prompting folder, there for sub-folders belonging to each LLMs.

Code is written in python notebook. Each notebook is given name specific to the prompting technique and LLM for which the experiment code written in it.

Steps to run the code on local machine.

1. Clone the repository on local machine.
2. Open the repository folder in suitable code editor such as VS Code or cursor.
3. Open terminal/command prompt in the code editor.
4. Initiate Python virtual environment.
5. Install ipykernel using command `pip install ipykernel`.
6. Create a new file with name .env at the root of the repository folder.
7. Add Groq API key in the .env file with format `GROQ_API_KEY=<<grok_api_key>>`
8. Open python notebook of your interest.
9. Start executing cells one by one.

After all the cell executed in a notebook, result of execution are saved under `Outputs` folder inside the root directory of the repository.

## Disclaimer

The content of this repository is provided for academic and research purposes only. The results and conclusions presented are based on specific models and techniques as detailed in the thesis. While every effort has been made to ensure the accuracy of the data and findings, variations may occur depending on the context and application of these methods. Users are advised to apply the information contained in this repository at their own discretion and risk.

## Copyright

© 2025 Chetanbhai Ranpariya. All rights reserved. Unauthorized use of the materials contained in this repository without permission is strictly prohibited.