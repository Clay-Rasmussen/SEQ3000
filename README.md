# SEQ3000

## Overview
___
This project is a COBOL program designed to perform sequential file maintenance on employee records. It processes an existing employee master file alongside a transaction file containing HR actions (add, delete, change). The program generates an updated master file and an error file for invalid transactions while following a balanced-line algorithm for accurate record comparison and updates.

## Table of Contents
___
* [New Concepts](#new-concepts)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Running Output](#running-output)
* [Learning Outcomes](#learning-outcomes)
* [Help](#help)
* [Authors](#authors)

### New Concepts
___
# RPT6000 Assignment – New Concepts

This assignment introduced working with sequential files, indexed files, and COBOL sort/merge features, along with implementing file validation and structured file processing logic.

## Chapter 13 – How to Work with Sequential Files
---
Sequential files are processed in order, one record at a time. In this project, a sequential employee master file and a transaction file were read simultaneously using a balanced-line algorithm to compare employee IDs and determine updates, additions, or deletions.


## Chapter 14 – How to Work with Indexed Files
---
Indexed files allow faster access to records using keys rather than strict sequential order. Although not fully implemented, this concept expands on how large datasets can be accessed efficiently compared to sequential processing.

## Chapter 16 – How to Use the Sort/Merge Feature
---
COBOL’s sort/merge functionality helps organize and combine large datasets. This concept supports file processing tasks like ensuring transaction files are properly ordered before applying updates to a master file.

## Tech Stack
___
* ![COBOL](https://img.shields.io/badge/COBOL-Enterprise-blue)
* ![Visual Studio Code](https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)

## Installation
___
1. Clone the repository to your local machine. (or just steal my code)
2. Put the code into VS Code in your mainframe of choice

## Running Output
___
![Code Running](assets/SEQ3000RunningOutput.png)

## Learning Outcomes
___
* Learned how to process and maintain sequential files using COBOL
* Implemented the balanced-line algorithm for comparing master and transaction records
* Gained experience handling file I/O operations with multiple input and output files
* Applied data validation and error handling, including file status checking
* Developed logic to handle real-world HR transactions such as hiring, termination, and updates
* Improved understanding of structured COBOL program design

## Help
___
* Make sure compiler is running correctly.
* Potentially re-clone repository
* restart IDE

## Authors
___
<img src="https://github.com/Clay-Rasmussen.png" alt="Profile Picture" width="100" />

**Clay Rasmussen**
* **Clay's GitHub Profile**: [Clay-Rasmussen](https://github.com/Clay-Rasmussen)
* **Clay's Email**: [clrasm02@wsc.edu](mailto:clrasm02@wsc.edu)

[Back to the top](#overview)
