# Automated_script
bash program is a fully automated command line with a graphical user interface. 

This project comprises a series of automated bash scripts designed to facilitate various bioinformatics tasks, including pairwise alignment, multiple sequence alignment (MSA), conversion from FASTQ to FASTA format, and k-mer analysis. The scripts utilize user-friendly menus provided by the `whiptail` tool for interactive operation.

## Usage
1. Run the main script `main_script.sh`.
2. Choose the desired operation from the menu.
3. Follow the prompts and provide necessary inputs when prompted.

## Scripts Overview
- **Pairwise Alignment:** Allows users to perform pairwise sequence alignment using either local or global alignment algorithms.
- **Multiple Sequence Alignment (MSA):** Enables users to conduct MSA using popular algorithms such as Muscle or Kalign.
- **FASTQ to FASTA Conversion:** Converts input FASTQ files to FASTA format.
- **K-mers Analysis:** Performs k-mer analysis on input sequences.

## Requirements
- `whiptail`: A utility for creating user-friendly dialog boxes from shell scripts.
- Bioinformatics tools such as BLAST, Muscle, Kalign, and others, depending on the chosen operation.

## Installation and Setup
1. Clone the repository to your local machine.
2. Ensure that all required bioinformatics tools are installed and accessible from the command line.
3. Run the main script `main_script.sh` to initiate the interactive menu.

## Notes
- Ensure that all input files are correctly formatted and located in accessible directories.
- Follow the prompts carefully to provide required inputs and make selections.

