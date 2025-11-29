# Project-Patti
This repository contains the Sudoku puzzle datasets used in the research paper "Project Patti: Why can You Solve Diabolical Puzzles on one Sudoku Website but not Easy Puzzles on another Sudoku Website?" (https://arxiv.org/abs/2507.21137)

For this study, Sudoku puzzles were collected from 5 popular Sudoku websites, along with the difficulty level provided by the website. I currently have permission from puzzlemakers for 3 of the 5 websites to release the datasets publicily for academic use only. 

## Sudoku Website Information

### Sudoku.org.uk
- **Difficulties:** Gentle, Moderate, Tough, Diabolical  
- **Release Schedule:**  
  - Gentle – Monday  
  - Moderate – Tuesday, Wednesday, Saturday  
  - Tough – Thursday  
  - Diabolical – Friday, Sunday  
- **Number of Puzzles in Dataset:** 240  
- **Collection Period:** April 15, 2024 – June 5, 2025  
- **Archive Availability:** Publicly available for all released puzzles
- **Link:**  [https://sudoku.org.uk/](https://sudoku.org.uk/)

### Extreme Sudoku
- **Difficulties:** Evil, Excessive, Egregious, Excruciating, Extreme  
- **Release Schedule:** 5 puzzles daily, one of each difficulty  
- **Number of Puzzles in Dataset:** 300  
- **Collection Period:** December 5, 2024 – February 2, 2025  
- **Archive Availability:** Publicly available for all released puzzles
- **Link:**  [https://www.extremesudoku.info/](https://www.extremesudoku.info/)

### Sudoku of the Day
- **Difficulties:** Beginner, Easy, Medium, Tricky, Fiendish, Diabolical  
- **Release Schedule:** 6 puzzles daily, one of each difficulty  
- **Number of Puzzles in Dataset:** 360  
- **Collection Period:** December 17, 2024 – February 20, 2025  
- **Archive Availability:** Archive published for previous week of released puzzles
- **Link:**  [https://www.sudokuoftheday.com/dailypuzzles](https://www.sudokuoftheday.com/dailypuzzles)

In total, the dataset containing all five websites has 1320 puzzles, with 60 puzzles per difficulty level for each website.

## File Structure

The datasets are organized in folders by website. Within each website folder, puzzles are separated into text files by difficulty level (e.g., `Beginner.txt`).

## Puzzle Format

Each puzzle is stored as a single line in the text files, in the following format:

`<date>` : `<81-digit string>`

`<date>`: The date the puzzle was collected, in `MM-DD-YY` format.  
`<81-digit string>`: The Sudoku puzzle represented as a string of 81 digits. The string list the digits of the Sudoku puzzle row by row. Zeros (`0`) indicate empty cells. For example the following Sudoku puzzle (from Sudoku.org.uk) collected from on Januaru 6th, 2025:
<p align="center">
  <img width="364" height="350" alt="image" src="https://github.com/user-attachments/assets/a1b8013f-5030-4075-8ee4-836b91cd1f18" />
</p>


will be converted to the following string: 

`01-06-25:009070800000502700400080020500006002100040005700800009070090003003605000004020600`


## Important Note
Please Note that these datasets are to be used for **academic and research purposes only**. 

