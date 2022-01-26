# Turku layout corpus

Corpus of Finnish open access publications with layout annotations

## Repository contents

- `original-documents/`: original PDF documents
- `metadata/`: [OAI-PMH](https://www.openarchives.org/pmh/) metadata for each PDF document, including license terms
- `coco/annotations.json`: annotations in [https://cocodataset.org/](COCO) format
- `coco/images/`: images extracted from PDF documents, one image per page

The data found in the `coco/` directory was generated from documents
annotated in the [PAWLS](https://github.com/allenai/pawls) annotation tool,
exported using the PAWLS CLI command `pawls export [...] coco`.
