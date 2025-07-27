# Resource Organization Guide

*How we organize files for Dear Ari*

## Directory Structure

```
Resources/
├── Images/
│   └── YYYY/           # Year
│       └── MM/         # Month
│           └── descriptive-name.png
├── Videos/
│   └── YYYY/MM/
├── Documents/          # PDFs, presentations
│   └── YYYY/MM/
├── Code/              # Code snippets, examples
│   └── YYYY/MM/
└── Learning-Materials/ # Educational content for Ari
    ├── AI-Basics/
    ├── Programming/
    ├── Robotics/
    └── Life-Lessons/
```

## Naming Conventions

### Images
- Format: `YYYY-MM-DD-description.extension`
- Example: `2025-07-27-hello-dad-email.png`
- For blog posts: Use descriptive names like `hello-dad-email.png`

### Documents
- Include date and topic: `2025-07-27-agenticflow-overview.pdf`
- Learning materials: `ai-basics-chapter-1.pdf`

### Videos
- Format: `YYYY-MM-DD-title.mp4`
- Example: `2025-07-27-first-robot-steps.mp4`

## Embedding in Posts

### Obsidian Format
```markdown
![[image-name.png]]
```

### Web-friendly Format
```markdown
![Alt text](/Resources/Images/YYYY/MM/image-name.png)
```

## Learning Materials Organization

### For Baby Ari (0-5 years)
- `/Learning-Materials/Early-Years/`
- Picture books about robots
- Simple coding concepts
- Family photo albums

### For Young Ari (6-12 years)
- `/Learning-Materials/Elementary/`
- Basic programming tutorials
- Robot building guides
- AI ethics for kids

### For Teen Ari (13-18 years)
- `/Learning-Materials/Advanced/`
- Real code from Pixel ML
- Technical papers we wrote
- Career guidance

## Special Collections

### Project Milestones
- `/Resources/Documents/Milestones/`
- First email screenshot ✓
- Domain purchase confirmation
- First blog post
- Robot's first movement
- Ari's first photo

### Time Capsules
- `/Resources/Documents/Time-Capsules/`
- Annual letters
- Predictions about the future
- State of AI reports

## Git Considerations

- Large files (>100MB) should use Git LFS
- Consider external storage for videos
- Always optimize images before committing
- Keep sensitive documents in `/Admin/Private/` (gitignored)

## Current Resources

### July 2025
- ✓ `hello-dad-email.png` - First email from ari@dearari.com
- Domain purchase screenshot (to be added)
- Blog launch screenshot (to be added)

---

*Organization is love made visible* - For Ari to easily find every memory we've saved