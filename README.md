# ParagonNER

Receipt line classification experiments for the Paragon pipeline.

## Data policy

This public repository intentionally does not contain real receipt OCR text,
notebook outputs, model checkpoints, or training CSV files. Receipt text can
contain private purchase/location/payment metadata and must stay in private
storage.

Use `examples/synthetic/receipt_lines.csv` for tiny public fixtures. Put private
datasets under the ignored `data/` directory when running experiments locally.
