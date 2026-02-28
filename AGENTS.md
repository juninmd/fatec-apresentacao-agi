```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure the efficient, maintainable, and robust development of AI coding agents within this repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data models, and utility functions must be implemented once and reused across multiple agents and components.
*   Avoid duplicating code segments; refactor existing code to minimize redundancy.
*   When implementing a new functionality, consider if there's a reusable component or pattern that can avoid repeating the logic.

## 2. KISS (Keep It Simple, Stupid)

*   Code should be concise and easy to understand.
*   Avoid unnecessary complexity.
*   Prioritize readability and clarity over rapid implementation.
*   Use the simplest solution that meets the requirements.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each agent, component, and function should have a single, well-defined purpose.
*   **Open/Closed Principle:** Agents should be extensible through well-defined interfaces, without modifying the core logic.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace base classes without affecting the correctness of the system.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they don’t use.
*   **Dependency Inversion Principle:** Components should be independent of each other and their dependencies.  Higher-level modules should not depend on lower-level modules.

## 4. YAGNI (You Aren’t Gonna Need It)

*   Only implement functionality that is currently required.
*   Defer implementation of future requirements to future versions of the code.
*   Avoid adding unnecessary complexity.  Focus on solving the current problem.

## 5. Testing & Code Quality

*   **All development must be productive.** Continuous integration and automated testing are critical.
*   **Mocks ONLY for Tests.**  Mocking is exclusively used for integration and end-to-end testing. No real implementations.
*   **Unit Tests:**  Each agent and component must have comprehensive unit tests covering all core functionalities.
*   **Integration Tests:**  Thorough integration tests to verify agent interactions.
*   **Test Coverage:**  Minimum 80% coverage is required.  Automated test suites are essential.
*   **Code Style:** Follow established coding style guidelines (e.g., PEP 8). Use a linter for automatic code formatting.
*   **Comments:**  Provide clear and concise comments to explain complex logic, algorithm choices, and the purpose of code sections.  Keep comments up-to-date with changes.

## 6. File Size & Structure

*   **Maximum Code Length:** 180 lines of code.
*   **File Structure:** Organize code into logical components and classes.
*   **Clear File Naming:** Use descriptive file names that indicate the component's purpose.
*   **Documentation:**  Include a brief introduction to the file’s purpose and key components in the file header.
*   **Version Control:**  Use Git for version control.

## 7. Specific Considerations

*   **Agent ID Management:** Implement a robust agent ID management system.
*   **Data Handling:**  Design data structures for efficient storage and retrieval.
*   **Error Handling:** Implement comprehensive error handling and logging mechanisms.
*   **Configuration:**  Provide a flexible configuration mechanism for agents.
*   **API Design:**  Consider the design of the API used by agents.  Keep it minimal and focused.


These guidelines are intended as a starting point and may be subject to change as the project evolves.  Regular review and updates are encouraged.  Any deviation from these guidelines will be considered a violation of these principles.
```