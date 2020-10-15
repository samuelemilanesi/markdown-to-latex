# Markdown to latex

## Files
- `style-header.tex`: latex header file optimized to manage code blocks with *solarized light* theme 

## Requirements 
- tex-live (latex package)
- pandoc 

## Usage
Export `example.md` in latex-style pdf using: 
```bash
pandoc example.md --listings -H style-header.tex -o outputName.pdf  
```
