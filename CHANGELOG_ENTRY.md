# Changelog

## [Unreleased] - 2026-08-08

### Features
- **Testing Infrastructure**: Set up comprehensive Python testing infrastructure with Poetry, including pytest, pytest-cov, and pytest-mock as development dependencies. Added testing directory structure with shared fixtures and coverage thresholds
- **String Interpolation**: Add string interpolation support to print function calls for improved code readability
- **File Handling Documentation**: Add note on the removal of comments on encoding to clarify file handling best practices

### Bug Fixes
- **File Position Reset**: Fix issue where file position was not being reset after reading, requiring users to either open/close files multiple times or manually seek to beginning when passing files to multiple functions
- **CLI Typo**: Fix typo in CLI code
- **Documentation Typos**: Fix various typos throughout the codebase, including "chicago" spelling corrections

### Documentation
- **README Updates**: Add Translation Section to README.md and various other README updates for improved project documentation
- **Description Text**: Update description text for better clarity
- **Chapter Notes**: Add notes on chapter 06 documentation

### Chores
- **Dependencies**: Update requirements.txt with Pillow version bump to 8.3.2
- **Code Modernization**: Convert codebase to Python 3 and refactor to apply PEP 8 style guidelines with optimized imports
- **Dependency Management**: Include all dependencies for repository code in package specifications

---

### Installation
- Requires Python 3.x (migrated from Python 2)
- Poetry is now the recommended package manager
- Dev dependencies available: `poetry install --with dev`

