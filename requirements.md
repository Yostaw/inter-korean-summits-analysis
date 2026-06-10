# Requirements

## Software

- Orange Data Mining
- Orange Text Mining add-on
- Python 3.x

## Additional Resources

The Orange workflow uses the following external resources:

- Kiwi Korean morphological analyzer
- Python Script widgets
- Custom Korean stopword lists
- Korean sentiment lexicons (positive and negative word lists)

These resources are required to fully reproduce the analysis.

## Operating System

- Windows or macOS

## Reproducing the Analysis

1. Open the Orange workflow file located in the `analysis` folder.
2. Ensure that all required scripts, stopword lists, and sentiment lexicons are available.
3. Load the dataset used in this study.
4. Run the workflow to reproduce the analyses and figures presented in the paper.

## Platform-Specific Scripts

Separate preprocessing scripts are provided for Windows and macOS users.

## Repository Structure

- `analysis/` contains the Orange workflow (.ows)
- `data/` contains dataset documentation
- `figures/` contains figures used in the paper
- `scripts/` contains Python scripts used in Orange
- `resources/` contains stopword lists and sentiment lexicons