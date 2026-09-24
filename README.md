# Composition-20

**Version 1.0**

Composition-20 is a Windows application designed to determine the amino-acid composition of protein sequences and calculate a cumulative Kyte-Doolittle hydropathicity score.

## Functionality

The program determines the number and percentage of each of the 20 standard amino acids in a protein sequence. It also calculates the cumulative Kyte-Doolittle hydropathicity score of the sequence.

## Input

A protein sequence is pasted into the input field together with an identifier. The program processes the sequence and excludes characters that do not represent the 20 standard amino acids.

## Output

Composition-20 reports:

- The number of occurrences of each amino acid
- The percentage composition of each amino acid
- The cumulative Kyte-Doolittle hydropathicity score

Results can be saved for subsequent analysis.

## Validation

The program was validated using a test sequence consisting of five repeats of the English alphabet. Each of the 20 standard amino-acid letters therefore occurred five times and was expected to represent 5.0% of the analyzed amino acids.

The program correctly reported each of the 20 standard amino acids at 5.0%. Letters that do not represent standard amino acids (B, J, O, U, X, and Z) were excluded.

Additional protein sequences were also analyzed to verify the operation of the program.

## Installation and requirements

- **Operating system:** Microsoft Windows
- **Application type:** Windows Forms application
- **Framework:** .NET 9.0 for Windows

A ready-to-install version of Composition-20 is available under **Releases** on this GitHub repository.

## How to use

1. Install and start Composition-20.
2. Paste the protein sequence into the sequence input field.
3. Enter an identifier for the sequence.
4. Perform the analysis.
5. Review the amino-acid composition and cumulative hydropathicity score displayed by the program.
6. Save the results if required.

For illustrated instructions and additional details, see **README-Composition-20-1.docx** included in this repository.

## Limitations

Sequence entry is performed manually. The program has been tested with protein sequences containing up to approximately 25,000 amino acids.

## Source code

The source code is not included in this release.

## Author

Copyright © 2026. All rights reserved.
