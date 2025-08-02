# python-sdk
 Python client for ContentVeritas API
```markdown
# ContentVeritas Python SDK

Official Python client library for the ContentVeritas AI Content Authentication API.

## Installation

```bash
pip install contentveritas
```

## Quick Start

```python
from contentveritas import ContentVeritas

# Initialize client
client = ContentVeritas(api_key="your_api_key_here")

# Validate content
result = client.validate("Your text content here")

print(f"AI Probability: {result.consensus_score}")
print(f"Confidence: {result.confidence}")
```

## Features

- ✅ Full API coverage
- ✅ Async support
- ✅ Type hints
- ✅ Error handling
- ✅ Retry logic
- ✅ Response caching

## Documentation

Full documentation available at [docs.contentveritas.com/python-sdk](https://docs.contentveritas.com/python-sdk)

```
