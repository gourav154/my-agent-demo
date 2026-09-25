# My Agent Demo

## Overview

This project demonstrates how to build a simple autonomous agent using the **my-agent-demo** framework. It showcases core functionalities such as prompt handling, tool integration, and response generation.

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/my-agent-demo.git
cd my-agent-demo

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install required dependencies
pip install -r requirements.txt
```

## Usage

Run the demo script to see the agent in action:

```bash
python rag_with_docling_chunks.py
```

You can also import the agent components in your own projects:

```python
from rag_with_docling_chunks import Agent

agent = Agent()
response = agent.run("Your query here")
print(response)
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes with clear messages.
4. Push the branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request describing your changes.

Please ensure that your code follows the existing style guidelines and includes appropriate tests.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.