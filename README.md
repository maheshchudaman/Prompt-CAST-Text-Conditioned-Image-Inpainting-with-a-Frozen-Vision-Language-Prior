# Prompt-CAST: Text-Conditioned Image Inpainting with a Frozen Vision-Language Prior

Paper draft. This repository holds the manuscript only — the reference implementation lives at
[github.com/maheshchudaman/Prompt-CAST](https://github.com/maheshchudaman/Prompt-CAST).

## Status

This is a **draft**, not a submitted or camera-ready paper. It reports one verified real result (the
unconditional CAST-Net baseline on ADE20K, Section 5) and is explicit throughout — especially in
Section 6, "Limitations and Planned Evaluation" — about what has not yet been run: full-scale
text-conditioned training, a CLIP-score evaluation, and comparisons against both the unconditional
baseline and a diffusion-based text-guided inpainting system.

## Files

- `PromptCAST_Draft.docx` — editable manuscript
- `PromptCAST_Draft.pdf` — rendered PDF

## Related repositories

- Code: [Prompt-CAST](https://github.com/maheshchudaman/Prompt-CAST)
- Verified baseline referenced in Section 5: [CAST-Net-Full-Seed42-RTX4050](https://github.com/maheshchudaman/CAST-Net-Full-Seed42-RTX4050)
- Base architecture: [CAST-Net](https://github.com/maheshchudaman/CAST-Net)
