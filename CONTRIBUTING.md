# 🤝 Contributing

Thanks for your interest in improving this list!

Contributions are welcome in many forms:

- adding missing papers or projects
- fixing broken links
- improving paper metadata
- suggesting better categorization
- clarifying inclusion boundaries
- improving descriptions or formatting

If you are unsure whether a paper fits, feel free to open an issue first. The goal is to keep the list focused while making it easy for people to suggest relevant work.

## ➕ Adding New Papers

Please modify `README.md` and add the paper to the appropriate section using the format below:

- **Short Title**: "Full Title". [![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](LINK) [![Website](https://img.shields.io/badge/Website-Link-blue.svg)](LINK) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](LINK)

Use only the badges that apply.

## 🧩 Adding New Sections

New sections or subsections should be added only if they are clearly aligned with the repository’s core concept:

- **iterative refinement of latent state**
- **shared or recurrent computation across refinement steps**
- **improved performance with additional internal compute**

Do not add new sections for loosely related areas.

## 🔒 Inclusion Criteria

A paper should be added only if it satisfies all of the following:

1. **Iterative refinement of latent state** at inference time
2. **Shared or recurrent computation** across refinement steps
3. **Performance improves with additional internal compute**

## 🕰️ Ordering

Within each subsection, papers should be ordered **chronologically**, from older to newer.

## 🎨 Badge Guide

- **arXiv**: red (`b31b1b`)
- **OpenReview**: purple (`8E44AD`)
- **Website**: blue
- **Code**: green
- **Paper**: blue, for non-arXiv / non-OpenReview primary paper links
- **HuggingFace**: yellow, for model collections or checkpoints

## 📝 Guidelines

- Prefer **arXiv abstract links** over conference, journal, or PDF links whenever available
- Use **OpenReview** when relevant
- Include all available resources when possible
- Use a **short title** only if the paper, or its main proposed method, has a recognizable short title
- Otherwise, use the full paper title directly
- Do not add papers that are only loosely related

## ✅ Examples

With a short title:

- **HRM**: "Hierarchical Reasoning Model". [![arXiv](https://img.shields.io/badge/arXiv-2506.21734-b31b1b.svg)](https://arxiv.org/abs/2506.21734) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/sapientinc/HRM)

Without a short title:

- **Planning in a recurrent neural network that plays Sokoban**. [![arXiv](https://img.shields.io/badge/arXiv-2407.15421-b31b1b.svg)](https://arxiv.org/abs/2407.15421) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/AlignmentResearch/learned-planner)
