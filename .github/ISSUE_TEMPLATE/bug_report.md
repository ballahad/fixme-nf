---
name: Bug report
about: Create a report to help us improve the pipeline
title: '[BUG] '
labels: ['bug']
assignees: ''

---

## Bug Description
A clear and concise description of what the bug is.

## Steps to Reproduce
Steps to reproduce the behavior:
1. Command used: `nextflow run ...`
2. Profile used: (e.g., `-profile docker`, `-profile conda`)
3. Operating system: (e.g., macOS, Linux, Windows)
4. Architecture: (e.g., Intel/AMD64, Apple Silicon/ARM64)

## Expected Behavior
A clear and concise description of what you expected to happen.

## Actual Behavior
A clear and concise description of what actually happened.

## Error Messages
```
Paste any error messages here
```

## Environment Information
- **Nextflow version**: (run `nextflow -version`)
- **Docker version**: (run `docker --version` if using Docker)
- **Conda version**: (run `conda --version` if using Conda)
- **Operating System**: 
- **Architecture**: 

## Work Directory
If applicable, provide the path to the work directory where the error occurred:
```
work/xx/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

## Additional Context
Add any other context about the problem here. Include any modifications you made to the pipeline.

## Checklist
- [ ] I have checked the existing issues to make sure this is not a duplicate
- [ ] I have included the complete error message
- [ ] I have specified my environment details
- [ ] I have tried running with `-resume` if this was a re-run 