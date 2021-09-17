# Convert to PDF

Install `pandoc`:

```
sudo apt install pandoc texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra
```

Convert:

```
pandoc README.md --variable urlcolor=cyan -o laura_martin_cv_$(date +%F).pdf
```
