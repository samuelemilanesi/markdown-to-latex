# Markdown to latex

## Files
- `style-header.tex`: latex header file optimized to manage code blocks with *solarized light* theme 

## Requirements 
- linux distro
- tex-live (latex package)
- pandoc 

## Usage
- Write your markdown file and save it as `example.md`
- Export it in pdf using: 
```bash
pandoc example.md --listings -H style-header.tex -o outputName.pdf  
```
