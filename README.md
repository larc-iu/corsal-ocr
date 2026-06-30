# CoRSAL-OCR

Code and documentation for CoRSAL-OCR, an OCR evaluation dataset
of 200+ document pages with gold-standard transcriptions from two South
Asian languages drawn from the CORSAL digital archive.

| Code | Language | Script | Pages | Ethnologue |
|---|---|---|---|---|
| brx | Bodo | Devanagari | 53 | [brx](https://www.ethnologue.com/language/brx/) |
| grt | Garo | Latin | 151 | [grt](https://www.ethnologue.com/language/grt/) |

The dataset itself (images + text, ~230MB) is published on Hugging Face at
**https://huggingface.co/datasets/larc-iu/corsal-ocr**.

This repository hosts the license, changelog, and citation for the dataset.
It does not contain the dataset itself (see Hugging Face above) or the raw
archive and annotation data used to build it.

## Versioning

See [change log](./CHANGELOG.md) for release notes.

## License

This repository is MIT-licensed (see `LICENSE`). The dataset itself is
CC-BY-4.0; see the dataset card on Hugging Face for details.

## Citation

```bibtex
@inproceedings{gessler-haynes-2026-corsal,
    title = "{C}o{RSAL}-{OCR}: Evaluating Zero-Shot {OCR} for Language Archive Materials",
    author = "Gessler, Luke  and
      Haynes, Andrew",
    editor = "Agyapong, Godfred  and
      Moeller, Sarah  and
      Arppe, Antti  and
      Marashian, Ali  and
      Rosenblum, Daisy",
    booktitle = "Proceedings of the Ninth Workshop on the Use of Computational Methods in the Study of Endangered Languages ({C}omput{EL}-9)",
    month = jul,
    year = "2026",
    address = "San Diego, California, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.computel-1.14/",
    pages = "125--135",
    ISBN = "979-8-89176-422-4",
}
```
