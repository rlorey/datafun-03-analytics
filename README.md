# datafun-03-analytics

> Professional Python project: working with data files for analytics.

# My Analytics Project

> 💡 **Note:** This repository was originally cloned from (https://github.com/denisecase/datafun-03-analytics). I have updated it to include custom analytical visualizations and structural changes required for our week 3 deliverable.


# To Run the Module
uv run python -m datafun.app

## This Project

This project illustrates **ETVL data pipelines** for extracting raw data,
transforming it, verifying results, and loading useful output.

The example project processes four different types of raw data:

- **CSV** - summarizes a numeric column from world happiness data
- **JSON** - counts astronauts by spacecraft
- **XLSX** - counts occurrences of a word in feedback text
- **TXT** - summarizes a plain-text document

Although the data and processing differ,
each pipeline follows the same ETVL structure:
**Extract / Transform / Verify / Load**

Run the example first and read the code
to see how the same workflow is applied to different data.

When you take ownership of the project,
adapt the processing pipelines to generate new analytics.

## Important Folders and Files

- **data/raw/** - raw input data files
- **data/processed/** - output created by the pipelines
- **docs/** - the project narrative and documentation
- **src/datafun/** - the Python instructions
- **zensical.toml** - update authorship & links


## Success

After running this module successfully, you will see the following:

```
===================================
END main() - Executed successfully!
===================================
```


### Original Repository

This module was cloned from https://github.com/denisecase/datafun-03-analytics 


## Data Card

- [Project Data Card](./docs/data-card.md) - with 4 types of files

## Annotations

- [.annotations/annotations.md](./.annotations/annotations.md)

## Citation

- [CITATION.cff](./CITATION.cff)

## License

This project is licensed under the [MIT License](./LICENSE).
