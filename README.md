# ChatBot Pattern Matching - KerangAjaib
> Tugas Besar 3 IF2211 Strategi Algoritma Semester II Tahun 2022/2023 Penerapan String Matching dan Regular Expression dalam Pembuatan ChatGPT Sederhana  
> Live demo [_here_](https://kerang-ajaib-habibibi.vercel.app). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [General Info](#general-information)
* [Program Requirement](#program-requirement)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [How to Use](#how-to-use)
* [Authors](#authors)


## General Information
The search for the question that is most similar to the user-given question is performed with Knuth-Morris-Pratt (KMP) and Boyer-Moore (BM) string matching algorithms. Regex is used to determine the format of the question (explained further in the application features section). If none of the questions in the database is an exact match to the user's question through the KMP or BM algorithms, then the most similar question with at least 90% similarity is used. If there is no question with more than 90% similarity, then the chatbot will provide a maximum of 3 most similar question options for the user to choose from.


## Program Requirement
1. [Node JS](https://nodejs.org/en/)


## Technologies Used
1. [React](https://reactjs.org/)
2. [Express JS](https://expressjs.com/)
3. [Sequelize ORM](https://sequelize.org/)

## Features
1. Text question (obtained from database)
2. Calculator
3. Date
4. Add questions and answers to the database
5. Delete question from database


## Screenshots
![Example screenshot](./doc/screenshot.png)

## How to Use
If you want to check the webiste use this: 

If you want to run it locally just download the repository using `https://github.com/habibibi/KerangAjaib.git` and make sure you have `node js` installed on your machine

0. Setup .env file for each server. For MONGODB_URI, filled it with your personal MongoDB uri.
1. Move to src directory using `cd src`
2. Run `npm run install-all`
3. Run the server with `npm run dev`

## Authors

| Nama                  | NIM      |
| --------------------- | -------- |
| Ahmad Ghulam Ilham | 13521118 |
| Ferindya Aulia Berlianty | 13521161 |
| Muhammad Habibi Husni | 13521169 |



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
