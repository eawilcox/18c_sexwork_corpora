# harrislists
An in-progress corpus and data repository for eighteenth-century sex work research. The repository currently contains transcribed/cleaned text files (including multiple editions/segments) intended for  close reading and future expansion into a more fully structured dataset.

## Usage

1. Browse the corpus  
- `original_texts/` contains source text files (primarily `.txt`, with some `.rtf`) prepared for reading, searching, and downstream processing.
- `xml files` contains the encoded TEI files prepared for later transformation through XSLT

1. Working with the texts
- For quick analysis, you can run plain-text searches (ripgrep/grep) across `original_texts/`.

## Data

Current contents include:

- Multiple files associated with Harris’s List(s) across years/editions (e.g., 1783, 1786, 1788, 1789, 1794), plus smaller excerpted/segmented files.
- Template files:`SWD_Template.xml` (used as a working schema/template for structuring entries).

Data notes:

- File naming conventions generally encode source + year (and sometimes a person/section label).
- Some files are `.rtf` and may require conversion for reproducible text analysis.

## Methods

This repository supports DH workflows that combine:

- Corpus building: collecting, versioning, and documenting transcriptions/editions
- Text preparation: format conversion, cleaning, tokenization, normalization
- Exploratory analysis: keyword searching and iterative expansion of <seg ana="example"> categories
- Future structured data work: moving from plain corpus files toward consistent, machine-readable records (using the provided template as a starting point)

## Citation

Until a formal release is prepared, cite as:

EA Wilcox. *18c_sexwork_corpora* (in-progress repository). GitHub: https://github.com/eawilcox/18c_sexwork_corpora. https://doi.org/10.5281/zenodo.19027604. Accessed YYYY-MM-DD.

If you use a specific file, include the filename and the commit hash in your citation for reproducibility.

## License

License: TBD.
