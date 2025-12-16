# Resume - Dylan Sutro

This folder contains the LaTeX source files for Dylan Sutro's resume.

## Files

- `DylanSutro_Resume.tex` - LaTeX source file
- `DylanSutro_Resume.pdf` - Compiled PDF (generated from .tex file)

## Compiling the Resume

### Option 1: Using pdflatex (Local)

If you have LaTeX installed:

```bash
cd resume
pdflatex DylanSutro_Resume.tex
pdflatex DylanSutro_Resume.tex  # Run twice for proper references
```

### Option 2: Using Overleaf (Recommended)

1. Go to [Overleaf.com](https://www.overleaf.com/)
2. Create a new project
3. Upload `DylanSutro_Resume.tex`
4. Overleaf will automatically compile and show you a preview
5. Download the PDF when ready

### Option 3: Using VS Code Extension

1. Install "LaTeX Workshop" extension in VS Code/Cursor
2. Open the .tex file
3. Use the build command (usually Cmd+Option+B on Mac)
4. The PDF will be generated in the same folder

## Updating the Resume

1. Edit `DylanSutro_Resume.tex` with your information
2. Compile to generate new PDF
3. The website will automatically use the updated PDF

## Notes

- The template uses the `moderncv` class for a professional look
- Make sure to fill in all placeholder dates and details
- Keep the PDF updated in this folder for the website download link

