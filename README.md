# Student dropout prediction

Coursework for CMP6202 (AI and Machine Learning), 2026-27.

I'm using the UCI student dropout dataset to see whether a student's outcome (dropout,
still enrolled or graduate) can be predicted from what the university knows when they
enrol and after their first year. The idea is that a student support team could use
something like this to spot students who might drop out and contact them earlier.

## Data

The data is in `data/data.csv`. It's the original file from UCI, not changed.

- Predict Students' Dropout and Academic Success, UCI Machine Learning Repository
  (https://doi.org/10.24432/C5MC89)
- Licence: CC BY 4.0
- 4,424 students, 36 features, plus the `Target` column
- The file uses `;` as the separator, not `,`

Classes: Graduate 2,209, Dropout 1,421, Enrolled 794. It's quite imbalanced, so
I'm using a stratified split.

Dataset by Realinho, V., Vieira Martins, M., Machado, J. and Baptista, L. (2021).

## Running the code

Still working on this. The notebooks will go in a `notebooks/` folder, and I'll add a
`requirements.txt` with the packages and the steps to run everything.
