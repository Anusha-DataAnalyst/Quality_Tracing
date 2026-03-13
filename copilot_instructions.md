# Copilot Instructions for Quality_Tracing

## Repository Overview
Quality_Tracing is a Python demo project that demonstrates traceability practices across requirements, code, and tests, mapped to ISO 25010 quality attributes.

## Repository Structure
- **requirements.md** - Functional requirements (FR-01, FR-02, etc.)
- **src/** - Source code implementation
- **tests/** - Test suite using pytest
- **qualityTracing.md** - Traceability matrix and quality attribute mappings

## Testing
Run tests with:
```bash
pytest
```

## Tracing Format
Use the following comment formats to maintain traceability:

### In source code (links to requirements):
```python
# Trace: FR-01
def function_name():
    pass
```

### In tests (verifies requirements):
```python
# verifies FR-01
def test_function_name():
    pass
```

This ensures every requirement is traceable through code to tests and quality attributes.
