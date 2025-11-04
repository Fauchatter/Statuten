
generate French Statutes:
pandoc "2025-11-01 statutes FAU Suisse.md"   --metadata-file=header-fr.yaml --pdf-engine=xelatex    -o "2025-11-01 Statutes FAU Suisse.pdf"FAU Suisse.md"   --metadata-file=head


generate german Statutes:
pandoc "2025-11-01 Statuten FAU Schweiz.md"   --metadata-file=header.yaml    -o "2025-11-01 Statuten FAU Schweiz.pdf"