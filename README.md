# ISDM Group-2
Group Project


## pandoc

To convert markdown to pdf using `pandoc`, first install the following packages:
```
sudo apt install pandoc texlive-latex-recommended texlive-fonts-recommended
```

Then run the following command to convert markdown to pdf:
```
pandoc report.md -s -o report.pdf
```

## markdown-pdf

To convert markdown to pdf using `markdown-pdf`, first install the following package:
```
npm install markdown-pdf
```

Then run the following command to convert markdown to pdf:
```
npx markdown-pdf report.md
```
